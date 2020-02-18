---
date: "2020-02-12T00:00:00Z"
external_link: ""
image:
  caption: Peer review process
  focal_point: BottomLeft
slides: 
summary: 
tags:
- Programming
- R
title: Peer review with ghclass
subtitle: 
url_code: ""
url_pdf: ""
url_slides: "anders_lightning_ballroomA.pdf"
url_video: https://resources.rstudio.com/rstudio-conf-2020/lightning-talk-therese-anders
links:
---

The [`ghclass`](https://rundel.github.io/ghclass/index.html) package in `R` provides a suite of functions to manage courses via GitHub repositories. The package has recently been supplemented with the functionality to implement **peer review**. Developed during my 2019 summer internship with RStudio, in collaboration with [Mine Çetinkaya-Rundel](http://mine-cr.com) and [Colin Rundel](http://www2.stat.duke.edu/~cr173/), the peer review functions in [`ghclass`](https://rundel.github.io/ghclass/index.html) interface with the GitHub API to create review repositories, move files between authors and reviewers, submit feedback, and collect grades. 

Peer review enables instructors of large data science classes to provide substantive feedback to students beyond what is feasible with standard code review via automated grading and continuous integration. It facilitates peer learning, which is shown in literature to have positive learning outcomes, and can reduce the burden of grading by course staff. 

[`ghclass`](https://rundel.github.io/ghclass/index.html) is available as a development version package from GitHub:
```r 
# install.packages("remotes")
remotes::install_github("rundel/ghclass")
```

Instructors might find the following material helpful:

- [Getting started with classroom management via `ghclass`](https://rundel.github.io/ghclass/articles/ghclass.html)
- [Peer review vignette](https://rundel.github.io/ghclass/articles/peer.html)
- [Instructions for students](https://rundel.github.io/ghclass/articles/instructions_students.html)
