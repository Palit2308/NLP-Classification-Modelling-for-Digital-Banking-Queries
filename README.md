# OSE 
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/R1vgPUT1)


**OSE PROJECT**

Name: Biswajit Palit

Matriculation Number: 50071214


**REPOSITORY STRUCTURE**:

The repository consists of 4 files apart from the README.md files
1. OSE_Project_Essay.pdf : This outlines the project report and underlines my observations in detail
2. Biswajit_Palit_Final_Notebook_Completed.ipynb
3. OSE_Questions_and_Answers.pdf : This comprises answers to 25 questions.
4. environment.yml : This comprises of the packages used in the project.


**PROJECT OUTLINE**:

At the very outset I would like to specify, in order to get the best reproducibility, it is best if the notebook is run sequentially.

*Dataset*: In this project I have used the PolyAI/banking77 dataset from the HuggingFace library. It consists of customer queries and comments related to online banking and digital payments. The dataset consists of 10003 train data points and 3080 test data points. I have for the purpose of cross validation split the test set equally into validation_set and test_set. 

*Task*: I have opted to perform a text classification task on the dataset. I wanted to check the performance of several sk-learn models and compare them with the performance of different transformer models. I have hypertuned each model to find the parameters giving the best accuracy score.

*Structure*: In the first half of the project I have run TF-IDF vectorization and run Logistic Regression, Decision Trees and Naive Bayes. In the second part of the project I have run the transformer models namely, BERT, ROBERTA, DISTILBERT, XLNET. 


**ENVIRONMENT NOTICE**:
 
 I have specified an environment in my code. However I did the project on torch version 1.9.1 and tensorflow 2.6.0 which is not a compatible version for jupyter notebook. Best reproducibility can be achieved when run with all the mentioned packages as well as these particular versions of torch and tensorflow. Reproducibility is mostly being achieved even without them.