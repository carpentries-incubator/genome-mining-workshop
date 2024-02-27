---
---

Data Carpentry’s aim is to teach researchers basic concepts, skills, and tools 
for working
with data so that they can get more done in less time and with less pain. This workshop uses 
Data Carpentry's approach to
teach data management and analysis for comparative bacterial genomics research, including: 
best practices for the organization of bioinformatics projects and data, 
use of command-line tools to compare genetic diversity between genomes,
organize this diversity in the core and dispensable set of a pangenome,
use of command-line tools to obtain and organize biosynthetic gene clusters, 
and connecting to and using cloud computing. 
This workshop is designed to be taught over two full days of instruction.

**Please note that workshop materials for working with Comparative Genomics data are in “pre-alpha” development. 
These lessons are available for review and for informal teaching experiences but are not yet part 
of The Carpentries’ official lesson offerings.**

Please chose your user in this [spredsheet](https://docs.google.com/spreadsheets/d/1uiBMjlIh3U5JufVoDl9BTncHPCmYm9GT-LHUkOwWnnU/edit#gid=0)

Interested in teaching these materials? We have an 
[Slack channel](https://metagenomicslesson.slack.com/archives/C023H1DRD1V) were we will be happy to help you! 


> ## Frequently Asked Questions
> Read our [FAQ](/comparative-genomics-workshop/faq/) to learn more about Data Carpentry's Comparative Bacterial Genomics Workshop, 
> as an Instructor or a workshop host. FIX [FAQ](/comparative-genomics-workshop/faq/) 💢
{: .callout} 

> ## Getting Started
>
> This lesson assumes that learners have no prior experience with the tools covered in the workshop. 
> However, learners are expected to be familiar with biological concepts,
> including the concepts of prokaryotic genome, biosynthetic gene cluster, and metabolite. 
> Participants should bring their own laptops and plan to participate actively.  
> 
{: .prereq}

> ## Data
> 
> This workshop uses data from the research "Genome analysis of multiple pathogenic 
> isolates of _Streptococcus agalactiae_: Implications for the microbial 'pan-genome' ",
> PNAS 2005. doi [10.1073/pnas.0506758102](https://doi.org/10.1073/pnas.0506758102).
> In this research, while studying the available genomes of _S. agalactiae_, 
> Tettelin and collaborators discovered that there was inter-species
> genome variation, and in consequence one genome is not enough to 
> describe the genetic repertoire of a species. 
> All of the data used in this workshop can be downloaded from:
>  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6599284.svg)](https://doi.org/10.5281/zenodo.6599284) 
> More information about this data is available on the [Data page](https://carpentries-incubator.github.io/pangenomics-workshop/data/index.html).
{: .prereq} 

# Workshop Overview 

| Lesson    | Overview | Estimated time|
| ------- | ---------- | ---------- |
| [Introduction to the Command Line for Pangenomics](https://carpentries-incubator.github.io/shell-pangenomics/) | Learn to navigate your file system, create, copy, move, and remove files and directories, and automate repetitive tasks using scripts and wildcards. | 4:00 hrs |
| [Introduction to Python](https://carpentries-incubator.github.io/pangenomics-python/) | Learn the basics of the Python language. |01:00 hrs| 
| [Genome Mining in Prokaryotes](https://carpentries-incubator.github.io/Genome-Mining/) |  Use command line and web-based tools for biosynthetic gene cluster prediction and organization.|04:30 hrs| 


# Teaching Platform
This workshop is designed to be run on pre-imaged Amazon Web Services (AWS)
instances. All the software and data used in the workshop are hosted on an Amazon Machine Image (AMI).
If you want to run your own instance of the server used for this workshop, follow the directions in the [Setup](setup.html) tab. 

## Citation 

