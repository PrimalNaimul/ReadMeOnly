<a name="readme-top"></a>

<!-- ABOUT THE PROJECT -->
## About The Project
<p align="center"><img src="https://github.com/PrimalNaimul/IMDB-Sentiment-Analysis-NLP/blob/main/img/SentimentAnalysis.gif"/></p>

In this project, I trained a Stochastic Gradient Descent Classifer using a Unigram and Bigram data representation of IMDB reviews. I then used the trained classifer to predict whether the review was positive or negative.


### Dataset
```
 http://ai.stanford.edu/~amaas/data/sentiment
```

### Unigram Representation Example
The very first step in solving any NLP problem is finding a way to represent the text data so that machines can understand.A common approach is using a document-term vector where each document is encoded as a discrete vector that counts occurrences of each word in the vocabulary it contains. For example, consider two one-sentence documents:  
* d1: “I love Columbia Artificial Intelligence course.
* d2: “Artificial Intelligence is awesome”

The vocabulary V = {artificial, awesome, Columbia, course, I, intelligence, is, love} and two documents can be encoded as v1 and v2 as follow:

<img src="https://github.com/PrimalNaimul/IMDB-Sentiment-Analysis-NLP/blob/main/img/Unigram.PNG"/>

### Bigram Representation Example
A more sophisticated data representation model is the bigram model where occurrences depend on a sequence of two words rather than an individual one. Taking the same example like before, v1 and v2 are now encoded as follow:

<img src="https://github.com/PrimalNaimul/IMDB-Sentiment-Analysis-NLP/blob/main/img/Bigram.PNG"/>

### Output
Depending on the data representation used to train the model, the output text files will contain a single column of classifications. The output files will be named likeso:

```
unigram.output.txt
bigram.output.txt
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Dependencies -->
## Dependencies
* python = 3.9
* numpy >= 1.16
* scikit-learn >= 0.21
* pandas >= 1.4

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact
Naimul Hasan - nhasan9@gatech.edu

<p align="right">(<a href="#readme-top">back to top</a>)</p>

http://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz.