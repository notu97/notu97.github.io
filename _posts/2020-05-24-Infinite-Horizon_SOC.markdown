---
layout: post
title:  "Infinite-Horizon Stochastic Optimal Control."
date:   2020-05-24 22:21:59 +00:00
image: /images/inverted_pendulum.gif
categories: project
report: /pdfs/ECE276B_PR3_Report.pdf
author: 
authors: "<strong>Shiladitya Biswas</strong>"
venue: 
arxiv: 
code: 
website: 
youtube: 
affiliation: "UC San Diego"
---
Implemented and compared the performance of value and Policy iteration-based controller in terms of convergence time and state space resolution on an Inverted pendulum balancing controller in Python. Formulated a Markov Decision Process (MDP) for the system by defining a discreet state space over the angular velocity, angular postion and control input of the pendulum. A transtion matrix is built over the 3D state-space of the system by using Euler discretization for state propgation and brownian noise to model the uncertanities in the system. Finally, a cost function is defined over the state-space which is ultimately used to solve the infinite-horizon discounted optimal control problem, thereby generating the optimal control policies. This was a course project for [ECE276B](https://natanaso.github.io/ece276b2020/) at UC San Diego, hence the code cannot me made public.
