# Principal-Component-Analysis-on-Breast-Tumor-Cancer-Data

The goal of this project is to implement Principal Component Analysis on the [Breast Cancer Data](https://github.com/Benjamin-compute/Breast-Cancer-Prediction__Comparing-4-ML-Algorithms) (without the 'target' variable).


The number of patients/instances is 569, with 30 original features (predictors). 


The Cumulative Explained Variance Ratio method was used to determine the optimal number of components, ensuring at least a 95% explained variance. Hence, the original 30 features were reduced to 10 features/components. 

Biological insights were given based on the main Principal Components (PC1 and PC2), which explained the most variance (~63%) of the top 10 components.
* PC1 and PC2 formed a space which is assumed to contain most tumor cells, and then each is correlated with the 'target' variable to see how well they drive the diagnosis of whether a tumor is malignant or benign.

