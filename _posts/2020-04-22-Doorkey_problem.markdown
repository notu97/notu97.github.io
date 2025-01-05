---
layout: post
title:  "Door-Key Problem."
date:   2020-04-22 22:21:59 +00:00
image: /images/doorkey.gif
categories: project
report: /pdfs/ECE276B_PR1_Report.pdf
author: 
authors: "<strong>Shiladitya Biswas</strong>"
venue: 
arxiv: 
code: 
website: 
youtube: 
affiliation: "UC San Diego"
---
The goal here was to figure out a set of control policy that enables the robot (red triangle) to first fetch the key, open the door with the key and then reach the goal location. To achive this, I formulated the problem as a Markov Decision Process (MDP) in which each cell on the 2D grid has a reward associted to it. I then implemented Dynamic Programming to generate the optimum control policy. This was a course project for [ECE276B](https://natanaso.github.io/ece276b2020/) at UC San Diego, hence the code cannot me made public.
