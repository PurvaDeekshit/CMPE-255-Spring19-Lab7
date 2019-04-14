# cmpe255-spring19-lab7

I have plotted four graphs:
1. Linear SVC
2. Polynomial SVC
3. Gaussian SVC
4. Sigmoid SVC

Each with Regularization parameter C = 1 and C = 10. Polynomial and Guassian kernels are also plotted for C = 5.

The plots show how decision boundaries change with a change in hyperparameters.

For Linear kernel, boundary is same even when hyperparameters are changed.

For Polynomial and Gaussian kernel, data is fitted more with an increase in regularization parameter.

For Sigmoid kernel, the plot shows no decision boundary, since the dataset contains three classes and Sigmoid kernel can be used for binary classification.

However, I changed the dataset to have two classes for ploting Sigmoid kernel decision boundary, but still no classification is shown, even after changing the parameters like degree, coefficient0, regularization and gamma.
