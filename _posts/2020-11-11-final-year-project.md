---
layout: post
title:  "Final Year Project"
date:   2020-11-11
excerpt: "Vehicle history cross-referencing using ANPR and OCR."
project: true
tag:
- blog
- final year
- college
- machine learning
- ocr
- anpr
- statistics
- projects
comments: false
---

<center>For my 4th year project, I'm working on a vehicle cross-referencing service that aggregates listings from different providers and matches them based on their registration plate numbers.</center>
![OCR'd image](https://i.imgur.com/jTS68uf.png) 
{: .img-small}

# Design

The goal is to deploy a Kubernetes cluster to orchestrate a network of Docker containers that:
- Scrape the information from the appropriate listing websites
- Run the Automatic Number Plate Recognition (ANPR) / OCR (Optical Character Recognition) script to identify the registration plate
- Match it against current records in the database
- Feed the updated information into the database
- Deliver a smooth user experience using React
- Attempt to predict possible insurance prices

### The project is still ongoing and will be finished towards the end of April 2021
### I will be updating this page as time goes on and the project starts taking shape 😃
