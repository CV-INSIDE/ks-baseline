# Assessing deep learning methods for the identification of kidney stones in endoscopic images

This repository has the code to implement the methods described in the conference article: [*Assessing deep learning methods for the identification of kidney stones in endoscopic images*](https://ieeexplore.ieee.org/abstract/document/9630211), developed as part of the project [*"RECONDITE: Deep learning and image analysis methods for improving the endoscopic identification of kidney stones composition"*](https://www.researchgate.net/project/RECONDITE-Deep-learning-and-image-analysis-methods-for-improving-the-endoscopic-identification-of-kidney-stones-composition) at [Tecnologico de Monterrey](https://tec.mx/en) and [Université de Lorraine](http://www.univ-lorraine.fr). 



## Abstract
Knowing the type (i.e., the biochemical composition) of kidney stones is crucial to prevent relapses with an appropriate treatment. During ureteroscopies, kidney stones are fragmented, extracted from the urinary tract, and their composition is determined using a morpho-constitutional analysis. This procedure is time-consuming (the morpho-constitutional analysis results are only available after several weeks) and tedious (the fragment extraction lasts up to an hour). Identifying the kidney stone type only with the in-vivo endoscopic images would allow for the dusting of the fragments and eneable early treatments, while the morpho-constitutional analysis is ready. Only few contributions dealing with the in vivo identification of kidney stones have been published. This paper discusses and compares five classification methods including deep convolutional neural networks (DCNN)-based approaches and traditional (non DCNN-based) ones. Even if the best method is a DCCN approach with a precision and recall of 98% and 97% over four classes, this contribution shows that an XGBoost classifier exploiting well-chosen feature vectors can closely approach the performances of DCNN classifiers for a medical application with a limited number of annotated data.

[[Paper]](https://ieeexplore.ieee.org/abstract/document/9630211) [[ArXiv]](https://arxiv.org/pdf/2103.01146)




---

## Contents

 
 
 
## Summary 

|      Dataset     | Patch |    Model    | View | Epocs | MEAN |    Acuracy    |   Precision   |     Recall    |    F1-Score   |      ROC      | Rounds |
|:----------------:|:-----:|:-----------:|:----:|:-----:|:----:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:------:|
| Jonathan-El-Beze |  256  |   AlexNet   |  MIX |   30  |  M+S | 0.8140+0.0378 | 0.8300+0.0184 | 0.8136+0.0359 | 0.8093+0.0384 | 0.8880+0.0217 |    5   |
| Jonathan-El-Beze |  256  |    VGG16    |  MIX |   30  |  M+S | 0.8260+0.0134 | 0.8543+0.0022 | 0.8256+0.0170 | 0.8223+0.0170 | 0.8943+0.0116 |    5   |
| Jonathan-El-Beze |  256  | InceptionV3 |  MIX |   30  |  M+S | 0.8500+0.0187 | 0.8666+0.0138 | 0.8513+0.0157 | 0.8503+0.0160 | 0.9096+0.0095 |    5   |
| Jonathan-El-Beze |  256  |   ResNet50  |  MIX |   30  |  M+S | 0.8020+0.0268 | 0.8303+0.0082 | 0.8033+0.0261 | 0.7996+0.0253 | 0.8806+0.0164 |    5   |
| Jonathan-El-Beze |  256  |   DenseNet  |  MIX |   30  |  M+S | 0.8940+0.0089 | 0.9066+0.0046 | 0.8960+0.0082 | 0.8950+0.0091 | 0.9383+0.0046 |    5   |
| Jonathan-El-Beze |  256  |   AlexNet   |  SEC |   30  |  M+S | 0.8280+0.0622 | 0.8493+0.0420 | 0.8293+0.0635 | 0.8193+0.0770 | 0.8986+0.0384 |    5   |
| Jonathan-El-Beze |  256  |    VGG16    |  SEC |   30  |  M+S | 0.7920+0.0217 | 0.8276+0.0201 | 0.7890+0.0217 | 0.7683+0.0348 | 0.8726+0.0137 |    5   |
| Jonathan-El-Beze |  256  | InceptionV3 |  SEC |   30  |  M+S | 0.8120+0.0268 | 0.8823+0.0052 | 0.8126+0.0171 | 0.8140+0.0276 | 0.8883+0.0149 |    5   |
| Jonathan-El-Beze |  256  |   ResNet50  |  SEC |   30  |  M+S | 0.8880+0.0602 | 0.8990+0.0524 | 0.8830+0.0585 | 0.8820+0.0620 | 0.9306+0.0361 |    5   |
| Jonathan-El-Beze |  256  |   DenseNet  |  SEC |   30  |  M+S | 0.9400+0.0000 | 0.9466+0.0000 | 0.9350+0.0000 | 0.9350+0.0000 | 0.9610+0.0022 |    5   |
| Jonathan-El-Beze |  256  |   AlexNet   |  SUR |   30  |  M+S | 0.7760+0.0622 | 0.7910+0.0420 | 0.7760+0.0635 | 0.7723+0.0770 | 0.8653+0.0770 |    5   |
| Jonathan-El-Beze |  256  |    VGG16    |  SUR |   30  |  M+S | 0.8260+0.0217 | 0.8593+0.0201 | 0.8276+0.0217 | 0.8280+0.0348 | 0.8976+0.0137 |    5   |
| Jonathan-El-Beze |  256  | InceptionV3 |  SUR |   30  |  M+S | 0.8220+0.0268 | 0.8403+0.0052 | 0.8263+0.0171 | 0.8193+0.0276 | 0.8946+0.0149 |    5   |
| Jonathan-El-Beze |  256  |   ResNet50  |  SUR |   30  |  M+S | 0.8120+0.0602 | 0.8380+0.0524 | 0.8113+0.0585 | 0.8116+0.0620 | 0.8863+0.0361 |    5   |
| Jonathan-El-Beze |  256  |   DenseNet  |  SUR |   30  |  M+S | 0.8560+0.0000 | 0.8620+0.0000 | 0.8560+0.0000 | 0.8540+0.0000 | 0.9133+0.0022 |    5   |
 
## Organization

No additional content directories are declared. 


## Contributors

Code for algorithms, applications and tools contributed by:

[Francisco Lopez](https://scholar.google.es/citations?user=IlG06bYAAAAJ&hl=es), Andres Varela, Oscar Hinojosa, Mauricio Mendez, Dinh-Hoan Trinh, Jonathan ElBeze, Jacques Hubert, Vincent Estrade, Miguel Gonzalez, [Gilberto Ochoa](https://scholar.google.com/citations?user=DDtiliwAAAAJ&hl=en&authuser=1), [Christian Daul](https://scholar.google.com/citations?user=XPH6u74AAAAJ&hl=en&authuser=1)

Please email us your comments, criticism, and questions at [`gilberto.ochoa@tec.mx`](mailto:gilberto.ochoa@tec.mx?subject=[GitHub]%20ks-baseline%20repository)


## Reference

If you use functions from this script in your work, please use the BibTex entry below for citation.

[[Paper]](https://ieeexplore.ieee.org/abstract/document/9630211)

```
@inproceedings{lopez2021assessing,
  title={Assessing deep learning methods for the identification of kidney stones in endoscopic images},
  author={Lopez, Francisco and Varelo, Andres and Hinojosa, Oscar and Mendez, Mauricio and Trinh, Dinh-Hoan and ElBeze, Yonathan and Hubert, Jacques and Estrade, Vincent and Gonzalez, Miguel and Ochoa, Gilberto and others},
  booktitle={2021 43rd Annual International Conference of the IEEE Engineering in Medicine \& Biology Society (EMBC)},
  pages={2778--2781},
  year={2021},
  organization={IEEE}
}
```
