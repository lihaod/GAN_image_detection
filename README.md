## Identification of GAN Generated Images

This is a simple implementation of the [Detection of Deep Network Generated Images Using Disparities in Color Components](https://arxiv.org/abs/1808.07276) paper.


### Requirements
- Matlab R2015b+


### Usage
Simply call the function `gan_img_detection_fea` to calculate the features proposed in the paper.
```
Fea = gan_img_detection_fea(Img)
```

Note: To train and test on a dataset, please use the code of [ensembles](http://dde.binghamton.edu/download/ensemble/) (for sample-aware and model-aware detection) / [SVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/) (for model-unaware detection) classifiers.
