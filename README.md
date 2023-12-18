# GymToolKit-bangkit-MachineLearning
### General
In the project we are working on, we carry out a classification of the gym tools dataset, in which there are 11 categories of gym tools, where it is hoped that the results of the machine learning that we created will be able to identify which class the gym tools fall into.

### What we do
The work of the machine learning team is to create machine learning models and train machine learning with the dataset that has been collected. This includes creating/searching datasets, evaluating datasets, creating machine learning architectures, machine learning training, and evaluating machine learning results.

# 1. Dataset for Different Type of Gym Equipment
We compile images of gym equipment, encompassing dumbbells, barbells, treadmills, and more, utilizing a crawling method for dataset acquisition.


# 2. Preparation Data
Upon gathering the datasets, we initiate data preparation by enhancing the quality of the images. This involves refining the dataset by eliminating images deemed unsuitable for our model. Actions include deletion and cropping of images that can still be effectively utilized.

[Alat-alat gym](https://drive.google.com/drive/folders/1qSnmJ8W2hc9-IuhagP3F69CFzN9MNIEN)
# 3. Preprocessing Data
Applying ImageDataGenerator for scale normalization on each image involves resetting the range of pixel values on each image so that they are uniform and standardized, facilitating a more stable and efficient neural network model training process.

[DATASET ML](https://colab.research.google.com/drive/17nM8hFJaw_Az5K3hBp7ZaTBIWbepgK0y#scrollTo=S6VNbElDVwSr)
# 4. Create Model and Training Data
For model architecture, resize the image into 180x180 and we use transfer learning using VGG16. In general, the Architecture of VGG16

# 5. Evaluate The Model
# 6. Test The Model
