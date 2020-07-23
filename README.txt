--------------------
| - General Info - |
--------------------
MEMBERS
	- Tess Landry: 100926518
	- Darren Pierre: 101015833

FILES
	- report.pdf
	- code.zip
		- README.txt
		- StatsCOMP4900A1.ipynb : Statistical Analysis code, separated for legibility of the main file
		- COMP4900A1.ipynb

NOTES
	- Please hit all play buttons in order
	- Below is a description of each portion of the main code base
		

------------------
| - COMP4900A1 - |
------------------

INITIAL SET-UP
	- Modify the links for each dataset to be the location of where you have the data sets 

START OF THE PROJECT
	- Imports needed libraries

DATASET SET-UP, FORMATTING, AND FEATURE SELECTION
	- Shows selected features using L1 Regression
	- Creates formatter that will be used later to convert a full Pandas dataset to two Numpy arrays (X and Y)

IMPLEMENTING MACHINE LEARNING MODELS
	- MLMetric: class that reports accuracy and confusion matrices
	- LogisticRegression: class that implements Logistic Regression with Gradient Descent
	- LDA: class that implements a Linear Discriminant Analysis
	- KFoldValidation: class that implements a K-Fold Validation.

GET LEARNING RATE FOR LOGISTIC REGRESSION
	- Tests out different learning rates

RUNNING OUR ALGORITHMS
	- Does 5x Runs of 10-Fold Cross Validation for the LDA and Logistic Regression for the following:
		- Parkinsons with all features
		- Parkinsons with selected features
		- Sonar with all features
		- Sonar with selected features

RESULTS
	- Displays results of 5x runs of our algorithms

EXTRAS
	- LDA fit and predict using all data as both training and validation set (not k-fold)




