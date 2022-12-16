# open-source-sw-final
This is a **support vector machine(svm)** model in Python that classifies **brain tumors**. 
The classifier is an object of the SVC class which was imported from sklearn.svm library.

## Installing / Getting started
We need *Jupyter Notebook*

scikit-learn, scikit-image are needed. If those packages are missed, then, install them by using the following command.

```
pip install scikit-learn scikit-image
```

## Developing

### The parameters I set
  + C = 2
  + kernel = 'rbf'
  + gamma = 0.02
  + Use the default values for the rest

### The packages I used
  + os
  + sklearn.datasets
  + sklearn.linear_model
  + sklearn.svm
  + sklearn.model_selection
  + sklearn.metrics
  + skimage.io
  + skimage.transform
  + skimage.color
  + numpy
  + matplotlib.pyplot

### label
This model is divided into four labels: glima_tumor, 'meningioma_tumor', 'no_tumor', and 'pituitary_tumor'.

## The licence
![MIT](https://img.shields.io/github/license/kyyuubin/open-source-sw-final)

### Author
If you have any questions, please email cmkb076@gmail.com
