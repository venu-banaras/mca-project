This is project for degree of MCA of Mayank Singh. It is Deep learning based building and vehicles identification system. 


MINI-PROJECT SYNOPSIS
ON
DEEP LEARNING BASED MILITARY BUILDINGS AND VEHICLES IDENTIFICATION SYSTEM

FOR PARTIAL FULFILMENT OF AWARD OF
MASTER’S OF COMPUTER APPLICATION
SESSION – 2021-2023

![image](https://user-images.githubusercontent.com/63134916/200489610-d39494e1-c2a8-4394-870f-1f3b8cf84e72.png)

SUBMITTED BY:
GROUP NO. – 9
MAYANK SINGH (21730)
MCA – 2nd YEAR




Department of Computer Science and Engineering
KAMLA NEHRU INSTITUTE OF TECHNOLOGY, SULTANPUR
Affiliated to Dr. APJ Abdul Kalam Technical University, Lucknow
 

TITLE

Deep Learning and Computer Vision based military buildings and vehicles identification system.

OBJECTIVES

The project aims to provide an intelligent eye-in-the-sky to fighter jets or ground troops operating in a hostile territory and provide them a means to target specific buildings or vehicles, either according to previously known data or live data. This model is aimed for use in medium altitude armed (or unarmed surveillance) drones. If we provide historical satellite imagery of a plot of enemy territory and provide a building from the several buildings, that most probably exist in that area, as input, the model can identify the building when another set of images, of that same plot, are provided to it. This model can also detect and track several classes of military vehicles like trucks, using the same detection method we apply for buildings.

TECHNICAL DETAILS

HARDWARE SPECIFICATION: -

1.	PROCESSOR   :   AMD Ryzen 7 (or similar) 
2.	RAM         :   Minimum 8 GB
3.	HARD DISK   :   512 GB SSD

SOFTWARE SPECIFICATION: -

   1. OPERATING SYSTEM        :  Microsoft Windows 10
   2. DEVELOPMENT ENVIRONMENT :  Python 3.7.10
   3. IDE                     :  Microsoft VSCode, Jupyter Notebooks
   4. LIBRARIES               :  TensorFlow v2.9.2, OpenCV v4.6.0, NumPy     
                                 v1.23.3, Pandas v1.4.4, Matplotlib v3.5.2
   5. DATABASE                :  File system
   6. SERVER                  :  Google Collab (for extra processing power     
                                  , if needed)
PROJECT SURVEY: -

After recent hype in Fifth-Generation aerial vehicles development and usage, a need for an AI-powered drone was also felt, which could be used for surveillance or attack purposes. However, the concept of an AI-powered wingman took much of the spotlight. In this concept, we have a long endurance and medium to high altitude drone which will fly alongside a manned fighter jet and will act as its wingman (teammate) and it will be able to identify and target buildings or vehicles and provide necessary actions on the same. 

With this concept in mind, I aim to build and train a model that would be able to identify military style buildings and vehicles and show us it’s results in form of rectangles on the identified objects. For this, I will use satellite images of a certain plot of land over a certain period of time and provide the model with a random building for it to learn to identify. Such images will be taken from several locations (as much is freely available) and a sufficient sized dataset will be created. Then this dataset will be used as the training set for the model to learn to identify buildings. To identify vehicles, I will create a small class of vehicles, most probably 3 to 4 classes, and train the same model on them. 

In this kind of identification, I will not take into consideration the type of terrain or weather, as it will make the model more complex and would require more processing power. To be able to point out buildings or vehicles, we will use image segmentation, which can segment or point out such objects using CNNs. Since this type of model is a probabilistic model, it will also show us the probability percentage of how sure the model is, that, the object 


![image](https://user-images.githubusercontent.com/63134916/200489660-cd3f4cf2-1c2e-441e-aefb-960ee4c03c4a.png)


show us the probability percentage of how sure the model is, that, the object 

it identified is a building or a vehicle. Hence, to increase the probability percentage, we will have to create a sufficiently large sized dataset.

Such type of object identification and tracking will require Deep Convolutional Neural Networks (CNNs) for model learning. We will use TensorFlow v2.9.2 to build such a network. The image processing part will be handled by OpenCV v4.6.0. In image processing, we will clean noise from the images, smooth the images and so on. To create the dataset, I will use Google Earth and NASA’s Earth Explorer website which provides high quality satellite images for free. To provide easy marking of the objects on the images, we will also look into a library called as YOLOv3, You Only Look Once version 3, which makes it easy to segment objects out of huge dataset of images.


![image](https://user-images.githubusercontent.com/63134916/200489705-e704a464-633a-4352-9dc7-cfd598134173.png)


REFERENCES: -

1. https://www.analyticsinsight.net/the-role-of-ai-in-the-defence-sector/ 
2. www.tensorflow.org
3. www.opencv.org 
4. https://link.medium.com/Sd90cLTzBtb 
5. https://link.medium.com/CcD43JXzBtb 
6. https://www.kaggle.com/competitions/dstl-satellite-imagery-feature-detection/data 
7. https://towardsai.net/p/computer-vision/50-object-detection-datasets-from-different-industry-domains
