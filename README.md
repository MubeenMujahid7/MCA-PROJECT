# MCA-PROJECT
MCA Project of Driver Drowsiness Detection By
RollNo 60- Mubin Mujahid
and 02 - Aaquibe Shaikh

With this Python project, we will be making a drowsiness detection system. A countless number of people drive on the highway day and night. Taxi drivers, bus drivers, truck drivers and people traveling long-distance suffer from lack of sleep. Due to which it becomes very dangerous to drive when feeling sleepy.

The majority of accidents happen due to the drowsiness of the driver. So, to prevent these accidents we will build a system using Python, OpenCV, and Keras which will alert the driver when he feels sleepy.

Driver Drowsiness Detection Dataset

The dataset used for this model is created by us. To create the dataset, we wrote a script that captures eyes from a camera and stores in our local disk. We separated them into their respective labels ‘Open’ or ‘Closed’. The data was manually cleaned by removing the unwanted images which were not necessary for building the model. The data comprises around 1240 images of people’s eyes under different lighting conditions. After training the model on our dataset, we have attached the final weights and model architecture file “models/cnnCat2.h5”.

Project Prerequisites

The requirement for this Python project is a webcam through which we will capture images. You need to have Python (3.6 version recommended) installed on your system, then using pip, you can install the necessary packages.

    OpenCV – pip install opencv-python (face and eye detection).
    TensorFlow – pip install tensorflow (keras uses TensorFlow as backend).
    Keras – pip install keras (to build our classification model).
    Pygame – pip install pygame (to play alarm sound).

Driver Drowsiness Detection Execution

Let’s execute drive drowsiness detection system and see the working of our ml project. To start the project, you need to open a command prompt, go to the directory where our main file “drowsiness detection.py” exists. Run the script with this command.

python “drowsiness detection.py”
It may take a few seconds to open the webcam and start detection.


Example Screenshot:

![image](https://user-images.githubusercontent.com/91794230/155575365-ee2ea3f7-106a-42e4-9054-5123f7da7023.png)


OutPut ScreenShot:

![Screenshot (7)](https://user-images.githubusercontent.com/91794230/155587385-a7af8a22-b482-4b21-b666-7467f1eeb7c3.png)
![Screenshot (8)](https://user-images.githubusercontent.com/91794230/155587387-c6b08ea8-725c-4358-bfe9-a6114241b50e.png)
![Screenshot (9)](https://user-images.githubusercontent.com/91794230/155587389-5f481536-3e32-4aa4-af12-e9af1f3abfb2.png)

![Screenshot (3)](https://user-images.githubusercontent.com/91794230/155587368-e4b38c85-57c2-49f0-852c-fac7d1de178c.png)
![Screenshot (4)](https://user-images.githubusercontent.com/91794230/155587377-a1cb8ff7-65b1-468d-8668-03fd0f5c8394.png)
![Screenshot (5)](https://user-images.githubusercontent.com/91794230/155587380-4dcaa3a7-1162-493b-9fad-e64b02fa8919.png)
![Screenshot (6)](https://user-images.githubusercontent.com/91794230/155587383-b66e1ca3-6d39-436a-be80-4b7c9ac8374a.png)


Summary

In this Python project, we have built a drowsy driver alert system that you can implement in numerous ways. We used OpenCV to detect faces and eyes using a haar cascade classifier and then we used a CNN model to predict the status.

