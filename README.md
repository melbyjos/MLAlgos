# MLAlgos
From-scratch implementations of various ML algorithms.

This repository contains multiple Jupyter Notebooks I have written in order to explore the
inner-workings of various ML and statistical algorithms. This work has been spread over the last 5
years while I was completing my PhD in mathematics at MSU. While my research expertise generally
lies outside of machine learning and rather in applications of topology and geometry to data
science, I have found the process of implementing these algorithms from scratch to be a valuable
exercise for my transition from academia into industry.

The following notebooks are a bit old and are my first attempts at implementing some ML algorithms
(and I plan to update and improve them in the near future):

- ANN_2_Layer
- Regularized_SVM

The rest of the notebooks are newer and higher-quality implementations. In particular, the notebooks

- Logistic_Regression
- Single_Layer_Perceptron
- Multiclass_Log_Reg

all contain complete implementations of their respective classifiers, tests on toy data sets and the
standard Iris data set, and mathematical descriptions of the steps of each implementation. These are
examples of how I have learned to think about ML frameworks in general, and I feel these notebooks
provide a near-comprehensive picture of how I personally understand these algorithms.

The data folder here will eventually contain the datasets (synthetic or benchmark) to which many of
these algorithm implementations will be applied.

Stay tuned to this repo for further implementations of ML algorithms (generally following the
complete ones above in structure). 

Next up to implement: a better regularized SVM, Decision Tree, Random Forest, Multi-layer
perceptron, LDA/QDA/etc., and a better 2-layer ANN

Still to come: *.py modules containing many of the supporting functionality (i.e.
statistical/accuracy scoring functions, cross-validation infrastructure, class files for various
custom classes found in the notebooks)

Joseph Melby
October, 2023
