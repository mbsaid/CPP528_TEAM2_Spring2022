---
layout: page
title: Read Me
---
# CPP-528
CPP-528 Spring 2022 Session B
<br>
Team 2 Final Project

This project was completed for the [Arizona State University](asu.edu) course CPP-528, Foundations of Data Science Part III: Project management for data analysts, part of the [Program Evaluation and Data Analytics masters program](https://ds4ps.org/ms-prog-eval-data-analytics/).

US Census data were used to evaluate the impact of two tax credit programs, New Market Tax Credits and Low Income Housing Tax Credits, using median home values as an indicator of improved neighborhood wellbeing. 

**Team Members**
<br>
Sarah Johaningsmeir, https://github.com/Johaning
<br>
Caitlyn Mccullers, https://github.com/ctmccull
<br>
Ahmed Radwan, https://github.com/radwan-a
<br>
Mohamed Said, https://github.com/mbsaid


**Replication Tips**
<br>
<br>
This project was completed using R 4.1.0, RStudio, GitHub, and GitHub Desktop.
<br>
<br>
In this repository, you will find a renv.lock file. Should you want to replicate this study, you will need to run the renv::restore() function to install all packages and their dependencies involved in this project.
<br>
<br>
**Data Files**
<br>
<br>
You will find the Census Longitudinal Tabulated Database (LTDB) file here:
<br>
[Harmonized Census Data](https://github.com/ctmccull/CPP528_TEAM2_Spring2022/tree/main/data/raw)
<br>
[Cleaned Data](https://github.com/ctmccull/CPP528_TEAM2_Spring2022/tree/main/data/rodeo)
<br>
[Codebook](https://watts-college.github.io/cpp-528-spr-2022/data/LTDB-codebook.pdf)
<br>
<br>
Low Income Housing Tax Credit (LIHTC) data files are stored here:
<br>
[LIHTC Data Dictionary](https://github.com/ctmccull/CPP528_TEAM2_Spring2022/blob/main/data/raw/LIHTC%20Data%20Dictionary%202017.pdf)
<br>
[LIHTC Raw Data](https://github.com/ctmccull/CPP528_TEAM2_Spring2022/blob/main/data/raw/LIHTCPUB.csv)
<br>
<br>
New Market Tax Credit (NMTC) data files are stored here:
<BR>
[NMTC Data Dictionary](https://github.com/ctmccull/CPP528_TEAM2_Spring2022/blob/main/data/raw/2019%20NMTC%20Public%20Data%20Release_FY_17.xlsx)
<br>
[NMTC_Sheet_1](https://github.com/ctmccull/CPP528_TEAM2_Spring2022/blob/main/data/raw/nmtc-sheet-01.csv)
<br>
[NMTC Sheet 2](https://github.com/ctmccull/CPP528_TEAM2_Spring2022/blob/main/data/raw/nmtc-sheet-02.csv)
<br>
<br>
  
**Required Packages**
  
<br>
To install required packages you can restore packages dependencies from renv.lock file that is located in [renv](https://github.com/ctmccull/CPP528_TEAM2_Spring2022/tree/main/renv) folder. Use the code renv::restore(here::here())

<br>
<br>
  
**Licensing**

<br>
The project is licensed under MIT open source license. For more details check [license](https://github.com/ctmccull/CPP528_TEAM2_Spring2022/blob/main/LICENSE) file.

<br>
<br>
<br>
  
