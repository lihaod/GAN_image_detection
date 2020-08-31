## Identification of GAN Generated Images

This is an implementation of the paper [Identification of deep network generated images using disparities in color components](https://doi.org/10.1016/j.sigpro.2020.107616).


### Requirements
- Matlab R2015b+


### Usage
Simply call the function `gan_img_detection_fea` to calculate the features proposed in the paper.
```
Fea = gan_img_detection_fea(Img)
```

Note: To train and test on a dataset, please use the code of [ensembles](http://dde.binghamton.edu/download/ensemble/) (for sample-aware and model-aware detection) / [SVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/) (for model-unaware detection) classifiers.

## Citation
If you use our code please cite:
```
@article{li2020identification,
  title={Identification of Deep Network Generated Images Using Disparities in Color Components},
  author={Li, Haodong and Li, Bin and Tan, Shunquan and Huang, Jiwu},
  journal={Signal Processing},
  volume = {174},
  pages={107616},
  year={2020},
  issn = {0165-1684},
  doi = {https://doi.org/10.1016/j.sigpro.2020.107616},
}
```
