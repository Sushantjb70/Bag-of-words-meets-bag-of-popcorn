# Bag of Words Meets Bags of Popcorn


## Table of Contents  
- [Project Description](#project-overview)
- [Installations](#install)
- [Code](#code)
- [Run](#run)
- [Data](#data)


### <a name="project-overview"></a>Project Description

This project contains a practice of using Bag-of-Words with a Random Forest Classifier to learn IMDB review text and predict review sentiment labels.
In this project we train the labelled data.Based on this trained data we label the test data with 0 and 1 i.e negative and positive reviews.
The final output is stored in a .csv file.
The step-wise screenshots of the implementation have also been provided.


### <a name="install"></a>Installations.

This project requires **Python 3.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/)
- [nltk](http://www.nltk.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/)

Moreover, use anaconda to install the packages.You can also use pip installation.
Eg: conda install numpy
Eg: pip install numpy

### <a name="code"></a>Code

The code is provided in the `BOW meets BOP.ipynb` notebook file.
The code is simple to execute as additional information about the various steps is given in the code itself.
You will also be required to use the dataset file in `data` directory to complete your work.
The steps are as follows:
1) Step 1: import all the modules/packages.
2) Step 2: Load Training Data for supervised learning.Read the labeled training data in .tsv file with pandas.read_csv.
3) Step 3: Displaying the training labeled data.
4) Step 4: Data Cleaning and Preprocessing.
5) Step 5: Dealing with Punctuation, Numbers and Stopwords.
6) Step 6: Creating Features from a Bag of Words.
7) Step 7: Creating a function for the Cleaning Process.
8) Step 8: Load,Read and Clean Test Data.
9) Step 9: Use Random Forest Method for Classification.
10) Step 10: Final output.Creating a Submission of Random Forest.

### <a name="run"></a>Run

Open the jupyter notebook using the terminal and then navigate to the directory where you have downloaded this file and open the `BOW meets BOP.ipynb` file. Run the code step-wise.


### <a name='data'></a>Data

Training data is provided in the data directory.
You can also download the Training and test data [here](https://www.kaggle.com/c/word2vec-nlp-tutorial/data).
The data also contains the sample submission file.
