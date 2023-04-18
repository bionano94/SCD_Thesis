# SCD_Thesis
Repository with my Second Cycle Degree Thesis in Applied Physics
| **Author**  | **Project** |  **Supervisor** | **Co-Supervisor** |
|:------------:|:-----------:|:-----------------:|:-----------:|
| [**N. Biondini**](https://github.com/bionano94) | **SCD_Thesis** <br/> [**Neuroradiomics**](https://github.com/bionano94/Neuroradiomics)| [**Prof. G. Castellani**](https://www.unibo.it/sitoweb/gastone.castellani) |[**Dr. R. Biondi**](https://github.com/RiccardoBiondi) |


# SCD Thesis
Second Cycle Degree final dissertantion in Applied Physics.

The thesis work relies on the use of the code implemented in the repository [Neuroradiomics](https://github.com/bionano94/Neuroradiomics).

## Abstract

Sickle Cell Disease (SCD) is a group of disorders of red blood cells that cause ab- normal hemoglobin and could lead to different symptoms.
Brain MRI scans of patients affected by this condition show peculiar lesions in White Matter, without any apparent neurological evidence, called Silent Cerebral Infarcts (SCI).
To increase the comprehension of this condition is necessary to find and segment the lesions. Up to now this process is performed manually, comporting an high consumption of time and a dependence on the experience of the involved operator.
The European project GenoMed4All aims to provide solutions, control and pre- vention for haematological diseases, including SCD, by applying AI technologies. In this context, a pipeline for identifying and segmenting SCIs was proposed.
This work of thesis aims to develop and implement a pre-processing and post- processing steps to improve the results obtained with the proposed segmentation technique.
The pre-processing step includes a phase of brain automatic extraction and seg- mentation of its main tissues. The post-processing step consists in the classification of the lesions found in the segmentation step, aiming to remove the false positives.
The proposed steps were developed and tested on a data set of MRI scans pro- vided by different medical centers in Italy. The performances of the pre-processing step were tested comparing the obtained results with those of the software FSL, which is a standard in the analysis of MRI scans. The brain mask comparison mea- sured a Dice coefficient of 0.87, the white matter of 0.78, the grey matter of 0.67 and the cerebrospinal fluid of 0.66.
The post-processing step was developed training a set of three classifiers and their results were compared to the manual annotation of the SCIs in the same data set, obtaining a, AUC precision-recall for the best classifier of 0.75.


## Citation

If you have found this work useful in your research, please consider to cite it:

```BibTeX
@mastersthesis{mastersthesis,
  author       = {Nicolas Biondini},
  title        = {Development of pre and post-processing steps to a pipeline aimed to identify silent cerebral infarcts},
  school       = {Alma Mater Studiorum - Università di Bologna, School of Science},
  year         = 2023,
  address      = {bionano94@gmail.com},
  month        = 3,
}
```
