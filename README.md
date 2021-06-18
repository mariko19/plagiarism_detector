# Plagiarism Detection Project
This repository includes files for deploying a plagiarism classifier using AWS SageMaker.

## Project Overview
In this project, I am tasked with 
- building a plagiarism classifier that compares a student answer text file with an original Wikipedia source file, and also performs binary classification; 
- computing a few features such as **containment** and **longest common subsequence**, to compare the similarity of the given answer text and the original Wikipedia text file; selecting "good" features by analyzing the correlation between computed features; 
- labeling the given answer file as either plagiarized or not, according to the above-mentioned selected features;
- training a plagiarism classifier model and deploying it using SageMaker;

The Project Notebook I submitted for revision to Udacity's reviewers includes the following files.

**Notebook 2:** Plagiarism Feature Engineering

**Notebook 3:** Training and Deploying a Model in SageMaker

**training file:** `source_sklearn`/`train.py`

Note that `problem_unittests.py` and `helpers.py` are files for testing.

## Project Instructions 
For more details about project, please refer to [Udacity/ML SageMaker Studies](https://github.com/udacity/ML_SageMaker_Studies/tree/master/Project_Plagiarism_Detection). 





