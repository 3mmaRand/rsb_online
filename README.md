[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3901361.svg)](https://doi.org/10.5281/zenodo.3901361)

# Introduction to Reproducible Analyses in R

A [Royal Society of Biology](https://www.rsb.org.uk/) online Continuing Professional Development course held 29 June 2020, 1000 - 1600

## Overview

An increase in the complexity and scale of biological data means biologists are increasingly required to develop the data skills needed to design reproducible workflows for the simulation, collection, organisation, processing, analysis and presentation of data. Developing such data skills requires at least some coding, also known as scripting. This makes your work (everything you do with your raw data) explicitly described, totally transparent and completely reproducible. However, learning to code can be a daunting prospect for many biologists! That's where an Introduction to reproducible analyses in R comes in!

R is a free and open source language especially well-suited to data analysis and visualisation and has a relatively inclusive and newbie-friendly community. R caters to users who do not see themselves as programmers, but then allows them to slide gradually into programming.

## Who is this course for?

Introduction to reproducible analyses in R is aimed at biologists at all stages of their careers interested in experimenting with R to make their analyses and figures more reproducible.

## Prerequisites
No previous coding experience will be assumed. Pre-course instructions for participants are given below

## Learning outcomes

After this workshop the successful learner will be able to:

* Find their way around the RStudio windows
* Create and plot data using the base package and ggplot
* Explain the rationale for scripting analysis
* Use the help pages
* Know how to make additional packages available in an R session
* Reproducibly import data in a variety of formats
* Understand what is meant by the working directory, absolute and relative paths and be able to apply these concepts to data import
* Summarise data in a single group or in multiple groups
* Recognise tidy data format and carry out some typical data tidying tasks
* Develop highly organised analyses including well-commented scripts that can be understood by future you and others
* Use R Markdown to produce reproducible analyses, figures and reports

## Pre-course instructions for participants

The course will be delivered online using Zoom. The link will be sent to you by Friday 26 June. If you have not used zoom before, I recommend you download when prompted to do so when you join.

### Computing requirements

If possible, use a large or two-screen set-up.

You should have the following installed **prior** to attending the workshop:

- R version 3.6 or higher
- RStudio (1.2)
- RTools (windows only)
- these packages: `tidyverse`, `janitor`, `rticles`, `bookdown`, `citr`

### Installing R

Download the pre-compiled binary for your OS from https://cloud.r-project.org/ and install. More specifically:

**For Windows**

Click "Download R for Windows", then "base", then "Download R 4.0.0 for Windows". This will download an `.exe` file; once downloaded, open to start the installation. 

**For Mac**

Click "Download R for (Mac) OS X", then "R-4.0.0.pkg" to download the installer.
Run the installer to complete installation.

**For Linux**

Click "Download R for Linux". Instructions on installing are given for Debian, Redhat, Suse and Ubuntu distributions. Where there is a choice, install both `r-base` and `r-base-dev`.

### Installing R Studio

Downloads are available from https://www.rstudio.com/products/rstudio/download3/ (scroll to the end of the page to see the downloads).

**For Windows with no admin rights**

Download the `.zip` source archive under "Zip/Tarballs". Extract the files to a folder where you have write access, e.g. `C:\Users\username\RStudio`. In this folder, open the `bin` directory and find the RStudio program: it is named `rstudio.exe`, but the file extension will typically be hidden, so look for `rstudio`. Right-click this executable to create a desktop shortcut. Double-click the executable or use the shortcut to open.

### R Tools

Downloads are available from https://cran.r-project.org/bin/windows/Rtools/

### Installing packages

Once you have installed R and RStudio, start RStudio up and go to the Packages tab in the bottom right pane; click Install and type the name of the package you want to install in the box that appears. Then wait until you get the cursor (>) back in the console window.

### RStudio Cloud
If installing R and RStudio is tricky or impossible with your setup (e.g., if you only have a chrome book) then you can use https://rstudio.cloud/. This is a version of RStudio that runs in your browser. It is free but you will need to make an account. You will still need to install packages.


## Issues 

Typically R, Rstudio and R packages are painless to install. However, if you encounter problems there will be Zoom office hours on 26 June, 1500-1600 assist with set up.  The Zoom link will be sent to you for this session.


## Slides

[Morning](https://3mmarand.github.io/rsb_online/slides/01_intro_to_r_and_working_with_data.html)

[Afternoon](https://3mmarand.github.io/rsb_online/slides/02_r_markdown_for_reproducible_reports.html)


## Please cite as

Emma Rand. (2020, June 19). 3mmaRand/rsb_online: Royal Society of Biology Online: An Introduction to Reproducible Analyses in R (Version v1.0.0). Zenodo. http://doi.org/10.5281/zenodo.3901361

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Royal Society of Biology Online: An Introduction to Reproducible Analyses in R</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Emma Rand</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.







