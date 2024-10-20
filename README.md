
# BIRD SPECIES CLASSIFICATION with DEEP LEARNING
**Project Overview**

It is a project that uses transfer learning to predict 525 classes belonging to bird species. Data set of 525 bird species.84635 training images,2625  test images(5 images per species) and 2625 validation images(5 images per species. This is a very high quality dataset where there is only one bird in each image and the bird typically takes up at least 50% of the pixels in the image. As a result even a moderatly complex model will achieve training and test accuracies in the mid 90% range.

To become one with data is significant in such projects. Therefore, visualization techniques are usually applied in the project. A pre-trained model of Keras (InceptionV3) is  used in the project. After reachin nearly %79 accuracy, fine-tuning is applied and the accuracy is improved to **%90**.

Steps followed during the development of the project:

* 1. Become One with Data
* 2. Data Preprocessing
* 3. Create a and fit the Model (Using InceptionV3 pre-trained model)
* 4. Freeze top layers of Base Model
* 5. Fine-tuning and Refitting 
