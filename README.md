# 🤖 Real-time object detection of sign language letters of the American Sign Language (ASL) alphabet. 
![signl](https://user-images.githubusercontent.com/92129567/236470362-a0224f9d-ac85-4e47-b889-842cc99004f6.jpg)




## 📖 **Introduction**
In our increasingly digital world, we often overlook the challenges faced by individuals lacking the necessary knowledge or abilities to communicate effectively online. This realization has led us to reflect on our encounters with individuals who are deaf or have speech impairments, particularly their difficulties in efficient online communication.

## 🎯 **Objective**
Our goal is to overcome the communication gap and enable deaf individuals to participate more fully in society, especially in online settings. 

## 🚀 **Future Plans**
In the future, we plan to focus on developing the application to detect and display whole words instead of just letters. Currently, we have a mock-up of the project and aim to enhance the UI/UX design. Additionally, we would like to develop a premium version of the application, offering extended features.

## 📊 **Results**
Our application utilizes a model trained on the American Sign Language (ASL) letters. With an accuracy rate of 83%, the model successfully detects all 26 letters of the alphabet. The training data was gathered from open-source websites and contributions from friends and relatives.

## 📐 **Model Overview**
The **YOLOv5** model used in our project is pre-trained on a large image dataset, allowing it to accurately detect sign language letters in real-time video frames. We trained it on 100 images for each letter of the alphabet (26 classes for 26 letters). The labeling process for each image ensured that the model could accurately recognize each sign language letter during a video, even with variations in hand shape and movement.

### Dependencies

* yolov5 requirements.txt
* librarii: pandas, openCV, matplotlib
* pytorch


### RUN

run detect.py

hit "q" key for exiting the app
hit "enter" key for typing a letter on the screen

## Contributors

 Vlada Pulbere    [@peoplecallitinsanity](https://github.com/peoplecallitinsanity)
 
 Anastasia Panfil    [@anastasiaapanfil](https://github.com/anastasiaapanfil)


Resources
* [Yolov5](https://github.com/ultralytics/yolov5)
* [Kaggle Dataset 1](https://www.kaggle.com/datasets/grassknoted/asl-alphabet)
* [Kaggle Dataset 2](https://www.kaggle.com/datasets/kapillondhe/american-sign-language)
