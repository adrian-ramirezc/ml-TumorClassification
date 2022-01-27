# Tumor Gliales Classificaton

**Gliomas** or **glial tumors** are tumors of the glia, the neuronal support tissue of the brain. They are classified in 4 anatomo-pathological grades, on which the management depends.

In this dataset, each observation is a glioma, described by the expression of 4 434 genes.

The expression of a gene is a measure of the amount of RNA corresponding to that gene that is present in the cell. Schematically, DNA is transcribed into RNA, which in turn is translated into a protein. 

Proteins perform a multitude of functions in life, but measuring their quantity is difficult; hence the interest in using RNA quantities, although the correspondence is not immediate.

Each glioma in our dataset is labeled according to its grade.

The goal of this project is to build a classifier that determines, based on the expression of these 4434 genes, the grade of a glioma.

To have in consideration:
- Implement at least 2 models
- Data leakage (do not use the data on which the models are evaluated to train them or preprocess the data)
- The size of the data set
- The number of classes
- Choosing an appropriate performance measure (justify the choice)
- Identify, when possible, the most important genes for the models you have trained. Are these the same genes between two models obtained using a different learning algorithm? between two models obtained using the same training algorithm on different subsamples of the data?
