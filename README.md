# Dog Breed Classifier
## by José Manuel García 
## Project of the Udacity Data Science Nanodegree
----------------------------------

### Project overview
In this repository, an application to detect human/dog faces, and according to the results, predict the dog's breed more similar to what is shown in the picture has been developed.

### Summary of the results
We started creating a model from the scratch, obtaining a poor result due to the small dataset used to train the model. After that, we used Transfer Learning to create the models, improving the results significantly (Up to 85%). Finally, everything previously developed was ensembled in an algorithm that detects if there is a human face in the photograph or a dog, and provides the most likely dog breed to the thing in the provided photograph.

### Files in the repository
- extract_bottleneck_features.py: to extract the bottleneck features of the models.
- main.ipynb: Jupyter Notebook that includes the app

### Libraries
- sklearn
- keras
- numpy
- glob
- random
- cv2
- matplotlib
- tqdm
- PIL


### Instructions to use the code
The user has to create a folder called bottleneck_features and add DogResnet50Data.npz and DogVGG16Data.npz to run the model, since due to the rules of GitHub, they are too large to be included in the repository.

All that the user has to do is to run the main.ipynb Jupyter Notebook.

### Conclusions after developing the model
During the project, the steps followed to develop a CNN model to classify dog breeds have been outlined. We started creating a model from the scratch, obtaining a poor result due to the small dataset used to train the model. After that, we used Transfer Learning to create the models, improving the results significantly (Up to 85%). Finally, everything previously developed was ensembled in an algorithm that detects if there is a human face in the photograph or a dog, and provides the most likely dog breed to the thing in the provided photograph.

In order to develop the project, Keras was used, although other alternatives (such as PyTorch) could be used too.

The most interesting point of the project has been to use Transfer Learning, since it provides the user with a very powerful tool with which you can make use of already trained models with large datasets to your own problems, what helps you increase the accuracy.

Another interesting, at the same time that challenging, was the hyperparameter tuning and the model's structure definition, since this determines the performance of the model. However, as it can be seen with the results achieved, it was successfully solved.

Nothing in this life is perfect, so some improvements are proposed to the model:

1- Introduce more images in the dataset in order to improve the performance of the model

2- Introduced modified images from the current dataset in order to improve face detection in adverse situations

3- Ensemble of models

My own reflection about this project is that after developing it one is in a good position and with enough knowledge to face more difficult problems in the CNN field, since many important aspects have been touched (e.g. developing a model from scratch, Transfer Learning...), so facing a problem like this is highly recommendable for those interested in the field.

### References
- [Keras documentation](https://keras.io/guides/)
- [CNN](https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53)
