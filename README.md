# Sentiment Analysis

We present you the Sentiment analysis code which can be applied to any text, pre-recorded audio or video file. The method relies on a Linear Support Vector Classifier (LSVC) to predict whether a product review is positive or negative. The method employs Google Cloud Speech Recognition API for Speech to text conversion in case the input is an audio or video file.


## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
The following python packages are required for running the software.

[pandas](https://pandas.pydata.org/pandas-docs/stable/)

[Sci-kit learn](http://scikit-learn.org/stable/documentation.html)

[speech recognition](https://pypi.org/project/SpeechRecognition/)

[matplotlib](https://matplotlib.org/contents.html)

[numpy](http://www.numpy.org/)

[OpenCV 3.4.1](https://github.com/opencv/opencv)

[PyTorch](https://pytorch.org/docs/stable/index.html)

## Output format
Output predicted by the classifier is written to output.txt and signifies the following:
0: negative review
1: positive review


## Built With
[Jupyter-notebook](http://jupyter.org/) - A web-based notebook environment for interactive computing.

[Anaconda Python Cloud](https://anaconda.org/anaconda/python) - A free and open source distribution of the Python and R programming languages for data science and machine learning related applications.

[Kaggle Amazon reviews dataset](https://www.kaggle.com/bittlingmayer/amazonreviews)
