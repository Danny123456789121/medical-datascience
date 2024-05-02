# README

Diese README erklärt die Verwendung jedes Skripts.

## data_exploration.ipynb
In diesem Notebook wird der Datensatz zum ersten Mal erkundet. Es werden datenanalytische Plots erstellt, um die Daten kennenzulernen.

## preprocessing.ipynb
In diesem Notebook findet das Preprocessing des Datensatzes statt. Am Ende wird eine Pickle-Datei erstellt, die dann im dataset_split-Notebook und im clustering-Notebook genutzt wird.

## dataset_split.ipynb
In diesem Notebook wird der Datensatz in Trainings- und Testdatensatz aufgeteilt. Am Ende werden vier Pickle-Dateien erstellt (X_train, X_test, y_train, y_test), die für die Classifier-Models verwendet werde.

## clustering.ipynb
In diesem Notebook findet das Clustering des Datensatzes statt. Die Daten "encoding.p" kommen aus dem preprocessing-Notebook.

## knn_classifier.ipynb
In diesem Notebook wird ein KNNClassifier trainiert. Die Daten dafür kommen aus dem dataset_split-Notebook.

## linearSVC.ipynb
In diesem Notebook wird ein LinearSVC Classifier trainiert. Die Daten dafür kommen aus dem dataset_split-Notebook.