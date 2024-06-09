# Heart Disease Prediction Project

![alt text](https://th.bing.com/th/id/R.209ef541590af14032aee4ca63c4e8ae?rik=Met3bGnverH9%2bw&pid=ImgRaw&r=0) 

On this project we will create a model to predict heart diseases using a dataset obtained from github [1] 

## Table of Contents
1. [Business Understanding](#business-understanding)
2. [Data Understanding](#data-understanding)
3. [Data Preparation](#data-preparation)
4. [Modeling](#modeling)
5. [Evaluation](#evaluation)
6. [Team Members](#team-members)

## Business Understanding
The objective of this project is to develop a predictive model that can accurately determine the likelihood of a heart disease occurrence in patients based on a range of medical parameters. This initiative is crucial because heart disease remains one of the leading causes of mortality globally, and early detection is key to effective treatment and management. By leveraging advanced analytics and machine learning techniques, we aim to provide healthcare professionals with a tool that enhances their diagnostic capabilities, thereby improving patient outcomes and reducing healthcare costs associated with late-stage heart disease treatment.

## Data Understanding
<table>
<thead><tr>
<th>Attribute</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Age</strong></td>
<td>Age of a patient [years]</td>
</tr>
<tr>
<td><strong>Sex</strong></td>
<td>Gender of the patient [M: Male, F: Female]</td>
</tr>
<tr>
<td><strong>ChestPain</strong></td>
<td>Chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]</td>
</tr>
<tr>
<td><strong>RestingBP</strong></td>
<td>Blood pressure in Hg (Normal blood pressure - 120/80 Hg)</td>
</tr>
<tr>
<td><strong>Cholesterol</strong></td>
<td>Serum cholestrol level in blood (Normal cholesterol level below for adults 200mg/dL)</td>
</tr>
<tr>
<td><strong>FastingBS</strong></td>
<td>Fasting Blood Sugar (Normal less than 100mg/dL for non diabetes for diabetes 100-125mg/dL)</td>
</tr>
<tr>
<td><strong>RestingECG</strong></td>
<td>Resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of &gt; 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]</td>
</tr>
<tr>
<td><strong>MaxHR</strong></td>
<td>Maximum heart rate achieved [Numeric value between 60 and 202]</td>
</tr>
<tr>
<td><strong>ExerciseAngina</strong></td>
<td>Exercise-induced angina [Y: Yes, N: No]</td>
</tr>
<tr>
<td><strong>Oldpeak</strong></td>
<td>oldpeak = ST [Numeric value measured in depression]</td>
</tr>
<tr>
<td><strong>ST_Slope</strong></td>
<td>The slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]</td>
</tr>
<tr>
<td><strong>HeartDisease</strong></td>
<td>output class [1: heart disease, 0: Normal]</td>
</tr>
</tbody>
</table>

## Data Preparation
The data preparation stage is fundamental to the success of predictive modeling. For this project, we will perform several steps to prepare the data:
- **Data Cleaning**: Address missing values, remove duplicates, and correct erroneous data entries.
- **Feature Selection**: Identify which features are most relevant to heart disease prediction through statistical analysis and domain knowledge.
- **Data Transformation**: Normalize or standardize data to ensure that the model inputs are on a comparable scale.
- **Train-Test Split**: Divide the data into training and testing sets to ensure the model can be trained and then independently evaluated.

## Modeling
We will explore five different machine learning models to predict heart disease:

### 1. Neural Network (NN)
A Neural Network will be configured with multiple layers to learn complex patterns from the data. It is expected to perform well due to its ability to model nonlinear relationships.

### 2. Logistic Regression
As a statistical model, Logistic Regression is straightforward and efficient for binary classification problems such as predicting the presence or absence of heart disease.

### 3. Decision Tree Classifier
This model uses a tree-like graph of decisions and their possible consequences. It is intuitive and easy to interpret, making it useful for gaining insights into the decision-making process.

### 4. Random Forest Classifier
An ensemble method that operates by constructing a multitude of decision trees at training time and outputting the class that is the mode of the classes of the individual trees. It is typically more accurate than a single decision tree.

### 5. KNeighbors Classifier
A non-parametric method used for classification and regression. In this case, it will classify patients by a majority vote of their neighbors, with the patient being assigned to the class most common among its k nearest neighbors.

## Evaluation
The models will be evaluated based on their accuracy and the insights provided by the confusion matrix. 

- **Accuracy**: This metric will help us understand the overall effectiveness of the model in correctly predicting heart disease.
- **Confusion Matrix**: Each model will have its results summarized in a confusion matrix, which will provide detailed insight into true positives, true negatives, false positives, and false negatives. This breakdown is crucial for understanding the model's performance in various scenarios.

## Team Members
* [Aaron Zhu](https://github.com/aazhu0)
* [Daniel Rice](https://github.com/drice16)
* [Paola Morales](https://github.com/285608)
* [Charles Averill](https://github.com/charlieaverill)
* [Leonardo Alvarado](https://github.com/Leonardoalv201)

This collaborative effort combines expertise from multiple domains to ensure the success of the heart disease prediction project.

[1] Dataset: https://github.com/jayachandru001/Heart-Failure-Prediction-/tree/main
