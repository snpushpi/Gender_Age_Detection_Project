# Gender_Age_Detection_Project
In this Python Project, we will use Deep Learning to accurately identify the gender and age of a person from a single image of a face. We will use the models trained by Tal Hassner and Gil Levi. The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100) (8 nodes in the final softmax layer). It is very difficult to accurately guess an exact age from a single image because of factors like makeup, lighting, obstructions, and facial expressions. And so, we make this a classification problem instead of making it one of regression.
In order to run it on any image, we have to write this code on command prompt going to the location of this folder-
```
python gad.py --image <image_path>
```
For example, for an image in the folder and in my location, the code will be -
```
C:\Users\pushp\Desktop\Gender_Age_Detection_Project\gad>python gad.py --image girl1.jpg
```
The output shown on the command prompt is - 
```
Gender: Female
Age: 25-32 years
```
And also a screen with the image of the girl and the detection of her face with a box  will pop up with too.
