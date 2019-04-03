## Title
How Data-Augmented Neural Network Perform on Predicting Survival Rate of Heart Attack

## Group Members
Devina Kumar, Barry Yang, and Ray Tianyu Li

## Objectives and Goals of Project
The goal of this project is to compare the performance of various classifiers and neural networks in predicting whether or not a patient survives a heart attack. The project involves training classifiers and networks on the open-source echocardiogram-UCI dataset. We will compare the performance of these classifiers and networks to determine which one performs with the most accuracy.  Then, we will train a neural network on an augmented data set and compare its performance to the most accurate model for the non-augmented set to determine the value of data augmentation.

## Innovation
There are several papers that already compare different classifiers on predicting heart attack survival rates. However, our paper offers several differences:
- Our paper examines the echocardiogram-UCI dataset from Kaggle. To our knowledge, no other papers specifically train multiple classifiers on this dataset.
- No other prominent paper examines data-augmented neural networks on heart attack survival rate.

## Dataset
We plan to use two datasets for this study:
- the dataset provided by the instructor, and
- a larger dataset with similar variables (probably obtained from an ECG, which the first dataset used) that will be used to pre-train a neural network. This dataset can be found [here](https://www.statcrunch.com/app/index.php?dataid=1327534)

The first dataset is smaller, and has 132 observations with 12 variables. The second dataset is larger, and has 481 observations and 8 variables. This dataset will be used to augment the neural network.

## Submission Venue
We plan to write a paper submittable to [IEEE Journal of Biomedical Health Informatics (JBHI)](https://jbhi.embs.org/).

## References
Litjens, Geert, et al. "A survey on deep learning in medical image analysis." *Medical image analysis* 42 (2017): 60-88.

Ravi, Daniele, et al. "A deep learning approach to on-node sensor data analytics for mobile or wearable devices." *IEEE journal of biomedical and health informatics* 21.1 (2017): 56-64.

Ravì, Daniele, et al. "Deep learning for health informatics." *IEEE journal of biomedical and health informatics* 21.1 (2017): 4-21.
