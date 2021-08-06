---
site: [pasteur, freiburg, erasmusmc, elixir-it, belgium, genouest]
tags:
- training
- COVID-19
title: "SARS-CoV-2 Data Analysis and Monitoring with Galaxy"
starts: 2021-08-09
ends: 2021-08-12
organiser:
location: online
supporters: 
 - denbi
 - galaxy-europe
 - galaxy-australia
 - gallantries
 - erasmus+
 - eosc
 - converge
 - pari
 - neic
 - australian_biocommons
 - qfab
 - melbbioinfo
---

The goal of this workshop is to build capacity in SARS-CoV-2 data analysis and data management, including data submission to ENA. After the workshop,
all participants will be able to upload viral sequencing data, call all variants, create a variety of reports and create consensus alignments.

It will be a 4-day event introducing scalable and reproducible SARS-CoV-2 data analysis with Galaxy. The sessions will be pre-recorded and provided in advance.
During the workshop, there will be live support in chat and live Q&A sessions, in which experts will answer questions.
<br>

<div align="center" width="100%"><a href="https://covid19.galaxyproject.org/"><button type="button" class="btn btn-primary btn-lg">More Galaxy COVID projects!</button></a></div>

<br><br>

<div class="row">
<div class="col-md-6" markdown="1">
- **WHEN**: August 9-12, 2021
- **WHO**: Open for everybody, but the target audience is **clinicians** and **researchers** that deal with SARS-CoV-2 sequencing data.
- **COST**: Free.
- **FORMAT**: Virtual and asynchronous. All training **sessions will be pre-recorded and provided in advance**.
- **SUPPORT**:
    - **Live support in chat** (Slack Channel), in which experts will answer questions on a peer-to-peer basis.
    - **Real-Time Q&A sessions** on days 2, 3 and 4 (9 am and 4 pm CEST).
