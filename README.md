# Doodling with Deep Learning!

## Introduction:
This is the Repo of our Quick Draw Kaggle Competition Project.We present our data preprocessing, models fittings, and a fun application of the Google Quick, Draw! dataset. This project  was built by Akhilesh Reddy, Vincent Kuo, Kirti Pande, Tiffany Sung, and Helena Shi. To see the full walk-through, find our blog post at: 

https://towardsdatascience.com/doodling-with-deep-learning-1b0e11b858aa 

Walk with us through this journey to see how we have tackled the challenge in successfully classifying what is “arguably the world’s cutest research dataset!”

### Structure of the repository:
**Shuffle_CSV_and_ResNet** folder:  includes data pre-processing/shuffle csv code and the SE-ResNet model we tried.<br>

**Mobile_net** folder:  includes the Mobile Net model code and training.<br>

**OtherModels** folder: we tried some skicit learn classifiers for instance Random Forest, k-NN and MLP Classifier.<br>

**QuickDraw** folder: One can replicate the demo application we created by running the QuickDrawApp.py code. Also, download the CNN model from the following link: https://drive.google.com/open?id=1PAFXI5HrY7HguZy0I8yDaUQUebTQYus0 and save in the same location as the folder.<br>

### Result: 
We achieved **92.11% precision (MAP@3)** on all the 350 classes and ranked **268 among 1316** teams that participated in the competition.

### Demo application:
In addition to the competition, we have also created one demo application that captures the input on the screen and the identifies the class of the sketch drawn.

The model is trained for 15 classes:
<br>Donut 🍩 <br>
Eye 👁<br>
Tent ⛺<br>
Bicycle 🚲<br>
Flower 🌸<br>
Mermaid 🧜‍<br>
Snake 🐍<br>
Camera 📷<br>
Pineapple 🍍<br>
Rainbow 🌈<br>
Lipstick 💄<br>
Face 😊<br>
Shoe 👠 <br>
Cup ☕<br>
Hockey stick 🏑 <br>

A preview of the application is as follows: 

![](quickdrawgif.gif)

