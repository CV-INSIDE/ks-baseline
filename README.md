# Assessing deep learning methods for the identification of kidney stones in endoscopic images

This repository has the code to implement the methods described in the conference article: [*Assessing deep learning methods for the identification of kidney stones in endoscopic images*](https://ieeexplore.ieee.org/abstract/document/9630211), developed as part of the project [*"RECONDITE: Deep learning and image analysis methods for improving the endoscopic identification of kidney stones composition"*](https://www.researchgate.net/project/RECONDITE-Deep-learning-and-image-analysis-methods-for-improving-the-endoscopic-identification-of-kidney-stones-composition) at [Tecnologico de Monterrey](https://tec.mx/en) and [Université de Lorraine](http://www.univ-lorraine.fr). 



## Abstract
Knowing the type (i.e., the biochemical composition) of kidney stones is crucial to prevent relapses with an appropriate treatment. During ureteroscopies, kidney stones are fragmented, extracted from the urinary tract, and their composition is determined using a morpho-constitutional analysis. This procedure is time-consuming (the morpho-constitutional analysis results are only available after several weeks) and tedious (the fragment extraction lasts up to an hour). Identifying the kidney stone type only with the in-vivo endoscopic images would allow for the dusting of the fragments and eneable early treatments, while the morpho-constitutional analysis is ready. Only few contributions dealing with the in vivo identification of kidney stones have been published. This paper discusses and compares five classification methods including deep convolutional neural networks (DCNN)-based approaches and traditional (non DCNN-based) ones. Even if the best method is a DCCN approach with a precision and recall of 98% and 97% over four classes, this contribution shows that an XGBoost classifier exploiting well-chosen feature vectors can closely approach the performances of DCNN classifiers for a medical application with a limited number of annotated data.

[[Paper]](https://ieeexplore.ieee.org/abstract/document/9630211) [[ArXiv]](https://arxiv.org/pdf/2103.01146)




---

## Contents

 
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
