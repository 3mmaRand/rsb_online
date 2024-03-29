[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3901361.svg)](https://doi.org/10.5281/zenodo.3901361)

# Introduction to Reproducible Analyses in R

A [Royal Society of Biology](https://www.rsb.org.uk/) online Continuing Professional Development course 1000 - 1600

## Overview

An increase in the complexity and scale of biological data means biologists are increasingly required to develop the data skills needed to design reproducible workflows for the simulation, collection, organisation, processing, analysis and presentation of data. Developing such data skills requires at least some coding, also known as scripting. This makes your work (everything you do with your raw data) explicitly described, totally transparent and completely reproducible. However, learning to code can be a daunting prospect for many biologists! That's where an Introduction to reproducible analyses in R comes in!

R is a free and open source language especially well-suited to data analysis and visualisation and has a relatively inclusive and newbie-friendly community. R caters to users who do not see themselves as programmers, but then allows them to slide gradually into programming.

## Who is this course for?

Introduction to reproducible analyses in R is aimed at biologists at all stages of their careers interested in experimenting with R to make their analyses and figures more reproducible.

## Prerequisites

No previous coding experience will be assumed. Pre-course instructions for participants are given below

## Learning outcomes

After this workshop the successful learner will be able to:

-   Find their way around the RStudio windows
-   Create and plot data using ggplot
-   Explain the rationale for scripting analysis
-   Use the help pages
-   Know how to make additional packages available in an R session
-   Reproducibly import data in a variety of formats
-   Understand what is meant by the working directory, absolute and relative paths and be able to apply these concepts to data import
-   Summarise data in a single group or in multiple groups
-   Recognise tidy data format and carry out some typical data tidying tasks
-   Develop highly organised analyses including well-commented scripts that can be understood by future you and others
-   Use R Markdown to produce reproducible analyses, figures and reports

## Pre-course instructions for participants

The course will be delivered online using Zoom. If you have not used zoom before, I recommend you download when prompted to do so when you join.

### Computing requirements

If possible, use a large or two-screen set-up.

You should have the following installed **prior** to attending the workshop:

-   R version 4.0 or higher
-   RStudio (1.4)
-   RTools (windows only)
-   these packages: `tidyverse`, `janitor`, `bookdown`

### Installing R

**For Windows**

Go to <https://cloud.r-project.org/>
Click "Download R for Windows", then "base", then "Download R 4.x.x for Windows". This will download an `.exe` file. Click to start the installation.

**For Mac**

Go to <https://cloud.r-project.org/>
Click "Download R for macOS", then "R-4.x.x.pkg" to download the installer. Run the installer to complete installation.


### Installing R Studio

Downloads are available from  <https://www.rstudio.com/products/rstudio/download/#download> 

**For Windows**

Download "RStudio-1.4.xxx.exe"
This will download an `.exe` file. Click to start the installation.

**For Windows with no admin rights**

Download the `.zip` source archive under "Zip/Tarballs". Extract the files to a folder where you have write access, e.g. `C:\Users\username\RStudio`. In this folder, open the `bin` directory and find the RStudio program: it is named `rstudio.exe`, but the file extension will typically be hidden, so look for `rstudio`. Right-click this executable to create a desktop shortcut. Double-click the executable or use the shortcut to open.

**For Mac**

Download "RStudio-1.4.xxx.dmg"
Click to start the installation.



### R Tools
Go to <https://cran.r-project.org/bin/windows/Rtools/>
Download "rtools40v2-x86_64.exe"
This will download an `.exe` file. Click to start the installation.



### Installing packages

Once you have installed R and RStudio, start RStudio up and go to the Packages tab in the bottom right pane; click Install and type the name of the package you want to install in the box that appears. Then wait until you get the cursor (\>) back in the console window.

You need to install `tidyverse`, `janitor`, `bookdown`

### RStudio Cloud

If installing R and RStudio is tricky or impossible with your setup (e.g., if you only have a chrome book) then you can use <https://rstudio.cloud/>. This is a version of RStudio that runs in your browser. It is free for 15 hours a month but you will need to make an account. You will still need to install packages.

## Issues

Typically R, Rstudio and R packages are painless to install. However, if you encounter problems use RStudio Cloud.

## Slides

[Morning](https://3mmarand.github.io/rsb_online/slides/01_intro_to_r_and_working_with_data.html)

[Afternoon](https://3mmarand.github.io/rsb_online/slides/02_r_markdown_for_reproducible_reports.html)

## Please cite as

Rand E. (2021). Introduction to Reproducible Analyses in R. A Royal Society of Biology online Continuing Professional Development course (version v1.0.2). DOI: https://doi.org/10.5281/zenodo.3901361 URL: https://github.com/3mmaRand/rsb_online

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" alt="Creative Commons License" style="border-width:0"/></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Royal Society of Biology Online: An Introduction to Reproducible Analyses in R</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Emma Rand</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
