[Article](https://github.com/Chawalar/Fake-news-detection/blob/master/Fake_news_detection.pdf) about this project

# Fake news detection project for Huawei NLP course

Everyday we accessing media outlets such as news blogs, social media feeds, and online newspapers have made it challenging to identify trustworthy news sources, thus increasing the need for computational tools able to provide insights into the reliability of online content.
I want to conduct a set of learning experiments to build accurate fake news detectors, and show that accuracies i can achieve.

# Baseline models
Implemented five machine learning algorithms for fake news detection:
- Passive Aggressive Classifier
- Naive Bayes 
- Logistic Regression
- Random Forest
- XGBoost

# Main model - BERT
- Implemented BERT model with PyTorch
- In this case i choice pre-trained bert-base-cased model by huggingface what i finetuned in process
- In this model we have: 

12-layer, 768-hidden, 12-heads, 110M parameters

Pre-trained on cased English text and finetuned on political articles news dataset.

# Files info
- news.csv - politics articles news dataset
- cleaner.py - functions for text cleaning and filtering
- Fake_news_basic_algorithms_modeling - implementation of basic algorithms for fake news classifier
- text_preprocessing - different ways to text preprocessing
- BERT_fake_news - implementation of BERT with PyTorch

# Most common words in fake news articles
![WordCloud](https://raw.githubusercontent.com/Chawalar/Fake-news-detection/master/img/wordcloud.png)

# Reference
1. [The Illustrated BERT, ELMo, and co. (How NLP Cracked Transfer Learning)](http://jalammar.github.io/illustrated-bert/)
2. [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/pdf/1810.04805.pdf)
3. [Fake News Detection Using Machine Learning](https://matheo.uliege.be/bitstream/2268.2/8416/1/s134450_fake_news_detection_using_machine_learning.pdf)
4. [Pre-trained transformers and usage examples by HuggingFace team](https://github.com/huggingface/transformers)
5. [Attention Is All You Need](https://arxiv.org/pdf/1706.03762.pdf)
