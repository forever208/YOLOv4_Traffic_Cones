![YOLOv4](https://img.shields.io/badge/YOLOv4-API-brightgreen) ![Colab](https://img.shields.io/badge/Colab-training-orange)

## Introduction
- This is project call YOLOv4 official API to train a custom model which is used for detecting taffic cones.
- This project refers to [AIGuy's repo](https://github.com/theAIGuysCode/YOLOv4-Cloud-Tutorial) and his detailed [video](https://www.youtube.com/watch?v=mmj3nxGT2YQ)
- Details of the traffic cone object detection model I trained:
     - 270 training images, 40 validation images
     - 1000 epoches
     - 53% map
     - 46 fps (based on Colab GPU)
     

## How to use the trained model

1. Used the resources I shared in [Google Drive YOLOv4](https://drive.google.com/drive/folders/14fgDkg3bVDhNwwX3zV-Tl0itMRhzOZTj)
2. Download the YOLOv4_KTHFS folder and creat a same folder in your GoogleDrive
3. upload your images or videos to this folder

<img src="img/your GoogleDrive folder .png" width="800" />

4. open __YOLOv4_KTHFS.ipynb__ in colab and run all codes, connect your GoogleDrive to Colab
5. run the command to detect your images or videos, the result will be automatically saved to your GoogleDrive folder

<img src="img/detect your images or videos.png" width="800" />




## How to train and use your own model

    $ git clone https://github.com/forever208/YOLOv4_Traffic_Cones.git

    
(to be done)

    
