---
layout: page
title: Frequently Asked Questions
---

Thank you for your interest in hosting or teaching a Metagenomics workshop. Below you will find answers to some frequently asked questions about this curriculum. If the answer to your question doesn’t appear, please contact us using the Contact link in the righthand lower corner of this page.

* [For Hosts](#hosts)
* [For Instructors](#instructors)

## <a id="hosts"></a> Hosts

### What does this workshop cover? 

This workshop teaches data management and analysis for metagenomics research including: best practices for organization of bioinformatics projects and data, an introduction to the programing languages Bash and R, use of command line tools to process, analyze and visualize metagenomics data, and connecting to and using cloud computing. 

### What experience do learners need to have before this workshop? What will they be able to do by the end of the workshop? 

This lesson assumes no prior experience with the tools covered in the workshop. However, learners are expected to have some familiarity with biological concepts, such as DNA sequences and bacterial diversity. By the end of the workshop, learners will be able to: 

- structure their metadata, organize and document their genomics data and bioinformatics workflow, and access data on the NCBI sequence read archive (SRA) database,
- navigate their file systems, create, copy, move, and remove files and directories, and automate repetitive tasks using scripts and wildcards,
- use command-line tools to perform sequence quality control, assemble a metagenome, perform metagenomic binning, asses the quality of MAGs, perform taxonomic assignment to sequences, visualize taxonomic abundance,
- work with Amazon AWS cloud computing and transfer data between their local computer and cloud resources.

### What are the software, hardware, and connectivity needs for this workshop?

Learners will need to bring a laptop (not a tablet) with any spreadsheet program installed (e.g. LibreOffice, Microsoft Excel). Learners using a Windows machine will also need to download and install [Git for Windows](https://gitforwindows.org/). There are no other hardware or software requirements. Learners will need a stable, strong internet connection in order to work on the remote computing system used for this workshop.More information in the [Setup](https://drtamermansour.github.io/metagenomics-workshop/setup.html) page of this workshop.

### My institution has its own compute cluster, or our research group uses a different cloud computing resource. Can we deliver the workshop using that system?

To ensure a consistent workshop experience for learners and Instructors, all workshops organized by The Carpentries (“centrally-organized workshops”) use our stable, community-tested curriculum and technical set-up. Currently, all centrally-organized Metagenomics workshops are taught using AWS, although we are interested in supporting other systems in the future. If you are interested in using a different platform to teach this curriculum in a self-organized workshop, all of our materials are publicly available and licensed [CC-BY](https://creativecommons.org/licenses/by/4.0/). For information about the difference between centrally-organized and self-organized workshops, and limitations on use of “The Carpentries” brand name and logo, see the [Teaching and Hosting](https://docs.carpentries.org/topic_folders/hosts_instructors/index.html) section of The Carpentries Handbook.

### What experience do helpers need to have for this workshop?

Anyone who has experience using the Bash shell, R and RStudio can be an effective helper for this workshop. Helpers do not need to have experience working with metagenomics data or the specific command line tools taught in this workshop, although it is preferable. 

### Does the AWS image location matter? Do I need to set up an AMI in a different region if my workshop will be held outside of the Eastern US?

We have run this workshop in locations across the United States and Europe with no noticeable difference in instance speed. If you experience any issues, please [let us know](mailto:team@carpentries.org).

### Where can I find more information about this workshop?
For a full description of this workshop, including what content is covered, and what dataset we use to teach, visit the [Metagenomics Workshop Overview](https://carpentries-incubator.github.io/metagenomics-workshop/) page. 

## <a id="instructors"></a> Instructors

### What background and technological skills do I need to have to teach this workshop?

You will need experience using a bash shell (the default shell on Mac OS and most Linux systems), including writing your own small bash scripts and running programs written by others from the command line. You do not need to have specifically used the command-line programs that are used in these lessons. You do not need to have prior experience working with Amazon Web Services (AWS), but some experience logging on to remote computers would be useful. You should have experience working with genomic sequences in FASTQ format. 

### How can I prepare to teach this material? 

Each lesson has a set of Instructor Notes that provide information about the design of the lesson, commonly encountered problems, and technical tips and tricks. You can access [Instructor Notes](https://drtamermansour.github.io/metagenomics-workshop/guide/index.html). Instructor Notes are written collaboratively by our Instructors, so please contribute your own notes after your workshop!

### When will I have access to an AWS image to practice on?

Each Instructor will receive connection information for an AMI instance approximately one week before the workshop. If you would like workshop helpers to also have access to an instance to prepare for the workshop, or if you would like access more than one week in advance of the workshop, please contact [team@carpentries.org](mailto:team@carpentries.org).

### How will my learners get connection and log-in information? 

The Carpentries Workshop and Logistics Manager will provide Instructors with connection information for AMI instances the day before the workshop. Enough instances will be provided for each learner, and if requested, for each workshop helper, to have their own individual instance. Instructors can make connection information available to learners through the workshop Etherpad. 

### What are common problems that arise during this workshop?

The best place to get information about common problems that arise during workshops is in the [Instructor Notes](https://drtamermansour.github.io/metagenomics-workshop/guide/index.html). You can access Instructor Notes through the Extras menu in the top navigation bar that appears across the head of each lesson. Instructors are strongly encouraged to contribute back to the Instructor Notes based on their workshop experience. To contribute to the Instructor Notes, click the “Improve this page” menu option in the upper right corner of the Instructor Notes page. 

### Does the AWS image location matter? Do I need to set up an AMI in a different region if my workshop will be held outside of the Eastern US?

We have run this workshop in locations across the United States and Europe with no noticeable difference in instance speed. If you experience any issues, please [let us know](team@carpentries.org).

# Reference
This notes are adapted from the Data Carpentry Genomics Workshop [corresponding page](https://datacarpentry.org/genomics-workshop/faq/index.html)
