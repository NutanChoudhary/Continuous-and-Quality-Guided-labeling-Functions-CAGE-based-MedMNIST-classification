# Continuous-and-Quality-Guided-labeling-Functions-CAGE-based-MedMNIST-classification

This project aims to implement a semi-supervised
approach using data programming to generate iterative labels for
the DermaMNIST dataset, a subset of the MedMNIST dataset
that contains medical images for dermatology. The lack of a
large amount of labeled data is a bottleneck for supervised
learning models, and data programming with semi-supervision
can overcome this by utilizing weak supervision in the form of
heuristics or rules and the association of noisy labels to the
training dataset. We used the Continuous and Quality-Guided
Labelling Functions (CAGE) approach to aggregate the noisy
labels and generate iterative labels for large unlabeled datasets
with a high degree of confidence.
We started with a small labeled dataset and wrote shallow
labeling functions to generate labels for the unlabeled data.
The generated labels were then aggregated using SPEAR, a
data programming library that allows users to programmatically
label and build training data. The final labels were used to
train and evaluate three different machine learning algorithms:
Support Vector Machines (SVM), K-Nearest Neighbors (KNN),
and Decision Trees (DT).
