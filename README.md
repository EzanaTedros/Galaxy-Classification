A CNN model that classifies images of galaxies.

Firstly Github doesn't allow files bigger than 2.4GB to be uploaded and the dataset is 2.7GB. Here is a link to download the dataset
https://zenodo.org/records/10845026/files/Galaxy10_DECals.h5
Make sure to save the dataset in the same location as the notebook
Training the model takes a long time so to save time you can load the model by using the code below
model = tf.keras.models.load_model('Galaxy Neural Network ver1 .h5', compile = False)

The confusion matrix for obvious reason takes a long time aswell so is optional to run.

The errors are just kernel interupts and one line where I forgot I deleted a dataset. You can completly ignore them.
