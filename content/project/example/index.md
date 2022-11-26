---
title: Study and development of the algorithm Neuroevolution of Augmented Topologies in the Pac-man environment
summary: Thesis about the use of evolutionary algorithms to generate artificial neural networks with optimal parameters and topology for solving the game of Pac-man in deterministic and stochastic environments.
tags:
  - Neural Networks
  - Evolutionary Algorithms
date: '2022-10-09'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

links:
url_code: 'https://github.com/alejandrohdez00/Neuroevolution---Pacman'
url_pdf: '20220908_TFG_ALEJANDRO_HERNANDEZ_ARTILES.pdf'
url_slides: ''
url_video: 'https://www.linkedin.com/posts/alejandro-hernandez-artiles_algorithms-neuralnetworks-research-activity-6997651318991400960-9Lfd?utm_source=share&utm_medium=member_desktop'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

Artificial neural networks are currently very popular universal function approximators used in many Artificial Intelligence systems. One of their peculiarities is that for the same problem, the architecture of a neuronal network can drastically change the result, so the structure must be carefully chosen to optimize the task to be treated.\
\
However, such a suitable architecture is usually sought by means of a trial-and-error heuristic, which is a costly and time-consuming process.\
\
Therefore, in this work, we wanted to experiment with methods using Neuroevolution, a type of machine learning that uses genetic algorithms to perform searches over the topological space of a neural network, in order to find the one that optimizes the given task.\
\
Specifically, in this work we will study the algorithm of Neuroevolution of Augmented Topologies (NEAT). This algorithm will be analyzed and tested on an abstraction of the Pac-man game, using enemies whose movements follow a non-deterministic pattern. The objective will be to study the performance and limits of the algorithm, while trying to create an AI agent controlled by an optimal neural network.
