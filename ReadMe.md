---
title: "README.md"
author: "Becca Weingarten"
date: "January 28, 2016"
output: html_document
---




##**ReadMe**

This is the course project for Getting & Cleaning Data. This file contains all the assumptions and info to make the whole project fit together.

##**Data**

The data is here: *https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip*

It is assumed for this project the data files are downloaded already. The download is a .ZIP file. My code assumes the .ZIP is unpacked into a sub-folder called "data" and the structure of the .ZIP is intact (with a directory called "UCI_HAR_Dataset")

Secondly I have a code book to define and explain the data, structure and all of the variables.

##**Fitting it all together**

Once the data files are unpacked into a "data" directory, all you need to do to get this to run:

1. Change the working directory to the parent of "data" (if it isn't already) setwd({path to parent})
2. Source run_analysis.R

*note: see run_analysis.R for a walk thru of what the code is doing, each step of the way.*



