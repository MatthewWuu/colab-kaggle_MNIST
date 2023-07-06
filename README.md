# colab-kaggle_MNIST

### Config:

Colab: python3 gpu Tesla T4

Kaggle: python3 gpu Tesla T4 * 2

------

### To see

Two pieces of code train the MNIST dataset with a neural network model on Kaggle and Colab, respectively. The 'Run_on_Kaggle' code is very similar to the 'Run_on_Colab' code, only slightly different in the data set loading part. Kaggle TensorFlow library on a slightly different way of import, so using ` tf. Keras. Datasets. Mnist. Load_data ` () to load the mnist data set.

Try to run three times with the epoch set to 5 each time while controlling each variable. At the end of each session, the maximum GPU memory usage is checked by self-defined functions, and then the training time of each session is compared.

