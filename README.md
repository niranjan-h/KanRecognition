## INSTALLATION

You need to have Python 3.x installed

`pip install -r requirements.txt`

The python libraries used are

```
scikit image
numpy
OpenCV
Django
Tensorflow
Joblib
Scipy
Matplotlib
Keras
Pillow
```
We also made use of a LRN2D layer which was removed from the keras source. It needs to be manually included.
Paste the contents of `keras_addition.txt` in `/usr/local/lib/python3.5/dist-packages/keras/layers/normalization.py`. The file path may vary depending on your python version.
  
## KANNADA HANDWRITING RECOGNIZER

The project aims at Optical Character Recognition of handwritten documents in Kannada, a South Indian Language.

Kannada is being chosen as not much research was done prior with a whole document but only individual characters. The complexity further increases due to a very large number of classes due to letters, numbers, kagunitas and ottaksharas.

This project has also performed a comparative analysis of two supervised (k-Nearest neighbors and Support Vector Machines) and two unsupervised models (Inception V3 and Convoluted Neural Networks).

A web app provides the user interface. A handwritten document is given as input and the corresponding text as digital text is presented as an output in the web apps display
