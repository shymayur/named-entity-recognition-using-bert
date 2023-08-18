# named-entity-recognition-using-bert
In this code I have developed a model which is able to predict the named entity present in the given text sample.

# About NER:
Named Entity Recognition (NER) is a crucial natural language processing (NLP) task that identifies and classifies entities within text. These entities could be names of people, organizations, locations, dates, and more. NER plays a pivotal role in information extraction, enabling machines to understand context and relationships in unstructured text. By automating entity recognition, NER enhances various applications, from information retrieval to sentiment analysis and chatbots. Advanced techniques, like deep learning and pre-trained models, have propelled NER's accuracy, making it an indispensable tool in modern NLP, transforming raw text into structured, actionable insights.

# BERT
BERT (Bidirectional Encoder Representations from Transformers) is a groundbreaking NLP model that learns contextualized word representations by considering both left and right contexts. Pre-trained on massive text corpora, BERT has revolutionized various NLP tasks, achieving state-of-the-art results. Its deep understanding of context makes BERT a cornerstone in natural language understanding and generation.

# Steps:
  1.	Importing required libraries, classes and the dataset (from Kaggle)
  2.	Preprocessing: NaN, Rename, Encoding, Upper-case, Lower-case
  3.	Train-Test split
  4.	Model selection
  5.	Setting “labels” 
  6.	Hyperparameters: num_train_epochs learning_rate, overwrite_output_dir, train_batch_size, eval_batch_size
  7.	Defining the model and training
  8.	Checking outcomes and making predictions

# Applications/Use cases:
  1.	Classifying the content for news providers
  2.	Efficient search algorithms
  3.	Powering content recommendations
  4.	Customer Support
  5.	Analysing research papers based on the entities
  6.	Extraction of useful info from an unstructured text data
  7.	Bioinformatics can be improved
  8.	For analysis of text data
