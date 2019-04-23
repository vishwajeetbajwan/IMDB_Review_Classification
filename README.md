# IMDB_Review_Classification_using_Word_Embeddings
Opinion mining (sometimes known as sentiment analysis or emotion AI) refers to the use of natural language processing, text analysis, computational linguistics, and biometrics to systematically identify, extract, quantify, and study affective states and subjective information.
We can use classifiers on textual data to classify the text into its signified emotion. This can be used in various ways to predict the sentiments of any text automatically after it is trained in a corpus of sentences.

In this project we will classify the IMDB reviews for positive and negative reviews.

## Prerequisites
It is highly recommend that before starting the project you have some kind of toolchain and development environment already installed and ready. If you have no idea where to start with this, try a combination like:
- Python
- scikit-learn / sklearn- 
- Pandas
- NumPy
- matplotlib
- An environment to work in something like Jupyter or Spyder
- For Linux people, your package manager should be able to handle all of this. If it somehow can't, see if you can at least install Python and pip and then use pip to install the above packages.

## Objective:
- Using unweighted and normalized sentence vectors as features for the text using GloVe word embeddings.
- Use different standard classifiers for classification of the texts.
- Compare the accuracy of both normalized and unnormalized sentence vectors.
- Compare the accuracy of the classifiers using different standard classification metrics.

## Dataset:
The dataset is in form of a txt file and can be downloaded from:
https://drive.google.com/file/d/1zXOovxa6RSqmIOaFu9RNlluVlmyBfJ0M/view?usp=sharing
Each line has the text and tab separated target value.
1-Positive review
0-Negative review

## Workflow:
- Extract and store the word vectors for the words present in your dataset using proper data structures.
- Generate the sentence vectors both normalized and unnormalized for the textual data.
- Use the sentence vectors as the features of the sentences and the target of the training data to train the classifier.
- Use various standard classifiers and train with both normalized and unnormalized sentence vectors separately and compare the accuracy with various metrics like f1-score and accuracy_score.
- Finally compare the different classifier models on the data.
