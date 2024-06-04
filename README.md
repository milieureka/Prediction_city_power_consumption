# Predicting electricity consumption in Tetouan city using statistical ML and Deep leaning
*Reproduced the result from research paper "[Comparison of Machine Learning Algorithms for the Power Consumption Prediction: Case Study of Tetouan City](https://ieeexplore.ieee.org/document/8703007)". Use public dataset at [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/849/power+consumption+of+tetouan+city).*

In addition, I build ensemble models to check whether its improve performance.

## Language:
Python: sklearn, keras

## Overview:
Predicting electricity consumption is a crucial activity that provides valuable insights to utility companies, enhancing their efficiency and effectiveness. Machine learning models are recognized as the most accurate tools for such predictions. 

The dataset was combined from 3 distinct power distribution networks in Tetouan city, located in northern Morocco sourced from the Supervisory Control and Data Acquisition (SCADA) system,
covers the period from January 1, 2017, to December 31, 2017. It is a unique dataset, and it does not have any missing data. It is consisted of the date, time and the consumption of the three distribution networks.

## Used ML methods:
The models aims to forecast electricity consumption at intervals of every 10 minutes and/or every hour. 5 models was build which are: 
- Feedforward neural network with a back-propagation algorithm,
- Random forest,
- Decision tree,
- Support Vector Machine forregression (SVR) with a radial basis function kernel,
- Stacked Generalization

## EDA
