# Statistical Learning Analysis of Tweets using PCA and Random Forest Models (in progress)

This project is a statistical learning analysis of posts on Twitter (Now X) posted by Donald Trump and Joe Biden from January through April of 2020. It is aimed towards identifying similarities, differences, and other patterns in words used by the two presidential candidates. 

## Usage

To use this project with R, follow these steps:

1. **Install R**: If you haven't already, download and install R from the [official R website](https://cran.r-project.org/).

2. **Download RStudio**: RStudio is the interface in which R will be coded. If you do not have RStudio, the program will not run correctly (https://posit.co/products/open-source/rstudio/)

3. **Install and Load Required Packages**: This project relies on several R packages. To install them, run the following commands in RStudio:

   ```R
   install.packages("tidyverse")
   install.packages("tidytext")
   install.packages("lubridate")
   install.packages("ggwordcloud")

   library(tidyverse)
   library(tidytext)
   library(lubridate)
   library(ggwordcloud)

   #Ctrl + Shift + C (on Windows/Linux) or Command + Shift + C (on macOS) to comment out
   install.packages when finished installing.

5. **Load the CSV and gif files**: This code is formatted to go out and grab the files from the internet. Ensure your machine is connected to the internet and then run all chunks.


## Viewing

Alternatively, to view this project using HTML, follow these steps:

1. Select the HTML file from the repository
2. Download and open a copy on your device.

## Sources

Data was sourced from Kaggle.

- https://www.kaggle.com/datasets/austinreese/trump-tweets
- https://www.kaggle.com/datasets/rohanrao/joe-biden-tweets
