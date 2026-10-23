A CNN model that classifies images of galaxies into 10 groups and gives the probability of each group being the galaxy class.

1) Firstly Github doesn't allow files bigger than 2.4GB to be uploaded and the dataset is 2.7GB. Here is a link to download the dataset
https://zenodo.org/records/10845026/files/Galaxy10_DECals.h5

2) Make sure to save the dataset in the same location as the notebook
   
3) Training the model takes a long time so to save time you can load the model by using 'model = tf.keras.models.load_model('Galaxy Neural Network ver1 .h5', compile = False)'

4) Use the function model_predict_image() if you want to use the model to predict but it has to be converted into a numpy array before entering the function. 



