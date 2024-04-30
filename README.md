# BIOACTIVITY-OF-SMALL-MOLECULES-PREDICTION

INTRODUCTION

Our project focuses on developing an intuitive tool utilizing a Bayesian network to swiftly predict the bioactivity of small molecules against target proteins. This endeavor aims to expedite the drug discovery process by leveraging a dataset comprising information on 100 known small molecules, their molecular descriptors, target protein activity, and bioactivity. Through preprocessing, we will partition the dataset into training, validation, and testing sets.

Abstract

In the field of drug discovery, the rapid and accurate prediction of small molecule bioactivity against target proteins is paramount for expediting the identification of potential therapeutics. This project proposes the development of an intuitive tool leveraging Bayesian networks to predict bioactivity swiftly and efficiently. By utilizing molecular descriptors such as the logarithm of the partition coefficient (logP) and molecular weight, the tool aims to assess the hydrophobicity and mass of molecules, respectively. Initial analyses reveal a distribution centered around logP value of 3.0 and molecular weight of 90, providing valuable insights into the dataset characteristics. Moreover, model evaluation through intermediary outputs, including confusion matrices, ROC curves, and F1 score analyses, demonstrates promising performance in distinguishing between active and inactive compounds. Notably, the average area under the ROC curve (AUC) of 0.62 suggests moderate discriminatory ability, while F1 scores consistently highlight the model's effectiveness across various decision thresholds. Furthermore, the alignment of F1 score and accuracy across different folds underscores the tool's robustness and consistency in performance evaluation. Overall, this project endeavors to contribute a valuable resource to the drug discovery process by facilitating the rapid screening and prioritization of potential drug candidates based on their bioactivity profiles.

You can find the code for the implementation in BIOACTIVITY-OF-SMALL-MOLECULES-PREDICTION.ipynb and instructions to install the file can be found in Read Me.docx file
