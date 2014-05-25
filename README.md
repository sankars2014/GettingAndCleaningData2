    Getting and Cleaning Data Project

    Unzip the source ( https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip )

    into a folder on your local drive, say C:\R\Course\UCI HAR Dataset\

    Put run_analysis.R to C:\R\Course\UCI HAR Dataset\

    in RStudio: setwd("C:\\R\\Course\\UCI HAR Dataset\")

    and then: source("run_analysis.R")

    The latter will run the R script, it will read the dataset and write these files:

    merged_clean_data.txt -- 8.35 Mb, a 10299x68 data frame

    data_set_with_the_averages.txt -- 0.225 Mb, a 180x68 data frame

    Use data <- read.table("data_set_with_the_averages.txt") to read the latter to verify the contents.
    
