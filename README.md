# Principal-Component-Analysis-on-Breast-Tumor-Cancer-Data

The goal of this project is to implement Principal Component Analysis on the [Breast Cancer Data](https://github.com/Benjamin-compute/Breast-Cancer-Prediction__Comparing-4-ML-Algorithms) (without the 'target' variable).


The number of patients/instances is 569, with 30 original features (predictors). 


The Cumulative Explained Variance Ratio method was used to determine the optimal number of components, ensuring at least a 95% explained variance. Hence, the original 30 features were reduced to 10 features/components. 


Key Takeaways
Biological insights were given based on the main Principal Components (PC1 and PC2), which explained the most variance (~63%) of the top 10 components.

      Together, these two Principal Components gave a clear message that most tumors sit somewhere in the space of shape irregularity or distortion (PC1) and complexity (PC2).
      
      Other PCs (PC3 - PC10) are not very significant in determining malignancy, considering their individual variation is very low. For example, PC3 is less than 10% and continues to decrease until PC10, which is less than 2%
      
      Our data suggest that the primary biological difference between a benign and a malignant tumor is how distorted or irregular their structure is. In other words, malignant tumors tend to have irregular margins.
      
      The most diagnostic information in the dataset sits in a single hidden pattern (PC1)

