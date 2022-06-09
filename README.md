# Project_04_BanknotesFraudDetection
### <b>ABOUT</b>
The IT consulting company offered a new mission at the Ministry of the Interior to fight against organized crime at the Central Office to suppress counterfeiting. This project is focused on building a counterfeit detection algorithm.

### <b>CONDITIONS</b>
This project requires performing:
- Descriptive statistical analysis
- Principal component analysis
- Automatic classification
- Logistic regression type modeling

### <b>SKILLS ASSESSED</b>
- Perform and interpret a PCA analysis
- Use a Kmeans type clustering algorithm
- Modeling using logistic regression

### <b>DATA</b>
The judicial police sent a data set containing the geometric characteristics of banknotes with the following information:

- Banknote length
- Left height
- Right height
- Margin between the upper edge of the banknote and the image
- Margin between the lower edge of the banknote and the image
- Diagonal length

> *Units given in mm*

# <b>MISSIONS</b>
### Mission n°1
Brief description of the data (univariate and bivariate analysis).

### Mission n°2
Implementation of a principal component analysis of the sample, following all these steps:
- Eigenvalue scree analysis
- Representation of the variables by the circle of correlations
- Representation of individuals by factorial plans
- Quality analysis and the contribution of individuals

> *The variable True/False distinguishes the authenticity of the banknote from the fake ones*

### Mission n°3
1. Application of classification algorithm and analysis of the obtained results.
2. Visualization and analysis of the partition obtained in the first PCA factorial plane.

### Mission n°4
Data modeling using logistic regression. This allows for creating a program capable of predicting the authenticity of a banknote. The classification algorithm determines the probability of a banknote's authenticity.
> *If probability >= 0.5, then the banknote is considered True (real)*
> 
> *If probability <= 0.5, then the banknote is considered False (fake)*

# MODEL TESTING AND VALIDATION
The sample/test data used to test and validate the model can be accessed [here](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-analyst/example.csv).

The program will determine whether the banknote is True or False with the associated probability.
