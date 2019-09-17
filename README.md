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

# How to work with the notebooks

All the notebooks that you can find in this repository can be run (and have been tested) on Google Colab. Especially since
I select the 2.X TensorFlow version with the magic command `%tensorflow_version 2.x` that is __only__ available in 
Google Colab. If you open in Github the notebooks (in case Github render the notebook properly... Sometime Github have problems doing that, but that is not related to the notebooks. Is a known Github problem) you will find a button
at the top "open in Google Colab". Just click it and the notebook will open in Google Colab. In case Github does not render 
it properly, simply copy the URL of the notebook and open it in Goolge Colab (to know how check this link https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb).

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

# How should I study TF 2.0?

In case you are wondering what is the best strategy to study TensorFlow 2.0 I have a file that will give you some tips
on how to approach the subject. TensorFlow 2.0 is not easy and require some know-how and effort. Don't give up
too early.

Check my suggestions here

https://github.com/michelucci/TensorFlow20-Notes/blob/master/howto_study_TF20.md

# Some references

In the file

https://github.com/michelucci/TensorFlow20-Notes/blob/master/REFERENCES.md

you can find some suggestions for good books.
