# Machine Learning Labs

Lab and project notebooks from my AI graduate certificate coursework (Seneca Polytechnic, 2024). They go from probability and classical models to neural networks in TensorFlow and PyTorch. This is coursework, kept here as a record.

## Labs

| Notebook | What it covers |
|---|---|
| [`Python_Conda_Numpy_Pandas_Basics`](Python_Conda_Numpy_Pandas_Basics.ipynb) | Lab 1: Conda environments, NumPy and pandas basics |
| [`Bayesian_Email_Classifier_and_Probability`](Bayesian_Email_Classifier_and_Probability.ipynb) | Lab 2: coin-flip simulation, then a spam classifier built from Bayes' theorem |
| [`Decision_Theory_Examples`](Decision_Theory_Examples.ipynb) | Lab 3: decision theory through worked examples |
| [`Entropy_and_Information_Gain`](Entropy_and_Information_Gain.ipynb) | Lab 4: entropy and information gain, applied to a decision tree on Iris |
| [`Linear_Regression_with_CarPrices`](Linear_Regression_with_CarPrices.ipynb) | Lab 5: linear regression on synthetic data, then on car prices |
| [`Classification_LogReg_and_KNN`](Classification_LogReg_and_KNN.ipynb) | Lab 6: logistic regression (breast cancer) and KNN (Iris) |
| [`PyTorch_Spiral_Classifier_and_Intro`](PyTorch_Spiral_Classifier_and_Intro.ipynb) | Lab 8: tensors and autograd, then a multi-layer network on synthetic spiral data |
| [`TensorFlow_Addition_Model`](TensorFlow_Addition_Model.ipynb) | Getting started with TensorFlow: a small model that learns addition |

## Projects

| Notebook | What it covers |
|---|---|
| [`MNIST_GPU_Training_TF_vs_PyTorch`](MNIST_GPU_Training_TF_vs_PyTorch.ipynb) | The same simple network trained on MNIST in TensorFlow and in PyTorch, on GPU |
| [`CNN_CIFAR10_ImageClassifier`](CNN_CIFAR10_ImageClassifier.ipynb) | A convolutional network for CIFAR-10 in Keras |
| [`RNN_SentimentAnalysis_IMDB`](RNN_SentimentAnalysis_IMDB.ipynb) | A simple RNN for IMDB review sentiment in Keras |
| [`Project 1/Superstore_Sales_EDA_and_Statistical_Analysis`](Project%201/Superstore_Sales_EDA_and_Statistical_Analysis.ipynb) | Cleaning, exploratory analysis and statistics on the Kaggle Superstore Sales dataset |
| [`Project 2/Regression_and_Classification_Comparison_Project`](Project%202/Regression_and_Classification_Comparison_Project.ipynb) | Regression on USA housing prices and classification on UCI heart disease data, comparing several models |

## Running them

The notebooks use pandas, scikit-learn, TensorFlow/Keras and PyTorch. MNIST, CIFAR-10 and IMDB download through Keras or torchvision; the Superstore, housing and heart-disease CSVs are in the project folders.

Two datasets aren't in this repo, so those notebooks won't run as-is: `simulated_email_dataset.csv` (Lab 2) and `carprice.csv` (Lab 5).
