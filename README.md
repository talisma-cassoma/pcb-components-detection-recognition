# pcb component detection/recognition

This code shows the train and test of a YOLOV5 convolutional neural network for recognition of electronics components

download those files and put in a folder named Real_PCB and upload to your google drive: <a href="https://drive.google.com/drive/folders/1odzD298ImaHI3NKozQNGIgKbflzgSWIn?usp=sharing">here</a> it's the dataset originaly created by Animeshkumar Nayak(available on Kaggle) with some improvements that i made in roboflow

see the model working on video: <a href="https://www.linkedin.com/embed/feed/update/urn:li:ugcPost:6893204326802948096">here</a>

## 🔥 SETUP

This is how should look the projet struture :  
```
MyDrive/
└── Real_PCB/
    ├── Dataset/
    │   └── pcb_data/
    │       ├── data.yaml     
    │       ├── test/
    │       ├── valid/
    │       └── train/
    │   
    └── yolov5/
```
### THE TRAIN 

I chose to train on colab cause i havent a powerfull GPU as colab invidia does and its free :)

The train process is all commented 

### THE TEST

To test the the models you only need de results. its also commented 

yolov5 allows you to test the model using videos images even your web camera if you setup it your machine    
