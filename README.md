# Image-Classifier
Image classification of sports celebrity
This project is an end-to-end data science and machine learning initiative aimed at classifying images of sports personalities. The classification is restricted to the following five individuals:
Maria Sharapova
Serena Williams
Virat Kohli
Roger Federer
Lionel Messi

OpenCV Haar cascades were used to detect faces and eyes in the images.
This helped to focus on the most relevant parts of the images for classification.
Wavelet transform was applied to the detected faces and eyes to extract detailed features.
This step helped to capture both spatial and frequency information from the images
Various models were tested using GridSearchCV to find the best-performing model.
Logistic Regression was found to give the best results with a training score of 84.15%.
The heatmap below shows the results of Logistic Regression on the test data, with an accuracy of 95% on test images.
![image](https://github.com/Lasya-t07/Image-Classifier/assets/139983777/8c176d85-127f-45b9-ba1d-556d8a5e9452)
