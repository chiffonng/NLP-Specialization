Archive of my weekly final assignments with deeplearning.ai's [Natural Language Processing Specialization on Coursera](https://www.coursera.org/specializations/natural-language-processing), taught by Younes Bensouda Mourri, Instructor of AI at Stanford University and Łukasz Kaiser, Staff Research Scientist at Google Brain and the co-author of Tensorflow, the Tensor2Tensor and Trax libraries, and the Transformer paper. 

[Certificate](https://coursera.org/share/edef25426347b74c7ea0d11cce365065)

**LICENSE NOTE**: The assignments and materials are the intellectual property of deeplearning.ai, which should only be shared for educational purposes. Please do not use these for any commercial purposes. **I do not own the rights to the course material, nor am affiliated with deeplearning.ai in any way.**

My work is stored here for *my own* review. While I hope that this repository can be a helpful resource for others, I would like to remind you that copying or using any of the code here will not help you learn the material. I encourage you to try to solve the assignments yourself before looking at the solutions.

# Structure

## Course 1: Classification and Vector Spaces in NLP

**Week 1: Logistic Regression for Sentiment Analysis of Tweets**

- Use a simple method to classify positive or negative sentiment in tweets

**Week 2: Naïve Bayes for Sentiment Analysis of Tweets**

- Use a more advanced model for sentiment analysis

**Week 3: Vector Space Models**

- Use vector space models to discover relationships between words and use principal component analysis (PCA) to reduce the dimensionality of the vector space and visualize those relationships

**Week 4: Word Embeddings and Locality Sensitive Hashing for Machine Translation**

- Write a simple English-to-French translation algorithm using pre-computed word embeddings and locality sensitive hashing to relate words via approximate k-nearest neighbors search


## Course 2: Probabilistic Models in NLP

This is the second course of the Natural Language Processing Specialization.

**Week 1: Auto-correct using Minimum Edit Distance**

- Create a simple auto-correct algorithm using minimum edit distance and dynamic programming

**Week 2: Part-of-Speech (POS) Tagging**

- Apply the Viterbi algorithm for POS tagging, which is important for computational linguistics

**Week 3: N-gram Language Models**

- Write a better auto-complete algorithm using an N-gram model (similar models are used for translation, determining the author of a text, and speech recognition)

**Week 4: Word2Vec and Stochastic Gradient Descent**

- Write your own Word2Vec model that uses a neural network to compute word embeddings using a continuous bag-of-words model


## Course 3: Sequence Models in NLP

This is the third course in the Natural Language Processing Specialization.

**Week 1: Sentiment with Neural Nets**

- Train a neural network with GLoVe word embeddings to perform sentiment analysis of tweets

**Week 2: Language Generation Models**

- Generate synthetic Shakespeare text using a Gated Recurrent Unit (GRU) language model

**Week 3: Named Entity Recognition (NER)**

- Train a recurrent neural network to perform NER using LSTMs with linear layers

**Week 4: Siamese Networks**

- Use so-called ‘Siamese’ LSTM models to compare questions in a corpus and identify those that are worded differently but have the same meaning


## Course 4: Attention Models in NLP

This is the fourth course in the Natural Language Processing Specialization.

**Week 1: Neural Machine Translation with Attention**

- Translate complete English sentences into French using an encoder/decoder attention model

**Week 2: Summarization with Transformer Models**

- Build a transformer model to summarize text

**Week 3: Question-Answering with Transformer Models**

- Use T5 and BERT models to perform question answering

**Week 4: Chatbots with a Reformer Model**

- Build a chatbot using a reformer model

# Notes
- **This is not complete workspace**. I have only included the final assignments for each week. 
    - The course also includes quizzes and practice assignments. 
    - Data and pre-trained models are not included in this repository. They're not suitable for version control here.
- The assignments are written in Python 3 and TensorFlow 2.0.
- The assignments are written in Jupyter Notebooks and are best viewed there.
- In-line comments for some assignments are modified to reflect the intention of the code (for my learning purposes)