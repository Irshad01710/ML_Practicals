# ML_Practicals

# 1(A) Principal Component Analysis (PCA) 

## Dataset- Wine dataset 
- Source: [https://www.kaggle.com/datasets/hrdkcodes/wine-data]

Principal Component Analysis is a powerful technique used for dimensionality reduction while preserving as much variability as possible in the data. In this experiment, we will apply PCA to a wine dataset to reduce its dimensionality and help distinguish between red and white wine based on principal components.

## Step-by-Step Procedure:-

- Step 1: Load the Data:
  
  We start by loading the wine dataset, which includes measurements for various variables such as alcohol, ash, magnesium, and so on. For this example, we'll use a publicly available wine dataset.
                      
- Step 2: Preprocess the Data:
                      Preprocessing steps include handling missing values, scaling the data, and ensuring that the data is suitable for PCA.
                      
- Step 3: Apply PCA:
  
  We apply PCA to transform the original dataset into a new set of variables (principal components). The goal is to capture most of the variability in the data with a smaller number of principal components.

- Step 4: Analyze the Results:
  
   We examine the principal components to understand how much variability each component captures. We also visualize the transformed data to see if it helps in distinguishing between red and white wine.


- Conclusion:-

By applying PCA, we reduced the dimensionality of the wine dataset and visualized it using the first two principal components. The plot shows how the principal components help in distinguishing between red and white wine. While PCA can capture a significant portion of the variability, it is often beneficial to experiment with more components and further analysis to improve classification and understanding of the data.


# 1(B) Linear Discriminant Analysis (LDA)

## Dataset- Iris dataset
- Source: [https://www.kaggle.com/datasets/uciml/iris]

LDA is a supervised dimensionality reduction technique that maximizes the separation between multiple classes. In this experiment, we will apply LDA to an iris dataset to reduce its dimensionality and help distinuishing between different species.

## Step-by-Step Procedure:- 
- Step 1: Load and Prepare the Iris Dataset:
  
  The Iris dataset is readily available in scikit-learn. Here's how to load and prepare it.

- Step 2: Apply LDA for Classification:
                    
  Now, apply LDA to reduce dimensions and classify the species.

- Step 3: Visualize the Results:

  To better understand the classification, visualize the decision boundaries and the LDA projections.

- Conclusion:- 

We successfully applied Linear Discriminant Analysis (LDA) to the Iris dataset to classify iris flowers into their respective species. LDA proved to be an effective technique for both dimensionality reduction and classification by maximizing the separability between the three species classes.
