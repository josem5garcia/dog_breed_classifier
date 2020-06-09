# Dog Breed Classifier
## by José Manuel García 
## Project of the Udacity Data Science Nanodegree
----------------------------------

### Project overview
In this repository, an application to detect human/dog faces, and according to the results, predict the dog's breed more similar to what is shown in the picture has been developed.

The results obtained are very good, achieving an accuracy of up to 85%.

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
