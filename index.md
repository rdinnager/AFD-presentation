---
title       : For Ecology, Unaligned is Fine  
subtitle    : Phylogenetic diversity metrics calculated using an alignment-free method are faster, more accurate, and more consistent than alignment-based methods
author      : Russell Dinnage
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

## Understanding Biodiversity of Communities with Thousands (upon Millions) of Species

![plot of chunk test](assets/fig/test.png) 


* What is Diversity? 

---

## Understanding Biodiversity of Communities with Thousands (upon Millions) of Species

![plot of chunk test1](assets/fig/test1.png) 


* What is Diversity?
* Some species look (and act) more similar than others.

---

## Understanding Biodiversity of Communities with Thousands (upon Millions) of Species

![plot of chunk test2](assets/fig/test2.png) 


* What is Diversity? 
* Some species look (and act) more similar than others.
* Phylogenetic Diversity - Uses genetic data to estimate potential ecological similarity without measuring traits

--- &twocol

## Phylogenetic Diversity

- Uses genetic data to estimate potential ecological similarity without measuring traits
- For thousands of species, it is still very time consuming
- How can we adapt this useful diversity measure to **_rapid_ biodiversity assessment**?


*** =left

### __Alignment-free Phylogeny__

![plot of chunk AFP](assets/fig/AFP.png) 

**Four types of alignment-free phylogeny methods**
- *Word Based*, *Substring Based* 
- *Information Theory Based*
- *Graphical*


*** =right

### **Alignment Based Phylogeny**

![plot of chunk AP](assets/fig/AP.png) 

**One alignment-based method**

>- *MUSCLE + RAxML*


--- &twocol

## Alignment-free Phylogenetic Diversity?

*** =left

<video   controls="controls" loop="loop"><source src="assets/fig/treeanimate.ogg" />video of chunk treeanimate</video>


*** =right

- 4000 simulations of phylogenies, genomes, and communities

<---------------

- Calculated Alignment-Free genetic distances and Alignment-based phylogenetic distances
- How well did they capture the 'true'
  1. Branch-length distribution?
  2. Topology?

--- &twocol

## Results

*** =left

![plot of chunk Fig1aa](assets/fig/Fig1aa.png) 


*** =right

--- &twocol

## Results

*** =left

![plot of chunk Fig1ab](assets/fig/Fig1ab.png) 


*** =right
![plot of chunk Fig1bb](assets/fig/Fig1bb.png) 


---

## Results

![plot of chunk Fig3](assets/fig/Fig3.png) 


