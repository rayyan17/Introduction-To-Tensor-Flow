# Introduction To Tensorflow

I have made 3 notebooks on Introduction to Tensorflow:


**1. Tensorflow_Hello_World.ipynb**

I have picked a parabolic log function and tried to train a shallow deep network on a few samples to generate the same function. The goal of this notebook is to give you an idea that how to build a simple network in Tensorflow.



**2. Tensorflow_Intro_NLP.ipynb**

I have picked a dataset from kaggle related to fake-news and tired to show the steps you need to go through for solving an NLP based problem


**3. Tensorflow_Computer_Vision.ipynb**

I have taken the motivation to build this notebook from "TensorFlow in Practice Specialization - Coursera". It has covered important concepts of CV like convolution and pooling. It has also shown how to visualize images in the layers.


## Presentation 

You can find link to the presentation related to this at:
https://www.slideshare.net/rayyankhalid35/introduction-to-tensorflow-213058272


## Instructions for setup

1. Download and install python from python.org
    Version: minimum python version required 3.5
    URL: https://www.python.org/downloads/


2. Get the notebooks codebase

    ```bash
    git clone https://github.com/rayyan17/Introduction-To-Tensor-Flow.git <path-to-project-dir>
    ```

3. Create and activate virtual environment.

    ```bash
    cd <path-to-project-dir>
    python3 -m venv .python3_venv       # creates the virtual env
    source .python3_venv/bin/activate   # activates the virtual env
    ```
    After activating the virtual env. Any installed python packages would be installed here without affecting the main python binaries.
    To de-activate the virtual env, just type "deactivate"

4. Install Required Packages
    
    ```bash
    pip install -r requirements.txt
    ```

## Run your Notebook
Run you Notebook using the following command:

    ```bash
    jupyter notebook NOTEBOOK_NAME
    ```
