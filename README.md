# Arabic-OCR
The implementation of the OCR system for Arabic historical documents using the selected data from KITAB corpus. The figure below shows the main phases in our methodology for recognizing Arabic text using deep learning. The process begins with the pre-processing of the input page image, followed by line and word segmentation. The segmented word images are then divided into three distinct sets, consisting of a training set (80%), a validation set (10%) for monitoring the model's performance during training, and a testing set (10%) for evaluating the model. 

<img width="416" alt="Picture1" src="https://user-images.githubusercontent.com/66424485/218816002-dbcdb89c-0232-4b08-bc73-fb9ded26c1ec.png">

## Step 1: Pre-processing
 The books chosen from KITAB corpus have already been pre-processed. Thus, only resizing is required. We resized the word images to have a width of 64 pixels and height of 32 pixels. Resizing images is a critical pre-processing step, due to deep learning models learning faster on small images.
 ## Step 2: Line and Word Segmentation
 
