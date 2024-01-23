# AI for Classifying Dogs and Cats Images

The present notebook makes use of deep learning applied to computational vision for a binary classificatio between images of cats and dogs. Such artificial intelligence software was trained on about 700 images of cats and dogs using a sequential neural network built using Keras.

In order to run this model follow these steps:

1. Create a virtual environment in your terminal using the code:

               python3 -m venv classCD-venv

3. Activate the virtual environment you just created using:
       source classCD-venv/bin/activate

5. Install the necessary packages in the activated environment using: 
    cat requirements.txt | sed -e '/^\s*#.*$/d' -e '/^\s*$/d' | xargs -n 1 python -m pip install

The data used on the training may be accessed on:

https://www.kaggle.com/datasets/samuelcortinhas/cats-and-dogs-image-classification
