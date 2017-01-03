
class: center, middle

<image src="images/eScience_Logo_RGB_PP.png">

# Reproducibility and Open Science

### Allison Smith

<small>Follow along at: <a href="https://kallisons.github.io/ros-roadshow-2017-01-04-UWCoEnv">https://kallisons.github.io/ros-roadshow-2017-01-04-UWCoEnv</small>

---

layout: true

<div style="position: absolute; left: 650px; top: 370px;">
<image src="images/escience-network.png" width=500px style="opacity:0.2;filter:alpha(opacity=20);"> </div>

---
# Example from Dan Bolnick (Bolnick and Paull 2009):

<a href="http://ecoevoevoeco.blogspot.ca/2016/12/wrong-lot.html">http://ecoevoevoeco.blogspot.ca/2016/12/wrong-lot.html

- The authors measured morphology and diet on a large number of individual stickleback from a single lake on Vancouver Island, then tested whether pairwise difference in phenotype (between all pairwise combinations of individuals) was correlated with pairwise dissimilarity in diet (measured by stomach contents, or stable isotopes).

- Result: **They found morphology and diet to be positively correlated. And that’s what was reported in the paper, with the caveat (in the title!) that the association was weak.** 

- Dr. Tony Wilson from CUNY Brooklyn tried to recreate the same analysis, so that he could figure out how it worked and apply it to his own data. But Wilson could not quite recreate some of the core results from Bolnick and Paull (2009). 

- Bolnick dug up the original R code, sent it to Wilson, and after a couple of back-and-forth emails they found an error in the Mantel Test analysis.  When analyzed correctly, there was no correlation between morphology and diet. 

- Bolnick sent a retraction e-mail to the journal. 

---

# What makes research reproducible?

### .blue[The ability for someone outside the original research team to do the same analyses and get the same results.]

 - Descriptions of procedures and analyses are in the methods section of a scientific paper.  Data are included in the results section. 

 - In many cases, the raw data are too numerous to publish as part of the paper and the analyses are too complex to be reproduced without the original code.  

---

# Why publish data and code?

 1. Increase confidence of other scientists in your results

 2. Enable the building of new research directly on top of your past results
 
 3. Avoid repeated development of the same methods (improves efficiency)
 
 4. Increase collaborative opportunities
 
 5. Contribute to larger spatial and longer temporal scale analyses (get more citations)

---

# Data and code are not published because:

 1. Fear that someone will steal your research

 2. Not sure how to publish
 
 3. Messy file organization with no descriptions or notes
 
 4. Short-term time constraints

---

# Where to publish data:

### .blue[A long-term repository which provides a DOI for citations (DOI = Digital Object Identifier).]

Some Examples:
  1. Oceanography: BCO-DMO
  2. Earth and Environmental Science: Pangaea
  3. General: Dryad, Figshare, Zenodo
  4. University of Washington Libraries

---
# Where to publish code:

### .blue[A long-term repository which provides a DOI for citations (DOI = Digital Object Identifier).]

Some Examples:
  1. Zenodo
  2. University of Washington Libraries

---
# Tools for code development:

### .blue[...BUT not places to publish code]

Github/Bitbucket:
  1. collaborate with other code developers
  2. version control
  3. directions to directly publish code from Github on Zenodo <a href="https://guides.github.com/activities/citable-code/
">https://guides.github.com/activities/citable-code/

Jupyter Notebooks: contain both code which can be executed and text describing the code in an easy-to-read format.  

Docker: is used to create reusable software environments

---
# Licensing for data and code:

### .blue[All data and code are protected by copyright law in the United States.  If there is no license, data and code cannot be used by anyone else by default.]

Examples of the most open licenses:
 1. MIT License
 2. BSD License
 3. Creative Commons Licenses (CC BY)

---
# README files for data and code:

### .blue[Documentation that is critical for citation and use of data or code.]

  1. Citation(s) for scientific paper(s)
  
  2. Description of data or code contents
  
  3. List of dependencies

  4. Instructions for using data and code 

  5. Acknowledgements

---
# Timing of publishing data and code:

  1. Publish independently
  
  2. Publish in a dedicated paper
  
  3. Publish at the same time as a scientific paper, with links to data and code included in the paper

---

# Data and code reviews:

Starting to be done in some fields.  

Should we consider it in the environmental sciences? 

Time constraints on volunteer reviewers? 

---
# Increasing the academic value of data and code:

  1. Publish your data and code as your scientific paper is published
  
  2. Cite code and data resources in your scientific papers
  
  3. Publish code and data in dedicated papers
	    a. Nature Scientific Data
	    b. Software notes in Ecography
	    c. Geoscientific Instrumentation, Methods and Data Systems
	    d. Geoscientific Model Development
	    e. Earth Systems Science Data
     
---
# Get involved:

Join the UW reproducibility mailing list: 

<a href="http://mailman11.u.washington.edu/mailman/listinfo/reproducible">http://mailman11.u.washington.edu/mailman/listinfo/reproducible 

---
# Need help making your research reproducible?

  1. Websites: <a href="http://uwescience.github.io/reproducible/">http://uwescience.github.io/reproducible/

  2. eScience Office Hours: <a href="http://escience.washington.edu/office-hours/">http://escience.washington.edu/office-hours/

  3. Me: kasm@uw.edu, Office OSB 307




