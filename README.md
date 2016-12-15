# Getting and Cleaning Data Course Assignment
=================================
#Introdution too project
=================================
The purpose of this project is to demonstrate the ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. 
One of the most exciting areas in all of data science right now is wearable computing - see for example this article .
Companies like FitBit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked are collected from the accelerometers from the Samsung Galaxy S smartphone.

A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The data is available at:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

##Instructions for project

- run_analysis.R : the R-code run on the data set

- Tidy.txt : the clean data extracted from the original data using run_analysis.R

- CodeBook.md : the CodeBook reference to the variables in Tidy.txt

- README.md : the analysis of the code in run_analysis.R

- analysis.html : the html version of README.md

##Tools used to produce this project

- This project is built by `knirt` package instllled on RStudio with RMD (R Markdown) format.

- The  `run_analysis.md` and `codebook.md` files will be  automatically  produced by `run_analysis.Rmd` 

##Steps to produce this project

- Plsease see the details in `run_analysis.md` and `codebook.md`.

- Those files  contain the instructions and steps with R code embedded  to produce this project.

- The final tidy data is in `tidydata.txt`. It can be loaded by `Data<-read.table("tidydata.txt", sep=" ", head=TRUE)`

- The codebok is in `codebook.md` . It gives the descriptions of the variables in the data frame prouduced by this project.

##Steps to reproduce this project

-  Open Rstudio to open R  Markdown file  `run_analysis.Rmd` to build the Project , then `run_analysis.md` , `codebook.md` and 
  `tidydata.txt` will be produced.
  
-  Alterativley the R script `run_analysis.r` can be used  to build the Project, but it only produces the final tidy dataset in `tidydata.txt`

 

