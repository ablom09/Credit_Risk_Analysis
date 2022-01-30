# Credit_Risk_Analysis

**Overview:**

Our colleague Jill has approached us to help use the tools and reasoning within machine learning to the context of credit card risk. Because all lending, including credit cards, have an inherent risk to their operations, lending institutions need risk-reducing tools to help determine where to lend. In this project, we utilized the processes of imbalanced-learn and sckikit-learn libraries to evaluate our risk models while also using resampling methods.

By first drawing our credit card dataset from LendingClub, we’ll oversample our data with the RandomOverSampler and SMOTE algorithms before we then undersample our data with the ClusterCentriods algorithm. Finally, we will use a combination to compare our two machine learning models to reduce bias and make predictions within credit-risk.

**Results**

![image](https://user-images.githubusercontent.com/91284661/151713106-1999678e-56f8-4e78-b25e-0d023aa71a4b.png)

**SMOTEENN**

![image](https://user-images.githubusercontent.com/91284661/151713110-5d84985f-53d4-4757-abbf-17c2fdc0b612.png)

**SMOTE**

![image](https://user-images.githubusercontent.com/91284661/151713119-b99d5ead-20db-4418-b10e-89bebdea301e.png)

**RandomOverSample**

![image](https://user-images.githubusercontent.com/91284661/151713148-ca75e2b3-1952-4f63-bb12-a272fa80570e.png)

**ClusterCentroids**

![image](https://user-images.githubusercontent.com/91284661/151713159-5587cdba-d394-4b14-9639-e594294f0bbb.png)

**EasyEnsembleClassifier**

![image](https://user-images.githubusercontent.com/91284661/151713168-e734599f-6ae8-4a75-b6c8-ab1ae7f04257.png)

**BalancedRandomForestClassifier**

**Summary:**

Across all models, it can be observed that utilizing the EasyEnsembleClassifer delivers the most effective and efficient results. This can be readily shown in part by its method providing the highest score for all Risk loans, with low precision in each observed model. It can also be seen with current analysis higher than 90%, the EasyEnsembleClassifier will perform a precise, and effective report for examining High-Risk Loan analysis.
