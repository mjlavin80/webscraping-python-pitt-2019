# Web-scraping and Web-crawling with Python

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mjlavin80/webscraping-python-pitt-2019/master?filepath=https%3A%2F%2Fgithub.com%2Fmjlavin80%2Fwebscraping-python-pitt-2019%2Fblob%2Fmaster%2Fscraping_examples%2FScrape-Munge-Star-Trek.ipynb)

Schedule and various materials for "Web-scraping and Web-crawling with Python" Workshop, University of Pittsburgh, April 2019

# Schedule

## Workshop Begins at 1 p.m.

## Install Anaconda, connect to wifi 
### (approximately 15 minutes)

Note: Anaconda takes up 2.17GB of space! If you are short on disk space, you might want to install miniconda, which is a lightweight version. 

1. Go to https://www.anaconda.com/download/ and select Python 3.6 download (make sure the installer version matches your operating system)
2. Click and the downloaded installer and follow the on-screen instructions (on macs, this is a .pkg file
After it's done installing (can take 5-10 minutes), double-click the application "Anaconda-Navigator" and make sure it loads properly
3. If you would like to work in a Jupyter Notebook (which I recommend), you can open "Anaconda Navigator," click the Launch button on the Jupyter Notebook card (not the JupyterLab card), and then click "New > Python 3" to load a new notebook.

For Windows-specific instructions, visit https://docs.anaconda.com/anaconda/install/windows/

## Participant Intros 
### (approximately 20 minutes)

As we go around the room, tell us your name and what you are studying or working on. If you have a specific example, name something you are interested in scraping and why it's potentially a challenge for you. If your interest is more general, say a little about the kinds of sites you would want to scrape and why. 

## Fundamentals Pecha Kucha 
### (20 seconds x 20 slides = 7 minutes, plus transition time)

Below is a copy of my slide deck for later reference:

https://docs.google.com/presentation/d/e/2PACX-1vTyU_MB3a6KeBckheSvJ-WmkGUC1COVa5zlM6B8FA-rju2XL4qkf7aKhBt5Zynjn_SwEypxhyP3Pi8_/pub?start=false&loop=false&delayms=20000 

## Activity 1 
### (approximately 15 minutes)

In this part of the workshop, I'll take us through some of the examples I used in my slides, as well as a couple wildcards. We will look at the source code of several websites and try to think about how to break down the problem of web-scraping. The example sites are:

- https://mjlavin80.github.io/pseudonyms/ 
- http://www.oed.com/browsedictionary
- https://memory-alpha.fandom.com/wiki/Starfleet_casualties_(22nd_century)
- https://memory-alpha.fandom.com/wiki/Starfleet_casualties_(23rd_century)
- https://memory-alpha.fandom.com/wiki/Starfleet_casualties_(24th_century) Note: these three wiki pages were used to create a data visualization of Star Trek deaths by shirt color. See http://digg.com/2019/star-trek-shirt-color-death-data-viz and https://www.startrek.com/article/did-redshirts-really-die-more-often-on-tos for some background.
- http://movies2.nytimes.com/learning/general/onthisday/bday/0101.html I scraped the obituaries from the "On This Day" series for a tutorial I wrote for _The Programming Historian_ (forthcoming)
- http://www.nuforc.org/webreports/ndxpost.html Note: A dataset was scraped, geolocated, and time standardized from NUFORC data by Sigmond Axel (see https://github.com/planetsig/ufo-reports). The goal for us is to think about how it would be done.

## Break around 2:10 p.m. 
### (approximately 5 minutes)

## Best Practices Pecha Kucha 
### (20 seconds x 20 slides = 7 minutes, plus transition time)

https://docs.google.com/presentation/d/e/2PACX-1vTXMKkAhOD7yPHUTp51_TuKKYCDTA7qfgxhSSkddb_U__NB1pwgSrEAGVrX4QnqNniftBkhxrVXaLla/pub?start=false&loop=false&delayms=20000

## Activity 2 
### (approximately 20 minutes)

In this section of the workshop, we will break into groups and focus on some of the webscraping questions or use cases you have in mind. If participants don't have examples sites of their own, we will return to my examples and discuss end-to-end data collection, including modeling, scraping, crawling, and setting up datastores. 

## Share Results 
### (approximately 20 minutes)

## Farewells 
### (approximately 10 minutes)
