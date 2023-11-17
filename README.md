# Fauna Classification Project

#### Mason Walter


## Project Overview
The goal of this project is to build a predictive machine learning model utilizing a convolutional neural network to classify images of animals. My intention is to show my understanding of the modeling process, final model selection, and evaluation.

## Business & Data Understanding
I chose [this dataset](https://www.kaggle.com/datasets/alessiocorrado99/animals10), provided on kaggle. The set contains 10,000 images of 10 animals (1000 of each) and classifies their species.  Each picture is high definition and will allow for a lot of features for the model to learn.

I am assuming the role of a data scientist tasked with finding an area to profit with high-margins then creating a product that can generate said profit.

## Modeling

I sorted the data before the modeling process, translating species labels from italian to english.

For the MVP, I created a CNN model. This model achieved a 96.5% accuracy score on testing data after the 26th Epoch.

In pre-processing, I first loaded the images into data-loaders.  Then, I augmented the images randomly based on flip, rotation, and contrast.  After that, I configured each layer of the CNN. The final result after running the model was a new dataframe of just the predictions and the model's predictability of each image.

There is still room for improvement in the model and I think I'm first going to try editing the preprocessing numbers as well as adding a zoom augmentation filter. Below is the classification report for the model.


![Report](images/classification_rep_fauna.jpg)


## Evaluation & Conclusion
My recommendation is to use the convolutional neural network.

The model performs incredibly well and I don't see too many improvements that I could make.

In the future I will try to use some other packages, potentially something with Computer Vision and pytorch.

### Final Notebook
[Notebook](https://github.com/Wingaero/Fauna_Classification_Project/blob/main/Notebook.ipynb)

## Presentation:
[Presentation](https://github.com/Wingaero/Fauna_Classification_Project/blob/main/fauna_classification_slides.pdf)

## Contributers
Mason Walter <a href = "https://github.com/Wingaero"><img src='https://cdn.pixabay.com/photo/2022/01/30/13/33/github-6980894_1280.png' width = '25' height='25'></a><a href="www.linkedin.com/in/mason-c-walter/"><img src='https://upload.wikimedia.org/wikipedia/commons/8/81/LinkedIn_icon.svg' width = '25' height='25'></a>  