- **INFRASTRUCTURE**: [European Galaxy server](https://usegalaxy.eu){:target="_blank"} and the [Galaxy Training Material](https://training.galaxyproject.org){:target="_blank"}. Both will stay accessible and open after the training.
- [**Contact us**](mailto:contact@usegalaxy.eu) if you have questions.
</div>
<div class="col-md-6" markdown="1">
![sars-cov-2-workshop](/assets/media/2021-06-21-sars-cov-2-data-analysis-monitoring-training.png)
</div>
</div>

<br>


[**Register now**](https://docs.google.com/forms/d/e/1FAIpQLSeADQn0PdzfFppwoOGFAqWQglnKRhj3FNcqpUKggwXsn2PKBg/viewform?usp=sf_link){:.btn .btn-primary style="color: white; width: 100%; background-color: #3a3566;"}

<br>

# Program & Material

This workshop is virtual and asynchronous. Training sessions are pre-recorded and the material provided in advance in the program below (some material is still in preparation: WIP). 

Whenever you're ready to get started, you can access the material by clicking in the program on the different icons:
- [](){:.fa .fa-slideshare} for **slide** deck for a lecture
- [](){:.fa .fa-laptop} for **hands-on tutorial** (on the [Galaxy Training Material](https://training.galaxyproject.org/){:target="_blank"})
- [](){:.fa .fa-video-camera} for **video** (accompanying a lecture, a tutorial or a demo)
- [](){:.fa .fa-list-ul} for **shared Galaxy history** (on the [European Galaxy server](https://usegalaxy.eu){:target="_blank"})

## Day 1 (9.8.2021) - Introduction to Galaxy

Topic | Speaker | Material | Description | Duration
--- | --- | --- | ---
A very short introduction to Galaxy | Anton Nekrutenko | [](https://training.galaxyproject.org/training-material/topics/introduction/tutorials/galaxy-intro-short/slides.html?utm_source=usegalaxyeu&utm_medium=website&utm_campaign=covid2021){:.fa .fa-slideshare target="_blank"} / [](https://youtu.be/VZoz3k5EehI){:.fa .fa-video-camera target="_blank"} | Lecture: *This video will introduce the Galaxy data analysis platform, and give a short demo on how to use it.*{: .small} | 10m
Galaxy 101 | Anton Nekrutenko |  [](https://training.galaxyproject.org/training-material/topics/introduction/tutorials/galaxy-intro-101/tutorial.html){:.fa .fa-laptop target="_blank"} / [](https://youtu.be/D5HgJWdfOWw){:.fa .fa-video-camera target="_blank"} <br> *WIP*{:.fa .fa-list-ul} |  Hands-on: *This tutorial will introduce you to Galaxy. You will familiarize yourself with tools, workflows and histories. Those skills will be needed the next days.*{: .small} | 1h
NGS data logistics | Anton Nekrutenko | [](https://training.galaxyproject.org/training-material//topics/introduction/tutorials/galaxy-intro-ngs-data-managment/tutorial.html){:.fa .fa-laptop target="_blank"} / [](https://youtu.be/9mIL0tIfZ_o){:.fa .fa-video-camera target="_blank"} <br> *WIP*{:.fa .fa-list-ul target="_blank"} |  Hands-on: *Learn how to manipulate and process NGS data data derived from patients infected with SARS-CoV-2. Get familiar with quality control, mapping and NGS filetypes.*{: .small} | 1h 30m
{:.table.table-striped}

## Day 2 (10.8.2021) - Data Upload & Quality Control

Topic | Speaker | Material | Description | Duration
--- | --- | --- | --- | ---
 | All experts | [](https://docs.google.com/document/d/1SIcl7BPDGCV0D-AA_S008qVYaH8id4_ibD6iTVx6gYY/edit?usp=sharing){:.fa .fa-info-circle target="_blank"} Info & Zoom link | **Real-Time Q&A session (9 am CEST)** | 1h
Quality control of reads | Florian Heyl | [](https://training.galaxyproject.org/training-material/topics/sequence-analysis/tutorials/quality-control/slides.html?utm_source=usegalaxyeu&utm_medium=website&utm_campaign=covid2021){:.fa .fa-slideshare target="_blank"} / [](https://youtu.be/BWonTPS4zB8){:.fa .fa-video-camera target="_blank"} | Lecture: *This lecture goes over the concepts involved in assessing the quality of your sequencing data.*{: .small} | 40m | 
Quality control of reads | Florian Heyl | [](https://training.galaxyproject.org/topics/sequence-analysis/tutorials/quality-control/tutorial.html?utm_source=usegalaxyeu&utm_medium=website&utm_campaign=covid2021){:.fa .fa-laptop target="_blank"} / [](https://youtu.be/QJRlX2hWDKM){:.fa .fa-video-camera target="_blank"} <br> *WIP*{:.fa .fa-list-ul target="_blank"} | Hands-on: *In this tutorial you will get some hand-on experience performing a quality assessment on sequencing data.*{: .small} | 1h 10m
Mapping of reads | Peter van Heusden | [](https://training.galaxyproject.org/training-material/topics/sequence-analysis/tutorials/mapping/slides.html?utm_source=usegalaxyeu&utm_medium=website&utm_campaign=covid2021){:.fa .fa-slideshare target="_blank"} / [](https://youtu.be/7FhHb8EV3EU){:.fa .fa-video-camera target="_blank"} | Lecture: *This lecture covers the basic concepts involved in mapping sequencing reads to a reference genome.*{: .small} | 10m
Mapping of reads | Peter van Heusden | [](https://training.galaxyproject.org/training-material/topics/sequence-analysis/tutorials/mapping/tutorial.html?utm_source=usegalaxyeu&utm_medium=website&utm_campaign=covid2021){:.fa .fa-laptop target="_blank"} / [](https://youtu.be/1wm-62E2NkY){:.fa .fa-video-camera target="_blank"} <br> *WIP*{:.fa .fa-list-ul target="_blank"} | Hands-on: *In this tutorial you will map sequencing data to a reference genome, and explore the mapped reads in a genome browser.*{: .small} |20m
Using dataset collections | Anton Nekrutenko | [](https://training.galaxyproject.org/training-material/topics/galaxy-interface/tutorials/collections/tutorial.html?utm_source=usegalaxyeu&utm_medium=website&utm_campaign=covid2021){:.fa .fa-laptop target="_blank"} / [](https://youtu.be/uZUt9XIHUQo){:.fa .fa-video-camera target="_blank"} <br> [](https://usegalaxy.eu/u/bgruening/h/using-dataset-collections---tutorial){:.fa .fa-list-ul target="_blank"} | Hands-on: *How to manipulate large numbers of datasets at once? This will be needed to process 100 of SARS-CoV-2 samples in one go.*{: .small} | 30m
Data cleaning workflow | TBC (BE) | [](https://training.galaxyproject.org/training-material/topics/sequence-analysis/tutorials/human-reads-removal/tutorial.html){:.fa .fa-laptop target="_blank"} / *WIP*[](){:.fa .fa-video-camera target="_blank"} <br> *WIP*{:.fa .fa-list-ul target="_blank"} | Hands-on: *As a first exercise in actual SARS-CoV-2 data analysis with Galaxy, this tutorial will let you perform the steps necessary to remove contaminating human reads from sequencing data of SARS-CoV-2 isolates.*{: .small } | 1h
 | All experts | [](https://docs.google.com/document/d/1SIcl7BPDGCV0D-AA_S008qVYaH8id4_ibD6iTVx6gYY/edit?usp=sharing){:.fa .fa-info-circle target="_blank"} Info & Zoom link | **Real-Time Q&A session (4 pm CEST)** | 1h
{:.table.table-striped}

## Day 3 (11.8.2021) - SARS-CoV-2 Data Analysis on Public Datasets

Topic | Speaker | Material | Description | Duration
--- | --- | --- | ---
 | All experts | [](https://docs.google.com/document/d/1SIcl7BPDGCV0D-AA_S008qVYaH8id4_ibD6iTVx6gYY/edit?usp=sharing){:.fa .fa-info-circle target="_blank"} Info & Zoom link | **Real-Time Q&A session (9 am CEST)** | 1h
Galaxy for SARS-CoV-2 genome surveillance projects | Wolfgang Maier | *WIP*{:.fa .fa-slideshare target="_blank"} / [](https://www.youtube.com/watch?v=luxFraFJTc4){:.fa .fa-video-camera target="_blank"} | Lecture: *Get an overview of what day 3 has to offer: production-ready Galaxy workflows for SARS-CoV-2 sequencing data, tools you should know to automate workflow execution, and how you combine all of it to turn Galaxy into a platform for genome-surveillance.*{: .small } |
Variant calling, reporting, consensus building (with Galaxy GUI) | Wolfgang Maier | [](https://training.galaxyproject.org/training-material/topics/variant-analysis/tutorials/sars-cov-2-variant-discovery/tutorial.html?utm_source=usegalaxyeu&utm_medium=website&utm_campaign=covid2021){:.fa .fa-laptop target="_blank"} / [](https://www.youtube.com/watch?v=vnFQ2fR_fzw){:.fa .fa-video-camera target="_blank"} <br> *WIP*{:.fa .fa-list-ul target="_blank"} | Hands-on: *Illumina or ONT, ampliconic or WGS data? Learn how to combine the right set of Galaxy workflows to analyze the type of SARS-CoV-2 sequencing data of your choice.*{: .small } | 
Variant calling, reporting, consensus building (with Galaxy CLI) | Simon Bray | [](https://training.galaxyproject.org/training-material//topics/galaxy-interface/tutorials/workflow-automation/tutorial.html?utm_source=usegalaxyeu&utm_medium=website&utm_campaign=covid2021){:.fa .fa-laptop target="_blank"} / [](https://www.youtube.com/watch?v=o39QjVnLG68){:.fa .fa-video-camera target="_blank"} | Hands-on: *Learn how to use the command line to upload your SARS-CoV-2 data to a Galaxy-server and launch workflows for its analysis. Note: This first step towards automation requires the command line tool [Planemo](https://planemo.readthedocs.io/en/latest/) for interacting with Galaxy if you want to follow along.*{: .small } |
The usegalaxy.eu SARS-CoV-2 bot in action | Wolfgang Maier | [](https://www.youtube.com/watch?v=IRxja8bZ-MU){:.fa .fa-video-camera target="_blank"} | Demo: *See in this demo how, on usegalaxy.*, we've used Planemo and Bioblend to build and operate an automated SARS-CoV-2 genome surveillance system based on the Galaxy workflows for variant calling, consensus building and reporting.*{: .small } |
 | All experts | [](https://docs.google.com/document/d/1SIcl7BPDGCV0D-AA_S008qVYaH8id4_ibD6iTVx6gYY/edit?usp=sharing){:.fa .fa-info-circle target="_blank"} Info & Zoom link | **Real-Time Q&A session (4 pm CEST)** | 1h
{:.table.table-striped}

## Day 4 (12.8.2021) - Visualisation & Data Export

Topic | Speaker | Material | Description | Duration
--- | --- | --- | ---
| All experts | [](https://docs.google.com/document/d/1SIcl7BPDGCV0D-AA_S008qVYaH8id4_ibD6iTVx6gYY/edit?usp=sharing){:.fa .fa-info-circle target="_blank"} Info & Zoom link | **Real-Time Q&A session (9 am CEST)**  | 1h
Upload data to ENA | Miguel Roncoroni | [ Demo ](https://www.youtube.com/watch?v=POiQG-7O7rw){:.fa .fa-video-camera target="_blank"} | *Learn how to submit your sequencing data to the ENA directly from Galaxy.*{: .small } | 14m
Upload data to a local datastore | Wolfgang Maier | [ Demo ](https://www.youtube.com/watch?v=-5U0sINjoig){:.fa .fa-video-camera target="_blank"} | *So you've used Galaxy workflows to analyze your SARS-CoV-2 samples? Learn in this tutorial how to export results to your favorite datastore.*{: .small } |
Introduction to viral Beacon | Babita Singh | [ Demo ](https://youtu.be/R_4yUMPk7eY ){:.fa .fa-video-camera target="_blank"} / [ Slides](https://drive.google.com/file/d/1yCHOi1EGKpkH-3XpKTKNKpFjwYAWKSVx/preview){:.fa .fa-slideshare target="_blank"} | *How to visualize tens of thousands of SARS-CoV-2 analysis results? Learn about the Viral Beacon project's solution!*{: .small } | 24m
Using and Customising ObservableHQ | TBC | *WIP*{:.fa .fa-video-camera target="_blank"} Demo | *In this demo you will get to know the ObservableHQ platform for interactive data visualization. You will see how covid19.galaxyproject.org uses it to build a dashboard for their SARS-CoV-2 analysis efforts and will learn how to customize this solution to fit your own purposes.*{: .small } |
 | All experts | [](https://docs.google.com/document/d/1SIcl7BPDGCV0D-AA_S008qVYaH8id4_ibD6iTVx6gYY/edit?usp=sharing){:.fa .fa-info-circle target="_blank"} Info & Zoom link | **Real-Time Q&A session (4 pm CEST)** | 1h
{:.table.table-striped}

## Optional extra training

Topic | Speaker | Material | Description | Duration
--- | --- | --- | ---
SRA Aligned Read Formats to Speed Up SARS-CoV-2 data Analysis | Jonathan Trow | [  Slides](https://training.galaxyproject.org/training-material/topics/galaxy-interface/tutorials/ncbi-sarf/slides.html?utm_source=usegalaxyeu&utm_medium=website&utm_campaign=covid2021){:.fa .fa-slideshare target="_blank"} / [ Lecture ](https://www.youtube.com/watch?v=siLP71B9gm4){:.fa .fa-video-camera target="_blank"} | *This lecture will introduce the SRA Aligned Read format available in the cloud from SRA, as well as some accompanying metadata that can help you search and filter the data. This sessions is aimed specifically at SARS-CoV-2 runs in SRA.*{: .small} | 15m
SRA Aligned Read Formats to Speed Up SARS-CoV-2 data Analysis  | Jonathan Trow | [](https://training.galaxyproject.org/training-material/topics/galaxy-interface/tutorials/ncbi-sarf/tutorial.html?utm_source=usegalaxyeu&utm_medium=website&utm_campaign=covid2021){:.fa .fa-laptop target="_blank"} / [ Hands-on tutorial ](https://www.youtube.com/watch?v=ogu-NBTP-DM){:.fa .fa-video-camera target="_blank"} | *This tutorials will walk you through accessing and using SRA Aligned read format in Galaxy.*{: .small} | 40m
Assembly: Unicycler assembly of SARS-CoV-2 genome | Cristóbal Gallardo | [  Slides](https://training.galaxyproject.org/training-material/topics/assembly/tutorials/assembly-with-preprocessing/slides.html?utm_source=usegalaxyeu&utm_medium=website&utm_campaign=covid2021){:.fa .fa-laptop target="_blank"}  | |
Assembly: Unicycler assembly of SARS-CoV-2 genome | Cristóbal Gallardo | [[](https://training.galaxyproject.org/training-material/topics/assembly/tutorials/assembly-with-preprocessing/tutorial.html?utm_source=usegalaxyeu&utm_medium=website&utm_campaign=covid2021){:.fa .fa-laptop target="_blank"} / [ Hands-on tutorial ](https://www.youtube.com/watch?v=jNFLYhjgJPs){:.fa .fa-video-camera target="_blank"} | | 25m
Pandemics Research using Mass Spectrometry | Timothy J. Griffin, Subina Mehta, Andrew Rajczewski, Pratik Jagtap | [](https://drive.google.com/file/d/1anBPmGRWEVp9pBLZ_JInWV7iWrBpyCDs/view?usp=sharing?utm_source=smorgasbord&utm_medium=website&utm_campaign=gcc2021){:.fa .fa-laptop target="_blank"} / [ Demo ](https://www.youtube.com/watch?v=CI35gTmZoqM){:.fa .fa-video-camera target="_blank"} | | 35m
Scripting Galaxy using the API and BioBlend | TBC | [](https://training.galaxyproject.org/training-material/topics/dev/tutorials/bioblend-api/slides.html?utm_source=usegalaxyeu&utm_medium=website&utm_campaign=covid2021){:.fa .fa-slideshare target="_blank"} | |
What you can do with SARS-COV-2 data: Case studies | Andrew Page | [](https://www.youtube.com/watch?v=R4EoTEiAQNE){:.fa .fa-video-camera target="_blank"} | | 37m
{:.table.table-striped}


# Logistics

## Content delivery

This is a global workshop delivered asynchronously. In practice, this means that you will have training materials available to explore them at **your own pace**, without any time constraints:

- **Lectures**: pre-recorded videos ([](){:.fa .fa-video-camera}) with the theoretical explanation of the lesson, supported by slide decks ([](){:.fa .fa-slideshare}).
- **Hands-on tutorials** ([](){:.fa .fa-laptop}): a step-by-step explanation, including all the required information, to perform a data analysis, often available also as pre-recorded video ([](){:.fa .fa-video-camera}).

    Most of the tutorials are developed by the [Galaxy Training Network](http://training.galaxyproject.org/){:target="_blank"}. A feedback form is available at the bottom of each tutorial page. Please fill it out, it helps us to value and improve the tutorials.

- **Histories**: shared Galaxy history ([](){:.fa .fa-list-ul}), on the [European Galaxy server](https://usegalaxy.eu){:target="_blank"}, with all that you need to reproduce what is shown in the hands-on part.
- **Demo**: pre-recorded videos ([](){:.fa .fa-video-camera}) demonstrating a technical point or a nice feature.

Most of the material is available already, and they will all stay **available after the workshop**. Most of the material have been developed by a community of people via the [Galaxy Training Network](training.galaxyproject.org/){:target="_blank"}. Some videos were recorded for different previous events, e.g. [GTN Smörgåsbord](https://shiltemann.github.io/global-galaxy-course/){:target="_blank"} or [GCC2021 Training Week](https://galaxyproject.org/events/gcc2021/training/){:target="_blank"}, and the captions were manually-curated by several community members.

Whenever you're ready to get started, you can access the material by clicking on the different icons in the program!

## Doing the tutorials - Technical requirements

Some of you have asked about the technical requirements. You don't need a specific operating system or software installed, all you need is a browser and internet connection.

To run the tutorials, you will need a **Galaxy account**. We recommend you to:

- Register and use [European Galaxy server](https://usegalaxy.eu){:target="_blank"}

    You will receive an email to confirm your account before you can start using Galaxy.
- Join the [training event group](https://usegalaxy.eu/join-training/sars_cov2_2021/), it will make your jobs go faster!

## Support & Communication channels

Should you have any questions, the instructors will be available in chat. We will use the Slack space of the Galaxy Training Network. Depending on your location you might need to use a VPN, so **please make sure that you can join Slack before the workshop**.

Once you are in, you will see different channels (#general, #covid2021-day- for the different days) but also #random, #social. Pass by and say hi to your colleagues! Every day we will have an icebreaker question for the #social channel. 

When asking a question:
- Ask in the appropriate place:
    - #general for general issues
    - #event-covid2021-day-1 for day 1 (Introduction to Galaxy)
    - #event-covid2021-day-2 for day 2 (Data Upload & Quality Control)
    - #event-covid2021-day-3 for day 3 (SARS-CoV-2 Data Analysis on Public Datasets)
    - #event-covid2021-day-4 for day 4 (Visualisation & Data Export)
- Use threads.
- Say which server you're using.
- Share all of the details (What did the tool say? What was the error? Did you see more information in the bug-report icon?)

During the week of the workshop, the instructors will be there to reply to your questions. Please be aware of the **time zones**, the instructors are scattered all over the world and sometimes you may have to be patient to get a reply.

Real-time Q&A sessions will be run on days 2, 3 and 4 (9 am and 4 pm CEST). Find the details to join these sessions and register by adding your name to the attendees list in the [dedicated document](https://docs.google.com/document/d/1SIcl7BPDGCV0D-AA_S008qVYaH8id4_ibD6iTVx6gYY/edit?usp=sharing).

## Certificates

If you need a certificate, you can request it at the end of the workshop. Please make sure to keep all the work over the 4 days, stay active in the discussions and fill out the [final survey](https://forms.gle/m8NRg7WrgGwnCEGQA).

# Code of Conduct

Everyone is expected to abide by the [Code of Conduct (CoC)](https://galaxyproject.org/community/coc/) to make this environment welcoming and friendly for everyone.

# Instructors & helpers

Name | Location
--- | ---
Wolfgang Maier | Germany
Bérénice Batut | Germany
Beatriz Serrano-Solano | Germany
Engy Nasr | Germany
Simon Bray | Germany
Florian Heyl | Germany
Björn Grüning | Germany
Anton Nekrutenko | USA
Andrew Page | UK
Peter van Heusden | South Africa
Erik Hjerde | Norway
Annbjørg Barbakken | Norway
Kjell Petersen | Norway
Steven Morgan | Australia
Gareth Price | Australia
Anna Syme | Australia
Igor Makunin | Australia
Valentine Murigneux | Australia
Michael Thang | Australia
{:.table.table-striped}
