# CS470_K_SAM

Face Aging Model with AI_HUB's Korean face datasets.
All information about K-SAM is described below.

![Jang1](https://user-images.githubusercontent.com/71695489/205508296-aa60af72-7182-45d8-af4d-a8ef001bb83e.jpg)

<br/>

Here below link for the poster shows the detailed description. <br/>
=> [Style-based Age Manipulation Poster](https://docs.google.com/drawings/d/1nRQFLXTqVGUcLOyQGcd1hXAuTmZ-aQles3_a-YJdyZc/edit)

<br/>

Base paper for this Face Aging model is written and linked below. <br/>
 => [Only a Matter of Style: Age Transformation Using a Style-Based Regression Model](https://arxiv.org/pdf/2102.02754.pdf)
 
<br/>

The model configure and architecture is following the official github of the paper. <br/>
**Read below for our addition first, and follows official guide below.** <br/>
 => [official link of SAM - "yuval-alaluf / SAM"](https://github.com/yuval-alaluf/SAM)
 
<br/>

You can download the pre-trained model used from here. <br/>
 => [Get pre-trained model here](https://github.com/yuval-alaluf/SAM#pretrained-models)
 
<br/>

You also can download the pre-trained K-SAM model used for CS470 final project here. <br/>
 => [Get pre-trained K-SAM model here](https://drive.google.com/file/d/1v_ABip_aG9ZD3IMxYH4qSBQI0PfuKGQw/view?usp=share_link)

<br/>

Used train, test(=validation), result images with link listed below.<br/>
 => [train datasets](https://drive.google.com/file/d/1OtCT7v3OpiC-92A-Bdb2_HEbOKn5nTiP/view?usp=share_link)<br/>
 => [test(=validation) datasets](https://drive.google.com/file/d/1eco4WBUu1VZ1a5_-gHLwIASMIrbw3NlE/view?usp=share_link)<br/>
 => [**result face aging images**](https://drive.google.com/file/d/1G_7Wz8AgOJDBCsiuOwByu4xyAuwdrmK5/view?usp=share_link)<br/>

## Read carefully below to fully understand what we added.

### 1. Image Crop
##### Image Crop for Training

- You can explicitly crop your personal "Face Train Images" using **"/images/cropper.py"**
- You should **modify the code to fit your own datasets**.

##### Image Crop for Inference

- In **/datasets/inference_dataset.py**, you can annotate or not to choose whether activate cropping or not for the inference images.


### 2. Korean Image Dataset

![image](https://user-images.githubusercontent.com/71695489/205508518-011a5f5d-3d63-4fb6-8bde-1dea8a0106cd.png)
