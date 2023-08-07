# Assignment: Iris Dataset Analysis with PySpark on Databricks

In this assignment, we will analyze the Iris dataset using PySpark in a Databricks notebook. The main tasks include converting the species column to a numeric column, creating a features column using VectorAssembler, splitting the data into train-test sets, training two MLlib models on the train data, and evaluating their accuracy. We will also save the best model and later load it for prediction on the test data.

## Steps:

1. Load the Iris Dataset using Spark: 
   We will start by loading the Iris dataset into a DataFrame using Spark.

2. Convert Species Column to Numeric:
   We will convert the "species" column to a numeric column using StringIndexer, which is preferred for this task.

3. Create Features Column with VectorAssembler:
   We will use the VectorAssembler to create a single features column from multiple feature columns.

4. Split Data into Train-Test:
   Next, we will split the data into training and test sets to prepare for model training and evaluation.

5. Train Two MLlib Models:
   We will train two MLlib models on the training data and print their accuracy.

6. Save the Best Model and Load It Again:
   After finding the best model, we will save it to a specific location on DBFS. Later, we will load the saved model and use it for predictions on the test data.

## Files:

- `iris.csv`: The dataset file containing the Iris dataset.
- `ml1.ipynb`: The Databricks notebook where the analysis is performed.

Note: The notebook will include code snippets, explanations, and visualizations to help understand each step of the analysis.
