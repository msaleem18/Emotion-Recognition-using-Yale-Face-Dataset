## Emotion-Recognition-using-Yale-Face-Dataset

#### Project Description
Emotion recognition from facial expressions is the subfield of social signal processing which is applied in a variety of areas, specifically for human and computer interaction. Recognizing basic emotions such as angry, happy, disgust, fear, sad, and surprise is still a challenging problem in computer vision. During our literature review we found that papers that focus on Emotion Recognition based on facial expression have mostly employed Deep Learning methods (CNNs). A majority of papers trained, tested and used the model for the same image dataset that they initially started working with. However, our team was interested in understanding if the trained model can be used to predict emotions in a different image dataset as well; especially one that’s a bit more diverse in gender and complexion. Theoretically the basic emotions should remain consistent across datasets and hence a model trained on one imageset should be able to transfer learnings to a new dataset.    

In this paper our team will be using Yale Face Dataset (base dataset) to help classify basic human emotions. The dataset contains 11 mutually exclusive features, out of which 3 are related to human emotions (happy, sad, and surprise). We will be employing the VGG Deep Face Recognition model on this base dataset and test the model on 54 randomly selected images (happy, sad, surprised) from CK+ Face Dataset. The aim is to see if learnings can be transferred from a basic dataset to a more diverse one.


#### Dataset Information
In this paper we will be using the Yale Face Dataset as the base dataset; available at: https://www.kaggle.com/olgabelitskaya/yale-face-database#Readme.txt

The dataset contains 11 mutually exclusive features for 15 subjects out of which only 3 are related to human emotions, happy, sad and surprised (total of 45 images). From the 15 subjects, most are male except 1 and most have a fair complexion except for 3.


Fig 1 - All subjects with happy emotion in Yale Dataset

The second dataset that we’ll be using to test the model is CK+ Face Dataset, available at: https://www.kaggle.com/shawon10/ckplus

Compared to the Yale Dataset, our CK+ test sample has ~55% female and ~27% non-fair complexion subjects.


Fig 2 - All subjects with surprised emotion in our test CK+ Dataset
