# HEART DISEASE PREDICTION BASED ON PATIENT'S VARIOUS MEDICAL MEASUREMENTS

- THIS PROJECT PORTRAYS THE POWER OF MACHINE LEARNING IN DATA ANALYSIS AND PREDICTIONS

---

## Through this project we shall implement the process of machine learning inorder to solve a problem.

- Below are the processes followed in order to solve the problem
- [1] Get data
- [2] Split the data.
- [3] Clean data.
- [4] Get a model.
- [5] Train a model using various algorithms in this case I have used 3.
- [6] Use the model to make predictions.
- [7] Based on the model's predictions,evaluate the model to identify most effective machine learning algorithm.

[This is the link for downloading the dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset?resource=download)

- We are using jupiter notebook as our development environment.

### AFTER COMPLETING PROCESS 1,2,3,4,5 and 6 we identify the most effective algorithm based on .

1. Accuracy -Model's accuracy.
2. Confusion matrix - model's True positives/negatives and False positives/negatives
3. Classification report. - Breaks down the precision,recall and F1 score. F1 score balances precision and recall providing an overall score.

---

- We shall be using 3 machine learning algorithms here. (LINEAR REGRESSION, K-NEAREST NEIGHBOR,NEURAL NETWORKS)

![K-nearest neighbor output](/img/knearestneighboursoutput.png)
![Linear regression output](/img/linearregressionoutput.png)
![Neural networks output](/img/neuralnetworksoutput.png)

| Algorithm          |      Accuracy      |
| ------------------ | :----------------: |
| K-nearest neighbor | 0.7317073170731707 |
| Linear regression  | 0.7853658536585366 |
| Neural networks    | 0.751219512195122  |

- From the above Linear regression seems to have highest accuracy of 0.785 which is 78.5%. The model correctly classified approximately 78.5% of the samples
  in the test set which is a decent accurate score but it might not be high enough for certain application
  such as healthcare in this case. We should therefore try other models.

- The above model can be used as a Patient Risk assessment tool for healthcare professionals.
