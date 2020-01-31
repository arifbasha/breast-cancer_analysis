# Breast Cancer Data Analysis
Breast cancer is a cancer that develops from breast tissue. It occurs as a results of abnormal growth of cells in the breast tissue, commonly referred to as a Tumor. Not all tumors are harmful, it is classified as benign (non-cancerous) and malignant (cancerous) tumors. I carried out this data analysis on the given dataset , which includes measurements of breast cancer cells. Features that are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.

Task that i caried out in the analysis are;
1. Loaded the given dataset
2. Loaded the header file
3. Calculated the mean and median for smoothness and compactness fields for benign and malignant tumors
4. Identified the important features using Exploratory Data Analysis
5. Build 2 classification techniques using the important features; a. Logistic Regression Classification b. Random Forest Classification 
6. Calculated the accuracy of the model 

#Analysis Summary
Given dataset has 32 attributes 
Attribute Information: 
1. ID number 2) Diagnosis (M = malignant, B = benign) 3-32) Ten real-valued features are computed for each cell nucleus: 
a. radius
b. texture
c. perimeter 
d. area 
e. smoothness
f. compactness
g. concavity
h. concave points
i. symmetry 
j. fractal dimension

The mean, standard error and “worst” or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius. 

A. Limitation of this analysis
    Given dataset has 357 benign tumors and 212 malignant tumors, on creation of 70% training dataset there is a chance of minority sampling of malignant tumors to overcome it i have used SMOTE technique but for more accuracy we need more data samples related to malignant tumors.   
