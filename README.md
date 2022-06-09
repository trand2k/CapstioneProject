# Image classification with Bilinear Model

## Project Overview
I'm using bilinear model for flood detection.
This project can be used as a complete guide to EDA and machine learning technique for sentence classification tasks accompanied with advice for practioners. It will cover:

+ Craw data
+ Preprocessing data image
+ Tranfer learning with EfficientNetB4
+ Building bilinear model with 2 model EfficientNetB4
    +trainning with freezing base model weight
    +trainning with unfreezing base model weight
+ compare result

## Table of Contents

 * [Project Overview](#project-overview)
 * [Problem_statement](#problem-statement)
 * [Requirements](#requirements)
 * [File Descriptions](#file-descriptions)
 * [Dataset](#dataset)
 * [Acknowledgements](#acknowledgements)
 
## Problem statement

I try to improve preformance of EfficientNetB4. I using 2 EfficientNetB4 model to improve. This is called Bilinear Model. 
 
## Requirements
This project should be run with these following libraries
- numPy
- pandas
- tensorflow
- bs4
- opencv2

## File Descriptions
- 2 file data:
  + devset_images_gt.csv : data contain label
  + devset_images_metadata.json : metadata file, using to crawdata
- 1 notebook

## Dataset
find dataset in this link : https://www.kaggle.com/competitions/spr22-AIG201m-DPL301m
- 2 file data:
  + devset_images_gt.csv : data contain label
  + devset_images_metadata.json : metadata file, using to crawdata

find image data in https://drive.google.com/drive/folders/1CDaWl834KMQY_yfiiiG_-lLx4YDzVrof?usp=sharing

## Acknowledgements
- Thanks Udacity for great project 
- You can find Bilinear model in this paper: https://arxiv.org/abs/1504.07889
