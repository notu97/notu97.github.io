---
layout: post
title:  "Self-Driven Autonomous Car – A pilot project"
date:   2017-08-10 22:21:59 +00:00
image: /images/self-driving-car.jpg
categories: project
author: "Shiladitya Biswas"
authors: "<strong>Shiladitya Biswas</strong>, Srivatsa Sinha"
venue: 
arxiv: 
video: https://www.youtube.com/watch?v=2saD4n-uNxE
code: https://github.com/notu97/Neural-Network-Car?tab=readme-ov-file
website: 
affiliation: "Independent Project"
---
This project marked one of my earliest endeavors into creating a camera-based self-driving car. The car navigated autonomously by following a white path on a black background. A smartphone was utilized to transmit live video feeds to a laptop, where the images underwent pyramidal reduction processing and were subsequently fed into a neural network. The neural network's output layer comprised of four nodes—Left, Right, Forward, and Backward—responsible for decision-making. These decisions were then relayed back to the car via Bluetooth and executed by an Arduino Uno board, enabling the vehicle to maneuver along the road. This project served as a proof of concept for my UG thesis project "A Cloud based End to End Self Driving Car Prototype". The training dataset that was collected for this project can br found [here](https://www.dropbox.com/scl/fi/x91mmsn8v1oyko9pokods/Compress_Data.tar.gz?rlkey=pifj8zadcgb0piz45lb69cyv0&e=1&dl=0).