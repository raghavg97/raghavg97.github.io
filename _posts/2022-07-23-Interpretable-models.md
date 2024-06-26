---
title: 'Interpretable Models'
date: 2022-07-23
permalink: /posts/2022/07/Interpretable Models/
tags:
  - deep neural networks
  - differential equations
  - models
---

Data driven Physical Models?
======

Traditionally, a model of a physical system is always interpretable starting from the equations of motion derived from the simple rules of motion to more complicated systems of differential equations. With the development of these kind of models, there was an almost parallel development of statistical models. These statistical models usually have nothing to much do it with the "physical laws". It was, in fact, a validation for the experiments to prove whether a particular physical model is correct or not. 

With the recent advent of deep learning or the more general machine learning, the boundaries between the statistical model and physical model are probably merging. What does that even mean? To break it down, conventional machine learning is still a statistical model. It appeared to be magical that a statistical model, let us imagine a deep neural network model, can predict complicated functions with a lot of ease. So, the requirement of a physical model went suddenly out of sight since statistical model can predict whatever we want for any given scenario. But there is one bottleneck - THE DATA. 

A typical deep learning model requires a lot of data. For some problems, like the very famous image classification, they are available in plenty. For many problems in physics or material science, the data is pretty less. So, the typical practice is to still use the good old Ordinary or Partial Differential Equations (ODEs/PDEs) to model a system. Also, there is enormous research on how to solve these differential equations through direct methods and so many numerical methods like Finite Elements Methods. 

Recently, it is come to attention for many researchers that the deep neural network can solve the differential equations through what is known as the Physics-informed Neural Networks (Note: there are many different ways to embed physics information into a data driven model). It is remarkably simple and extremely powerful in what it does. It can totally change the way researchers thought about differential equations. It can potentially merge the statistical models and physical models. It can make the statistical model more interpretable and the physical model more closer to real world which has innumerable advantages.    





