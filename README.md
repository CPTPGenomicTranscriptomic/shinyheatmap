<div align="center">

# shinyheatmap

<img src="https://user-images.githubusercontent.com/9893806/35200211-c8d27534-febe-11e7-837f-477e2b606ca3.png">

##### R Shiny web app for enormous biological heatmaps

</div>

## About
Purpose: To create user-friendly, highly customizable static and interactive biological heatmaps of big datasets in a web browser.

If you are using `shinyheatmap` in your work, please cite the paper (http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0176334).

## Citation
Khomtchouk BB, Hennessy JR, Wahlestedt C: "shinyheatmap: Ultra fast low memory heatmap web interface for big data genomics."  <i>PLoS One</i>.  2017, 12(5): e0176334.  

## Funding

`shinyheatmap` was financially supported (2014-2017) by the United States Department of Defense (DoD) through the National Defense Science and Engineering Graduate Fellowship (NDSEG) Program. This research was conducted with Government support under and awarded by DoD, Army Research Office (ARO), National Defense Science and Engineering Graduate (NDSEG) Fellowship, 32 CFR 168a.

## Usage (for general public)

##### http://shinyheatmap.com/

## Installation

### Requirements

Please check CRAN (<a href="https://cran.r-project.org/" target="_blank">https://cran.r-project.org/</a>) for the installation of R.  
Please check <a href="https://www.rstudio.com/" target="_blank">https://www.rstudio.com/</a> for the installation of RStudio. 


## How to run (for users)

##### Install the R Shiny package

Start an R session using RStudio and run this line:  
```
if (!require("shiny")){install.packages("shiny")}
```

##### Start the app  

Start an R session using RStudio and run this line:  
```
shiny::runGitHub("shinyheatmap", "CPTPGenomicTranscriptomic")
```
This command will download the code of shinyheatmap from GitHub to a temporary directory of your computer and then launch the Gshinyheatmap app in the web browser. Once the web browser was closed, the downloaded code of shinyheatmap would be deleted from your computer. Next time when you run this command in RStudio, it will download the source code of shinyheatmap from GitHub to a temporary directory again. 

##### Choose your analysis set up  

Fist of all read the instructions at the rigth panel.

Once you are ready for the exam, you can download some example files to test the tool and look at the input file format.

Just upload the download file as input.

Click on the Static Heatmap button at the rigth panel.




## How to run (for developers only)

##### Git clone this repo to your computer, and in RStudio type:
* `setwd("~/path/to/my_directory_that_contains_shinyheatmap_folder")`
* `install.packages("shiny")`
* `library(shiny)`
* `install.packages("rsconnect")`
* `library(rsconnect)`
* `install.packages("data.table")`
* `library(data.table)`
* `install.packages("gplots")`
* `library(gplots)`
* `install.packages("heatmaply")`
* `library(heatmaply)`
* `library(tools)`
* `runApp("shinyheatmap")`

## Presentation
`shinyheatmap` was presented at the Bay Area R User Group (BARUG) Meeting, which was held at Intuit Building 9 – Invention and Innovation, Mountain View, CA.  Slides available here: https://github.com/joseph-rickert/BARUG/blob/master/Bohdan-Khomtchouk_BARUG_November-2017.pptx
