# Radical Violence in Yemenis’ Social media: Leveraging Sentiment Analysis and Deep Learning to Detect Radical Violence on Social Media
A Detection Radical Violence System (DRVS) is a proposed system to detect violence based on sentiment analysis and Deep Learning algorithms.
# Data Collection 
we collect a new dataset by API twitter Crawling for user com- ments and opinions on Yemenis’ Social Media. There are various techniques used for Crawling, such as API twitter, spider. The target will be a company’s website or their account on social media.
# Classification Violence tweets based on Topic Modelling 
 we labelled the dataset with the aspects by using Word2Vec [9] to measure the similarity degree between the aspects, which were selected in the previous phase and the sentences in the dataset. And give each sentence one aspect based on a high similarity degree. To validate the selection for the aspects, we used the topic modeling method (Latent Dirichlet Allocation algorithm) [8] to classify the users’ comments into Topics. In this phase, each sentence has a topic, and each topic has 20 top-keywords. Based on the topic’s keywords, we can determine aspects to each sentence and then apply labeling to the dataset.
# Validation Classification based on Deep Learning
to validadtion classification Processing, we used  machine learning (Naive Bayes Classifier (NBC),  Rocchio classification, Boosting and Bagging, Bagging, K-nearest Neighbor, Support Vector Machine (SVM), Conditional Random Field (CRF) and Decision Tree) to re-classification processing. we reached to high competitive result.
# Validation Classification based on Machine Learning
we used also Deep Neural Networks architectures to re-classification to validated classification processing. 
in this reseach, we used convolutional neural network, Recurrent neural networks, Deep neural networks and  Recurrent convolutional neural network
# Sentiment Analysis
Sentiment Analysis (VADER, Textblob, or wordnet ) is used for each aspect. So, we found out the polarities of the users’ opinions to each aspect to generate the sentiment (Informative), but we found some sentences have key- words that reflect Negative, or Positive (informative ) at the same time these keywords by Lexicon Emotions reflect to the opposite results. So, we used lexi- con Emotion such (NRC and SenticNet) to find users’ emotions to each aspect and generated the sentiment analysis (emotional).

# Dependencies

* [NLTK:](https://anaconda.org/anaconda/nltk) `conda install nltk` 
* [Pandas:](https://pypi.org/project/pandas/) `pip install pandas `.
* [Numpy:](https://anaconda.org/anaconda/numpy) `conda install -c anaconda numpy `.
* [Scikit-cmeans:](https://pypi.org/project/scikit-cmeans) `pip install scikit-cmeans`.
* [Keras:](https://pypi.org/project/keras/) `pip install keras`.
* [Tensorflow:](https://www.tensorflow.org/install) `pip install tensorflow`.
* [LDA:](https://pypi.org/project/lda/) `pip install lda`.
