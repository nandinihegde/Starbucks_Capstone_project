# Starbucks Capstone Challenge
This project is a submission for Udacity Data Scientist Nanodegree program.
A blog detailing the findings of this project can be found in on https://hegdenandini.medium.com/recommending-starbucks-offers-to-members-c6cd6fbb78a7

## Table of Contents
1. Required Installations
2. Project Background
3. Dataset Descriptions
4. Results
5. Licensing, Authors, and Acknowledgements


## Installation
Libraries required at listed at the top of the notebook.The code should run with no issues using Python versions 3.*.

## Project Background

This project is a submission for Udacity Data Scientist Nanodegree programy. The dataset was provided by the program and contains details about how people make purchasing decisions and how those decisions are influenced by promotional offers. Our task is to make a recommendation engine that recommends offers to be sent to a particular customer inorder to maximise gains.

We are interested to answer the following two questions:

Which offer should be sent to a particular customer to let the customer buy more?
Which demographic groups respond best to which offer type?

## Dataset Descriptions
The notebook available here showcases work related to the above questions.

The dataset consists of three files:
* portfolio.json: This dataset containing offer ids and metadata about each offer (duration, type, etc.)
* profile.json: This dataset contains demographic data for each customer
* transcript.json: This dataset contains records for “transactions”, “offers received”, “offers viewed”, and “offers completed”

## Results
Based on our analysis we found that Starbucks customer demographic is middle aged to older folks with a annual income <$100000.
Women tend to respond to offers more and social media have the highest responses. Finally we identified that BOGO offers have the highest gains for Starbucks

## Licensing, Authors, Acknowledgements
Dataset credits to Starbucks.
