# CNN classifier for dog breed imaging classification

In this project, I build a convolutional neural network (CNN) that can differentiate human from dog and classify the breed of dog from any user-supplied image. If the image is of a human and not a dog, the algorithm will provide an estimate of the dog breed that is most resembling.

The code is written in Python 3 and Keras with Tensorflow backend all presented in Jupyter Notebook. For model training, AWS EC2 gpu instance is used.

If you'd like to use this notebook to do any re-training on the dataset you can grab it at the links below
Dog imaging dataset for training: https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip;
Human imaging dataset for training: https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip;
Bottle-neck feature for dog imaging dataset: https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz
