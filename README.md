# Traffic-Light-Classifier


## Dataset

Dataset contains 1484 images of green, red and yellow traffic lights. 

![dataset](https://user-images.githubusercontent.com/74123050/134897581-7d65d93d-458a-4bb1-ac03-0b34628e9505.png)

## Pre-Processing

Each image in the dataset is resized and hence standardized for the ML model. 

![pre-process](https://user-images.githubusercontent.com/74123050/134897773-ef9b379a-198e-43c4-a308-0e83ef508d6f.png)

## Feature Extraction

RGB images are converted to HSV for further feature extraction. 

![hsvconversion](https://user-images.githubusercontent.com/74123050/134898520-30315334-32c0-4e81-974c-f5584dc0f894.png)

Features are extracted from the images and a brightness feature histogram set is created.

![brightness-feature](https://user-images.githubusercontent.com/74123050/134898594-5f7a504b-9e88-466f-acd2-081e05670d7a.png)

## Classification Results

Output is in the form of one-hot encoded vector giving the classified result. 

![classification as a one-hot encoded vector](https://user-images.githubusercontent.com/74123050/134898827-23111152-a8fd-4117-9e2d-fc465d10f2ed.png)



