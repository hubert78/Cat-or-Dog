# Cat vs Dog Image Classifier
# Overview
This is my journey through building different machine learning models to identify and determine if an image has a cat or dog in it. This project builds upon my traffic sign image classification algorithm. The dataset was taken from Kaggle. 

### The Big Picture
A larger classification of this, which entails many different animals could be helpful for children learning about animals. I imagine building a mobile application where people could upload an image and the classifier can tell them what animal it is and give them some fun facts about the animal.  You can get the dataset on [kaggle]( https://www.kaggle.com/datasets/ma7555/cat-breeds-dataset)

# Solving the problem
In this project, I first built a CNN model from scratch. This model rather performed poorly with an accuracy score of 66.33%. In order to improve the performance of the model, I learned more about transfer learning and used a CNN model pre-trained on mobilenet. From an initial 8005 images, I was able to use 1600 images, and minial fine-tuning to get a 98.00% accuracy.  

### Some challenges 
Because of the large number of images used in the model training, building this project on my local computer became a struggle as I continually ran out of memory space. Google Co-lab became a lifesaver in this regard. 
