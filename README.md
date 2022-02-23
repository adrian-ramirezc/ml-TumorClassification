# Tumor Gliales Classificaton

**Gliomas** or **glial tumors** are tumors of the glia, the neuronal support tissue of the brain. They are classified in 4 anatomo-pathological grades, on which the management depends.

In this dataset, each observation is a glioma, described by the expression of 4 434 genes.

The expression of a gene is a measure of the amount of RNA corresponding to that gene that is present in the cell. Schematically, DNA is transcribed into RNA, which in turn is translated into a protein. 

Proteins perform a multitude of functions in life, but measuring their quantity is difficult; hence the interest in using RNA quantities, although the correspondence is not immediate.

Each glioma in our dataset is labeled according to its grade.

The goal of this project is to build a classifier that determines, based on the expression of these 4434 genes, the grade of a glioma.

To have in consideration:
- 2 ML models implemented
- Data leakage (the training daata is not used to evaluate the model, if the data needs to be preprocessed the training parameters will be applied to the test/validation dataset)
- The size of the data set is too small
- The number of classes is huge
- An appropriate performance measure is chosen and justified.
- The most important genes, when possible, are identified for the implemented models. 
