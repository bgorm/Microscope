# MicroScope

## About

MicroScope is an RShiny and JavaScript (D3.js) software program designed to produce dynamic, interactive heatmaps in a web browser. MicroScope allows you to magnify any portion of a heatmap by a simple click-and-drag feature to zoom in, and a click-once feature to zoom out. MicroScope is designed with large heatmaps in mind (e.g., gene expression heatmaps with thousands of genes), where individual entries quickly become unreadable as more and more add up. However, MicroScope allows you to repeatedly zoom in to any sector of the heatmap to investigate a region, cluster, or even a single gene. You can scroll up and down the page of your web browser to see more genes than fit your window. MicroScope also allows you to hover the mouse pointer over any specific gene to show precise expression level details. As such, MicroScope presents a significant advance in heatmap visualization technology over current standard protocols. 

MicroScope is an ongoing bioinformatics software project fully financially supported by the United States Department of Defense (DoD) through the National Defense Science and Engineering Graduate Fellowship (NDSEG) Program. This research was conducted with Government support under and awarded by DoD, Army Research Office (ARO), National Defense Science and Engineering Graduate (NDSEG) Fellowship, 32 CFR 168a.

Current work is underway to expand Microscope's user-friendly features (e.g., multiple color schemes, download button, etc).

Please cite: "Khomtchouk BB, Dargis-Robinson V, Hennessy JR, Wahlestedt C.  “MicroScope: magnifying interactive gene expression heatmaps with RShiny and JavaScript”. bioRxiv doi: http://dx.doi.org/10.1101/034694" within any source that makes use of any methods inspired by MicroScope. 

## Usage (for general public)

##### Just click here!... https://microscope.shinyapps.io/microscope

## Installation (for developers only)

### Requirements for developers

* R programming language
  * RStudio

## How to run (for developers only)

##### Git clone this repo to your computer, and in RStudio type:
* `setwd("~/path/to/my_directory/Microscope")`
* `install.packages("d3heatmap")`
* `library(d3heatmap)`
* `install.packages("shiny")`
* `library(shiny)`
* `install.packages("ggplot2")`
* `library(ggplot2)`
* `runApp("microscope")`

## Screenshots

<img width="1440" alt="pic1" src="https://cloud.githubusercontent.com/assets/9893806/11985011/aecd4088-a98e-11e5-9e7d-b079c440e528.png">

<img width="1440" alt="pic2" src="https://cloud.githubusercontent.com/assets/9893806/11985017/b6d04424-a98e-11e5-93ea-2acd4664b406.png">

<img width="1440" alt="pic3" src="https://cloud.githubusercontent.com/assets/9893806/11985021/ba9bcd62-a98e-11e5-9463-ec5ee1e189c6.png">

