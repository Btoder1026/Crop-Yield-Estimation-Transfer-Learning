# Crop-Yield-Estimation-Transfer-Learning
## Problem Statement
Humanity continues to grapple with numerous challenges concerning hunger, primarily driven by food supply issues. One of the key hurdles is the growing global population, which places immense pressure on the already strained food systems. Addressing these multifaceted challenges demands collective efforts, innovative approaches, and sustainable agricultural practices to ensure food security for all.

NOTE: You need to create a Github repo that will allow you to submit multiple notebooks involved in this assignment.

## Task 1 (50 points)
You are tasked to build a computer vision system that will process drone images showing the health of the crops and predict the yield. This will help the farmers to understand the state of their crops and plan the next steps accordingly. As a data scientist, you are required to build a machine learning model and after a litarature survey you have decided to use an approach similar to the one described in this paper.

Luckily you are also able to locate some helper code in this repository.

## Task 1A (20 points)
Replicate the results of the code in the repository ensuring that you train the model with a much larger number of images, epochs and other parameters of your choice to present the best possible performance.

## Task 1B (30 points)
Unfortunately some of the berries are bad - they have a black color and it is interspersed amongst the good berriers. Produce images where the bad berries are 0% to 100 % of the total berries. For each image you sample uniformly random between 0 and 100 to determine the percentage of bad berries. You need to implement a system that separates bad crops - an image is bad when black berries exceed > 50% of the total berries per image.

Describe your approach on the modeling strategy on how to achieve that, implement the method and obtain results that manifest the performance of your predictor.

## Task 2 (50 points)
Read about Transfer Learning from chapter 14 of this textbook and replicate the results for the model described for the dataset tf_flowers. The code for this task is in this notebook and you need to copy the relavant code into a separate notebook.

Produce classification results with and without transfer learning and compare the results.
