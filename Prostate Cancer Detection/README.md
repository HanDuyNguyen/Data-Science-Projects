# Detecting Prostate Cancer on Images of Prostate Tissue Samples using Machine Learning
In this notebook, we are going build a machine learning model that help detect Prostate Cancer based on images of Prostate Tissue samples and estimate severity of the disease.

## 1. Problem definition

> How well can we detect and estimate severity of Prostate Cancer given images of Prostate Tissue samples ?

For more description about the problem and its importance check: https://www.kaggle.com/c/prostate-cancer-grade-assessment/overview.

## 2. Data

The data is downloaded from Kaggle Prostate Cancer Grade Assessment competition: 
https://www.kaggle.com/c/prostate-cancer-grade-assessment/data.

There are 4 main datasets:

* [train/test].csv contains ID code for the images.


* train_images: The images. Each is a large multi-level tiff file. You can expect roughly 1,000 images in the hidden test set. Note that slightly different procedures were in place for the images used in the test set than the training set. Some of the training set images have stray pen marks on them, but the test set slides are free of pen marks.

* train_label_masks: Segmentation masks showing which parts of the image led to the ISUP grade. Not all training images have label masks, and there may be false positives or false negatives in the label masks for a variety of reasons. These masks are provided to assist with the development of strategies for selecting the most useful subsamples of the images.

## 3. Evaluation

Submissions are scored based on the quadratic weighted kappa, which measures the agreement between two outcomes. This metric typically varies from 0 (random agreement) to 1 (complete agreement). In the event that there is less agreement than expected by chance, the metric may go below 0.

For more on the evaluation of this project check: https://www.kaggle.com/c/prostate-cancer-grade-assessment/overview/evaluation.

## 4. Features

Kaggle provides details of all features of the data sets. Check: 
https://www.kaggle.com/c/prostate-cancer-grade-assessment/data

## Instruction

* The file  <code> ProstrateCancerDetectionUnet.ipynb </code> contains the main codes of this project.

