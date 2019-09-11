# Notes on TensorFlow 2.0

![](https://img.shields.io/badge/dependencies-TensorFlow20-blue)
![](https://img.shields.io/badge/dependencies-Jupyter-red)
![](https://img.shields.io/github/forks/michelucci/TF20-Notes?label=Fork)
![](https://img.shields.io/github/last-commit/michelucci/TF20-Notes.svg)
![](https://img.shields.io/github/stars/michelucci/TF20-Notes.svg)
![](https://img.shields.io/github/issues/michelucci/TF20-Notes.svg)
[![license MIT](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

In case you want to contact me, drop me an email at [umberto.michelucci@toelt.ai](mailto:umberto.michelucci@toelt.ai)

This repository contains Various notes and tutorials on TensorFlow 2.0 that I am working on.
All examples are Jupyter notebooks, since in this way is easier to explain concepts and add examples.

# How to work with TensorFlow 2.0

The easiest way to work with TF2.0 is to use Google Colab. In this way you don't have to install anything.
To learn is a great environment.

You can find more information here: [https://github.com/michelucci/TF20-Notes/blob/master/TF_2_0_notes_choosing_the_TF_version.ipynb](https://github.com/michelucci/TF20-Notes/blob/master/TF_2_0_notes_choosing_the_TF_version.ipynb)

but basically in Google Colab you have a magic command that allows you to select the latest 1.x or 2.x versions 
of TensorFlow. Simply use the following code

    %tensorflow_version 2.x 
    import tensorflow as tf
    print(tf.__version__)
  
At the moment I am writing the ```rc0``` TensorFlow version is out. So I get this output

    TensorFlow 2.x selected.
    2.0.0-rc0
