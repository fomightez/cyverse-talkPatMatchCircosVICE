Short link to share to this page is [bit.ly/CyverseWayne](http://bit.ly/CyverseWayne)

# Resource listing to Wayne's May 17th CyVerse Friday Focus Webinar

Resource listing for accompanying Wayne's webinar on the PatMatch and Circos Binders and VICE apps (May 17th, 2019).  
More info and video of the webinar can be found on the CyVerse wiki [here](https://wiki.cyverse.org/wiki/display/Events/FFW%3A+Scan+and+Visualize+Genomes+with+PatMatch+and+Circos+in+VICE). 

-----

## Overview: Underlying Tech We'll Capitalize On

- [Juliette Taka's Reproducible Science and Binder system infographic](https://opendreamkit.org/public/images/use-cases/reproducible_logbook.png) for [OpenDreamKit](https://opendreamkit.org/2017/11/02/use-case-publishing-reproducible-notebooks/)
- CyVerse



----

PatMatch-Binder and VICE app
----------------------------

[PatMatch Binder and Vice App Github repo](https://github.com/fomightez/patmatch-binder)

[CyVerse QuickStart page for PatMatch](https://cyverse-patmatch-quickstart.readthedocs-hosted.com/en/latest/)

[Example PatMatch at the Yeast Genome Database](https://www.yeastgenome.org/nph-patmatch) - In particular look at the 'Supported Pattern Syntax and Examples' at the bottom


Need something else? (not meant to be exhaustive):
- [Fragrep: An Efficient Search Tool for Fragmented Patterns in Genomic Sequences](https://www.sciencedirect.com/science/article/pii/S167202290660017X)
- [Sequence Pattern Mining Based on Markov Chain](https://ieeexplore.ieee.org/document/7429136) - probability matrix based
- [Designing patterns for profile HMM search](https://academic.oup.com/bioinformatics/article/23/2/e36/203891)
- [RNAPattMatch web server](https://academic.oup.com/nar/article/43/W1/W507/2467908); several others mentioned therein
- [Infernal](http://eddylab.org/infernal/)
  >"Infernal is a software package that implements “covariance models” (CMs) for RNA homology search, which harness both sequence and structural conservation when searching for RNA homologs. 
- [RNABOB](https://github.com/bgruening/galaxy-rna-workbench#rna-structure-prediction-and-analysis) as part of the Galaxy-based [RNA workbench 2.0](https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gkz353/5487675)- a probe motif is specified in a descriptor file, which describes its primary sequence, secondary structure, and tertiary constraints
- [pure Python `find sequence elements in sequence data` script](https://github.com/fomightez/sequencework/tree/master/FindSequence) - no biologically specific wild-cards, though regular expressions allowed
- [Biostrings vmatch function in R](https://twitter.com/strnr/status/986215833453113344); see more about vmatch user under section 5 [Biostrings and BSgenome basics by Herve Pages and Patrick Aboyoun](https://bioconductor.org/help/course-materials/2009/SeattleNov09/Biostrings/BiostringsBSgenomeBasics.pdf)
- Other related software is noted in [the paper describing PatMatch](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1160129/) and on the page for [launching PatMatch in your browser](https://github.com/fomightez/patmatch-binder).

----

## Overview Part II: Underlying Tech We'll Capitalize On /CyVerse Benefits


CyVerse
------

- [CyVerse Portal to get to the Discover Environment](https://user.cyverse.org/services/mine)

VICE apps in CyVerse's Discovery Environment
--------------------------------------------

- [Visual Interactive Computing Environment (VICE) Guide](https://learning.cyverse.org/projects/vice/en/latest/index.html)
- [List of VICE Apps in DE](https://learning.cyverse.org/projects/vice/en/latest/vice_apps/examples.html)
- [VICE Starting JupyterLab App](https://cyverse-visual-interactive-computing-environment.readthedocs-hosted.com/en/latest/user_guide/quick-jupyter.html) 
- [VICE Webinar](https://www.youtube.com/watch?v=KpBC0nScfL0)
- see [Making VICE Apps](#making-vice-apps) below

----


Circos-Binder and VICE app
---------------------------

[Genomic Conservation illustration featuring what Circos excels at and serves as a guide to reading the plots](http://circos.ca/guide/genomic/img/circos-conservation.png)

Contrast with trying to follow relationship between particular regions among twice-duplicated Amphioxus chromosomes and specific regions of human chromosomes in [Figure 3 from Putnam et al., 2008 (PMID: 18563158)](https://www.nature.com/articles/nature06967/figures/3)


[Main Circos site](http://circos.ca/)

[Circos Binder and Vice App Github repo](https://github.com/fomightez/circos-binder)

[CyVerse QuickStart page for Circos](https://cyverse-circos-quickstart.readthedocs-hosted.com/en/latest/)




### Alternatives

Other tools for similar circular (and non-circular) visualization.  
This is not meant to be an exhaustive listing.

#### Command-line/ Script based

- [Chord diagrams](https://www.data-to-viz.com/graph/chord.html#)
- [RCircos package](https://bitbucket.org/henryhzhang/rcircos/src/master/vignettes/RCircosLayoutDemo.png)
- [CIRCULAR PLOT – CIRCLIZE PACKAGE](https://www.r-graph-gallery.com/123-circular-plot-circlize-package-2/)
- [Donut: automated Circos visualization of multiple fasta files within a docker image, for comparative genomics](https://github.com/philippmuench/Donut)
- [Circoletto ](https://www.ncbi.nlm.nih.gov/pubmed/20736339) - Front-end to Circos that allows visualizing BLAST sequence comparison results; *lists that it includes a downloaded software package version as well as Webtool described below.*
- [karyoploteR](https://bernatgel.github.io/karyoploter_tutorial/#Examples) - for linear
- [EasyFig](https://github.com/mjsull/Easyfig/wiki/Example-1.-Simple-genome-region-comparison) - for linear and sub-regions
- [Donut plot with subgroups](https://github.com/fomightez/donut_plots_with_subgroups) to contrast [Circos with highlights (specifically bottom plot here)](http://circos.ca/documentation/tutorials/highlights/recipe2/images) .

#### Webtools

- [Circos Online](http://mkweb.bcgsc.ca/tableviewer/)
- [Circoletto ](http://tools.bat.infspire.org/circoletto/#info) - Front-end to Circos that allows visualizing BLAST sequence comparison results
- [CircosVCF](http://legolas.ariel.ac.il/~tools/CircosVCF/) is a user friendly web based visualization tool for plotting genome-wide variant data described in VCF files, using circos plots; the associated publication, Drori et al. 2017, describing the tool is indexed at PubMEd [here](https://www.ncbi.nlm.nih.gov/pubmed/28453675).
- [Circa](http://omgenomics.com/circa/)($) and Chordial ($)
- [CiVi: User-friendly Circular Visualization for microbial genomes](http://civi.cmbi.ru.nl/) but limited to the microbes (currently 2773) they have
- NCBI's [Genome Decoration Page](https://www.ncbi.nlm.nih.gov/genome/tools/gdp/) enables annotating on cytoogenetic representations.

### Unsorted

- Discussion [here](https://twitter.com/BioMickWatson/status/1011231099203223552)
- [Simple alternatives for the program Circos](https://www.biostars.org/p/336589/#336693)



Getting started with Circos
---------------------------



Required for a Circos plot:
- karyotype - name and size of chromosomes (contigs). Cytogenetic banding information, if available.
- ideogram - how to depict the chromosome, or region of it, in the image

Terms `karyotype` and `ideogram` are 'in the spirit of' actual cytogenetic [karyotype](https://www.nature.com/scitable/topicpage/karyotyping-for-chromosomal-abnormalities-298) related data concepts and how you would represent it as an [ideogram](https://en.wikipedia.org/wiki/Ideogram). Borrows much from traditional linear representations of this data as  [chromosome ideograms /idiograms / karyograms](https://en.wikipedia.org/wiki/File:Ideogram_human_chromosome_1.svg).

Typical Circos plot enhancements:
- Links
- Data Tracks
- Ticks & Labels
- Highlights

Circos ships with several predefined karyotype files for common sequence assemblies: *human, mouse, rat*, and *drosophila*. These files are located in `data/karyotype` within the Circos distribution. If your favorite genome is not included there, see [here](https://github.com/fomightez/sequencework/tree/master/circos-utilities) for a utility script I made that fetches information for many organisms from the UCSC genome database and makes a karyotype file. Alternatively, you can see the 'DEFINING CHROMOSOMES' section [here](http://circos.ca/tutorials/lessons/ideograms/karyotypes/) and write a karyotype yourself.

['Hello World' - Circos-style](http://circos.ca/documentation/tutorials/quick_start/hello_world/lesson)

A good way to proceed is to find an example close to what you want, that has code associated, and work on making that and integratinbg your data. Sources of images and code:

- [TUTORIAL IMAGES](http://circos.ca/tutorials/images/large/) - a page with interactive thumbnails of the tutorial images on one page
- [Martins's Handouts for the Practical Sessions focusing on Circos core features](http://circos.ca/documentation/course/)
- [The Circos Google group discussion list](https://groups.google.com/forum/#!forum/circos-data-visualization) - users often post code there with accompanying images. *In fact, this list was one of the reasons I wanted to 'binderize' Circos. It seemed it might be easier to share [minimum working examples](https://stackoverflow.com/help/mcve) and solutions with this system for assisting one another.*

Finding a basis for what you want to make?
- Literature
- [Circos IMAGES IN SCIENTIFIC LITERATURE page](http://circos.ca/intro/published_images/)
- [Circos VARIOUS SAMPLE IMAGES page](http://circos.ca/images/samples/)
- [Circos PLOT TYPES page](http://circos.ca/intro/features/)
- [Circos APPLICATION OF CIRCOS TO GENOMICS](http://circos.ca/intro/genomic_data/)
- [TUTORIAL IMAGES](http://circos.ca/tutorials/images/large/) - a page with interactive thumbnails of the tutorial images on one page (Unfortunately, it doesn't show all images as some like [here](http://circos.ca/documentation/tutorials/highlights/recipe2/images) contain two images and the thumbnail and browse images option only include one image for each tutorial page.)
- and more on [Main Circos site](http://circos.ca/)


----


Acknowledgements
----------------

- [Martin Krzywinski](http://mkweb.bcgsc.ca/) at Canada's Genome Sciences Centre, who developed Circos and made [the associated site and authored the content](http://circos.ca/) to help people learn it
- PatchMatch authors - Yan T, Yoo D, Berardini TZ, Mueller LA, Weems DC, Weng S, Cherry JM, Rhee SY.
- [MyBinder Team](https://jupyterhub-team-compass.readthedocs.io/en/latest/team.html#binder-team)
- [CyVerse Team](https://www.cyverse.org/staff). In particular, I'd lke to directly thank Upendra Devisetty, Tina Lee, and Shelley Littin.
- Department of Biochemistry and Molecular Biology at Upstate Medical University and Mark Schmitt
- [Stacia Sower](https://www.unhsowerlab.com/) for sending me to Titus Brown and colleagues' Data Intensive Summer Biology Workshop. See below for more info about that. 
- Data Intensive Biology Summer Institute - See [here](http://ivory.idyll.org/dibsi/index.html) for the [advertisment for the 2019 version of Titus Brown and Colleagues' Sequence Analysis (ANGUS)/Data Intensive Biology Summer Workshop](http://ivory.idyll.org/dibsi/ANGUS.html). Registration for this year closes soon, but be prepared for next yeat by [joining the dibsi-announce mailing list](https://groups.io/g/dibsi-announce/join).
- [Peter Rose's mmtf-genomics](https://github.com/sbl-sdsc/mmtf-genomics) serves as an excellent guide for how to integrate CyVerse use with previously binderized tools and making clear documentation.

----

----

Pertinent recent CyVerse Friday Focus Forum Webinars
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



----

----

----


----

Jupyter and Binder
------------------

**Importantly** Jupyter is langauage agnostic!  
What I covered here today only touched on Python and the bash shell languages because the fromer is the language I presently work in most often. However, Jupyter can host an R kernel and the hub can even serve RStudio. Other langauges are possible too.

**TRICK** for going between lab and older notebook interface in Jupyter sessions:  
To go from JupyterLab to classic-style, change end of url from `/lab` to `/tree`.  
To go from classic-style to JupyterLab, change end of url from `/tree` or `/notebooks...` to `/lab`.

- [VICE Starting JupyterLab App](https://cyverse-visual-interactive-computing-environment.readthedocs-hosted.com/en/latest/user_guide/quick-jupyter.html) 
- [MyBinder.org](https://mybinder.org/)
- [Sample Binder Repositories as Guides](https://mybinder.readthedocs.io/en/latest/sample_repos.html)
- Scientific Binder Examples in the wild:
  - [Peter Rose's mmtf-genomics](https://github.com/sbl-sdsc/mmtf-genomics)
  - [Python for ecologists, a Data Carpentry lesson](https://github.com/ngs-docs/2017-davis-ggg201a-day1)
  - [Introductory image processing on biological images using python](https://github.com/dwaithe/model-training)
  - [ssbio: structural systems biology](https://github.com/SBRG/ssbio)
  - ["Not All Bioinformatics is NGS" part of the SfAM ECS 2017 symposium](https://github.com/widdowquinn/Teaching-SfAM-ECS) by Leighton Pritchard
  - [ipyvolume: 3d plotting for Python](https://github.com/maartenbreddels/ipyvolume/)
  - [VPython running in a Jupyter notebook](https://github.com/BruceSherwood/vpython-jupyter)
  - [The interaction between simulation and scattering](https://pythoninchemistry.org/sim_and_scat/intro.html)
  - [LIGO data analysis](http://github.com/gwastro/pycbc) - package was used in the first direct detection of gravitational waves
  - [Reproducible academic publications](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks#reproducible-academic-publications) in [a gallery of interesting Jupyter Notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)
- [Juliette Taka's Reproducible Science and Binder system infographic](https://opendreamkit.org/public/images/use-cases/reproducible_logbook.png) for [OpenDreamKit](https://opendreamkit.org/2017/11/02/use-case-publishing-reproducible-notebooks/)
- [Binder Documentation](https://mybinder.readthedocs.io/en/latest/index.html)
- [Jupyter and Binder Community Forum](https://discourse.jupyter.org/)
- [Introducing Binder 2.0 — share your interactive research environment](https://elifesciences.org/labs/8653a61d/introducing-binder-2-0-share-your-interactive-research-environment)
- [Ten Simple Rules for Reproducible Research in Jupyter Notebooks](https://arxiv.org/abs/1810.08055) , with accompanying demo notebooks with biological workflows illustrated [here](https://github.com/jupyter-guide/ten-rules-jupyter)

Additional guides to command line tools in Jupyter environment:
- BLAST
  - [My repo for running command line-based BLAST in Jupyter environment provided via Binder.](https://github.com/fomightez/blast-binder)
  - [Using NCBI BLAST+ Service with Biopython](https://github.com/widdowquinn/Teaching-SfAM-ECS/blob/61ee5e98e7c1327cfc2bfc2ca6e44c2bdefcaeed/workshop/02b-blast.ipynb) from ["Not All Bioinformatics is NGS" part of the SfAM ECS 2017 symposium](https://github.com/widdowquinn/Teaching-SfAM-ECS) by Leighton Pritchard


Computational biology and related data handling skills training
--------

- [Learning at CyVerse](https://www.cyverse.org/learning)
- [Foundational Open Science Skills camp](https://www.cyverse.org/foss)
- [The Carpentries: Teaching foundational coding and data science skills to researchers worldwide](https://carpentries.org/) - There lessons form the basis of Software Carpentry and Data Carpentry workshops. Lots of the lessons and content are available to explore or schedule a workshop.
- Data Intensive Biology Summer Institute - See [here](http://ivory.idyll.org/dibsi/index.html) for the [advertisment for the 2019 version of Titus Brown and Colleagues' Sequence Analysis (ANGUS)/Data Intensive Biology Summer Workshop](http://ivory.idyll.org/dibsi/ANGUS.html). Registration for this year closes soon, but be prepared for next yeat by [joining the dibsi-announce mailing list](https://groups.io/g/dibsi-announce/join).  
  **The course content for recent years (plus more done by Titus and DIBSI) is shared [here](https://dib-training.readthedocs.io/en/pub/).**
- [EDAMAME Workshop in microbial metagenome analysis at Michigan State University](http://www.edamamecourse.org/)  
  **The course content is shared [here](https://github.com/edamame-course).**
- [Workshops on mothur and programming in R for microbial ecologists](https://mothur.org/wiki/Workshops)
- [Avi'o Workshops](http://merenlab.org/2016/08/18/events/)
- [Cold Spring Harbor's Programming for Biology, The Genome Access Course, and Computational Genomics courses](https://meetings.cshl.edu/courseshome.aspx)
- [UCLA Computational Genomics Summer Institute](http://computationalgenomics.bioinformatics.ucla.edu/2019-cgsi/) 
- [Microbial Genomics & Metagenomics Workshops](https://mgm.jgi.doe.gov/)
- [National Center for Genome Analysis Support (NCGAS) online R for Biologists course]() (offered in early Sping and in Fall; https://ncgas.org/; Bloomington, IN ; follow [twitter.com/ncgas](https://twitter.com/ncgas) for updates)
- [Canadian Bioinformatics Workshops](https://bioinformatics.ca/workshops/)
- [EMBL-EBI Training](https://www.ebi.ac.uk/training)
- [Bioinformatics.org](https://www.bioinformatics.org/) often lists training education opportunities on its main page.
- [Two Day Python and Pandas Workshop presented at Library of Congress May 2019 by Matt Burton](https://github.com/mcburton/lc-python-training)
- [My listing for Learning Python](https://jan2015feng-gr-m.readthedocs.io/en/latest/going%20forward/#learning-python) (some might be outdated; however, I try to update it as I find new ones)
- [Kelly Sovacool's List of Resources for Bioinformatics Software Development & Data Analysis](https://sovacool.dev/posts/2019/05/bioinf-resources)
- EdX courses


