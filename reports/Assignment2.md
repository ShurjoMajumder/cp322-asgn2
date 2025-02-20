---
title: "Assignment 2 Master Report"
date: "23 Feb 2025"
author: 
  - "Shurjo Majumder (ID: 169035249)"
  - "Robin Chen (ID:...)"
  - "Petar Mancic (ID:...)"
geometry: margin=2cm
classoption:
- twocolumn
---

## Part 1: Feature Maps

> Completed By: ...

## Part 2: Logistic Regression

> Completed By: ...

## Part 3: Linear Regression

> Completed By: Shurjo Majumder

### Introduction

This document outlines the final results of the third part of Assignment 2. A gradient descent linear regression algorithm was used to model a surface lying in 3D space.

### Performance Chart

The following graph demonstrates the mean squared error of the model for various learning rates. The MSE was determined through 10-fold cross validation over the training dataset.

![MSE by Learning Rate](../assets/mse_by_learning_rate.png)

The mean squared error tends to increase as the learning rate increases, meaning that lower values produce less error. The least error was observed when the learning rate was $\lambda = 0.1$.

### Best Learning Rate

The best learning rate found was $\lambda = 0.1$. It displayed a mean squared error of $\approx 1.129$ during cross validation, and a mean squared error of $\approx 1.412$ during testing with the test dataset.
