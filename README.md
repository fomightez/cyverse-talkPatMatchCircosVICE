Short link to share to this page is [bit.ly/CyverseWayne](http://bit.ly/CyverseWayne)

# Resource listing to Wayne's May 17th Cyverse Talk

Resource listing for accompanying Wayne's Cyverse talk on the PatMatch and Circos Binders and VICE apps (May 17th, 2019).

Cyverse
------

- [Cyverse Portal to get to the Discover Environment](https://user.cyverse.org/services/mine)

VICE apps in Cyverse's Discovery Environment
--------------------------------------------

- [Visual Interactive Computing Environment(VICE) Guide](https://learning.cyverse.org/projects/vice/en/latest/index.html)
- [List of VICE Apps in DE](https://learning.cyverse.org/projects/vice/en/latest/vice_apps/examples.html)
- [VICE Starting JupyterLab App](https://cyverse-visual-interactive-computing-environment.readthedocs-hosted.com/en/latest/user_guide/quick-jupyter.html) 
- [VICE Webinar](https://www.youtube.com/watch?v=KpBC0nScfL0)
- see [Making VICE Apps](#making-vice-apps) below

----

PatMatch-Binder and VICE app
----------------------------

[PatMatch Binder and Vice App Github repo](https://github.com/fomightez/patmatch-binder)

[Example PatMatch at the Yeast Genome Database](https://www.yeastgenome.org/nph-patmatch) - In particular look at the 'Supported Pattern Syntax and Examples' at the bottom

**ADD LINK TO QUICK START**

Need something else:
- [RNAPattMatch web server](https://academic.oup.com/nar/article/43/W1/W507/2467908); several others mentioned therein

Circos-Binder and VICE app
---------------------------

[Main Circos site](http://circos.ca/)

[Genomic Conservation illustration featuring what Circos excels at and seves as a guide to reading the plots](http://circos.ca/guide/genomic/img/circos-conservation.png)

[Circos Binder and Vice App Github repo](https://github.com/fomightez/circos-binder)

**ADD LINK TO QUICK START**

**TO DO: make (or find if it is already in the demo notebooks) an example of scaling up to analyze many genomes at once?

### Alternatives

Other tools for similar circular (and non-circular) visualization.  
This is not meant to be an exhaustive listing.

#### Command-line/ Script based

- [Chord diagrams](https://www.data-to-viz.com/graph/chord.html#)
- [RCircos package](https://bitbucket.org/henryhzhang/rcircos/src/master/vignettes/RCircosLayoutDemo.png)
- [CIRCULAR PLOT – CIRCLIZE PACKAGE (2)](https://www.r-graph-gallery.com/123-circular-plot-circlize-package-2/)
- [Circoletto ](https://www.ncbi.nlm.nih.gov/pubmed/20736339) - Front-end to Circos that allows visualizing BLAST sequence comparison results; *lists that it includes a downloaded software package version as well as Webtool described below.*
- [karyoploteR](https://bernatgel.github.io/karyoploter_tutorial/#Examples) - for linear
- [EasyFig](https://github.com/mjsull/Easyfig/wiki/Example-1.-Simple-genome-region-comparison) - for linear and sub-regions
- [Donut plot with subgroups](https://python-graph-gallery.com/163-donut-plot-with-subgroups/) to contrast [Circos with highlights (specifically bottom plot here)](http://circos.ca/documentation/tutorials/highlights/recipe2/images) .

#### Webtools

- [Circos Online](http://mkweb.bcgsc.ca/tableviewer/)
- [Circoletto ](http://tools.bat.infspire.org/circoletto/#info) - Front-end to Circos that allows visualizing BLAST sequence comparison results
- [Circa](http://omgenomics.com/circa/)($) and Chordial ($)
- [CiVi: User-friendly Circular Visualization for microbial genomes](http://civi.cmbi.ru.nl/) but limited to the microbes (currently 2773) they have
- NCBI's [Genome Decoration Page](https://www.ncbi.nlm.nih.gov/genome/tools/gdp/) enables annotating on cytoogenetic representations.

### Unsorted

- Discussion [here](https://twitter.com/BioMickWatson/status/1011231099203223552)
- [Simple alternatives for the program Circos](https://www.biostars.org/p/336589/#336693)



Getting started with Circos
---------------------------



Required:
- karyotype
- ideogram

Meant to be reminiscent of actual cytogenetic [karyotype](https://www.nature.com/scitable/topicpage/karyotyping-for-chromosomal-abnormalities-298) related data concepts and how you would represent it as an [ideogram](https://en.wikipedia.org/wiki/Ideogram). Borrows much from traditional linear representations of this data as  [chromosome ideograms /idiograms / karyograms](https://en.wikipedia.org/wiki/File:Ideogram_human_chromosome_1.svg).


A good way to proceed is to find an example close to what you want, that has code associated, and work on making that and integratinbg your data. Sources of images and code:

- [TUTORIAL IMAGES](http://circos.ca/tutorials/images/large/) - a page with interactive thumbnails of the tutorial images on one page
- [The Circos Google group discussion list](https://groups.google.com/forum/#!forum/circos-data-visualization) - users often post code there with accompanying images

Finding a basis for what you want to make?
- Literature
- [Circos IMAGES IN SCIENTIFIC LITERATURE page](http://circos.ca/intro/published_images/)
- [Circos VARIOUS SAMPLE IMAGES page](http://circos.ca/images/samples/)
- [Circos PLOT TYPES page](http://circos.ca/intro/features/)
- [Circos APPLICATION OF CIRCOS TO GENOMICS](http://circos.ca/intro/genomic_data/)
- [TUTORIAL IMAGES](http://circos.ca/tutorials/images/large/) - a page with interactive thumbnails of the tutorial images on one page
- and more on [Main Circos site](http://circos.ca/)

----

Pertinent recent Cyverse Friday Focus Forum Webinars
-------------------------------------------------
-  [Deploying scalable interactive Bioinformatics analyses via VICE](https://wiki.cyverse.org/wiki/display/Events/FFW%3A+Deploying+scalable+interactive+Bioinformatics+analyses+via+VICE) by Peter Rose
- [Doing metagenomic analyses with QIIME 2 using Jupyter Notebooks in VICE](https://wiki.cyverse.org/wiki/display/Events/FFW%3A+Doing+metagenomic+analyses+with+QIIME+2+using+Jupyter+Notebooks+in+VICE) by  Joslynn Lee
- [Easier with containers](https://wiki.cyverse.org/wiki/display/Events/FFW%3A+Easier+with+containers) by Julian Pistorius
- [Going places with your containers](https://wiki.cyverse.org/wiki/display/Events/FFW%3A+Going+places+with+your+containers) by Tyson Swetnam
- [VICE Webinar](https://www.youtube.com/watch?v=KpBC0nScfL0)


Making VICE Apps
---------------

- [Guidelines for adding VICE tools in DE](https://learning.cyverse.org/projects/vice/en/latest/developer_guide/adding.html)
- [Building VICE tools and apps](https://learning.cyverse.org/projects/vice/en/latest/developer_guide/building.html)



Jupyter and Binder
------------------

**Importantly** Jupyter is langauage agnostic!  
What I covered here today only touched on Python and the bash shell languages because the fromer is the language I presently work in most often. However, Jupyter can host an R kernel and the hub can even serve RStudio. Other langauges are possible too.

- [VICE Starting JupyterLab App](https://cyverse-visual-interactive-computing-environment.readthedocs-hosted.com/en/latest/user_guide/quick-jupyter.html) 
- [MyBinder.org](https://mybinder.org/)
- [Sample Binder Repositories as Guides](https://mybinder.readthedocs.io/en/latest/sample_repos.html)
- Scientific Examples in the wild:
  - [Peter Rose's mmtf-genomics](https://github.com/sbl-sdsc/mmtf-genomics)
  - [Python for ecologists, a Data Carpentry lesson](https://github.com/ngs-docs/2017-davis-ggg201a-day1)
  - [Introductory image processing on biological images using python](https://github.com/dwaithe/model-training)
  - [ssbio: structural systems biology](https://github.com/SBRG/ssbio)
  - [ipyvolume: 3d plotting for Python](https://github.com/maartenbreddels/ipyvolume/)
  - [VPython running in a Jupyter notebook](https://github.com/BruceSherwood/vpython-jupyter)
  - [The interaction between simulation and scattering](https://pythoninchemistry.org/sim_and_scat/intro.html)
  - [LIGO data analysis](http://github.com/gwastro/pycbc) - package was used in the first direct detection of gravitational waves
- [Juliette Taka's Reproducible Science and Binder system infographic](https://opendreamkit.org/public/images/use-cases/reproducible_logbook.png) for [OpenDreamKit](https://opendreamkit.org/2017/11/02/use-case-publishing-reproducible-notebooks/)
- [Binder Documentation](https://mybinder.readthedocs.io/en/latest/index.html)
- [Jupyter and Binder Community Forum](https://discourse.jupyter.org/)
- [Introducing Binder 2.0 — share your interactive research environment](https://elifesciences.org/labs/8653a61d/introducing-binder-2-0-share-your-interactive-research-environment)
- [Ten Simple Rules for Reproducible Research in Jupyter Notebooks](https://arxiv.org/abs/1810.08055) , with accompanying demo notebooks with biological workflows illustrated [here](https://github.com/jupyter-guide/ten-rules-jupyter)

Training
--------

- [Learning at CyVerse](https://www.cyverse.org/learning)
- [Foundational Open Science Skills camp](https://www.cyverse.org/foss)
- [The Carpentries: Teaching foundational coding and data science skills to researchers worldwide](https://carpentries.org/) - There lessons form the basis of Software Carpentry and Data Carpentry workshops. Lots of the lessons and content are available to explore or schedule a workshop.
- Data Intensive Biology Summer Institute - See [here](http://ivory.idyll.org/dibsi/index.html) for the [advertisment for the 2019 version of Titus Brown and Colleagues' Sequence Analysis (ANGUS)/Data Intensive Biology Summer Workshop](http://ivory.idyll.org/dibsi/ANGUS.html). Registration for this year closes soon, but be prepared for next yeat by [joining the dibsi-announce mailing list](https://groups.io/g/dibsi-announce/join).  
**The course content for recent years (plus more done by Titus and DIBSI is shared [here](https://dib-training.readthedocs.io/en/pub/).**


Acknowledgements
----------------

- Martin Krzywinski who developed Circos and made the site and authored the content to help people learn it
- PatchMatch authors - Yan T, Yoo D, Berardini TZ, Mueller LA, Weems DC, Weng S, Cherry JM, Rhee SY.
- [MyBinder Team](https://jupyterhub-team-compass.readthedocs.io/en/latest/team.html#binder-team)
- [Cyverse Team](https://www.cyverse.org/staff). In particular, I'd lke to directly thank Upendra Devisetty, Tina Lee, and Shelley Littin.
- Department of Biochemistry and Molecular Biology at Upstate Medical University
- [Stacia Sower](https://www.unhsowerlab.com/) for sending me to Titus Brown and colleagues' Data Intensive Summer Biology Workshop. See below for more info about that. 
- Data Intensive Biology Summer Institute - See [here](http://ivory.idyll.org/dibsi/index.html) for the [advertisment for the 2019 version of Titus Brown and Colleagues' Sequence Analysis (ANGUS)/Data Intensive Biology Summer Workshop](http://ivory.idyll.org/dibsi/ANGUS.html). Registration for this year closes soon, but be prepared for next yeat by [joining the dibsi-announce mailing list](https://groups.io/g/dibsi-announce/join).
- [Peter Rose's mmtf-genomics](https://github.com/sbl-sdsc/mmtf-genomics) serves as an excellent guide for how to integrate Cyverse use with previously binderized tools and making clear documentation.
