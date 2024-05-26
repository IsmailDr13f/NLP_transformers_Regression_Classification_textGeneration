# NLP Lab - README

## Objective
The main objective of this lab is to get familiar with NLP language models using the PyTorch library.

## Work to Do

### Part 1: Regression task
1. **Data Collection:** Use scraping libraries (Scrapy / BeautifulSoup) to collect text data from various Arabic websites on a specific topic. Prepare the dataset with texts and corresponding relevance scores (0-10).
2. **Preprocessing:** Establish an NLP preprocessing pipeline (tokenization, stemming, lemmatization, stop word removal, discretization, etc.).
3. **Model Training:** Train models using RNN, Bidirectional RNN, GRU, and LSTM architectures. Tune hyperparameters for optimal performance.
4. **Evaluation:** Evaluate the models using standard metrics.

### Part 2: Transformer (Text Generation)
1. **Setup:** Install `pytorch-transformers` and load the GPT-2 pre-trained model.
2. **Fine-tuning:** Fine-tune the GPT-2 model on a custom dataset.
3. **Text Generation:** Generate new paragraphs based on given sentences.

### Part 3: BERT
1. **Model Setup:** Use the pre-trained `bert-base-uncased` model.
2. **Data Preparation:** Prepare the data and adapt the BERT embedding layer.
3. **Fine-tuning and Training:** Fine-tune and train the model with optimal hyperparameters.
4. **Evaluation:** Evaluate the model using standard metrics (accuracy, loss, F1 score).
5. **Conclusion:** Provide a general conclusion about the use of the pre-trained BERT model.

## Tools
- Google Colab or Kaggle or jupyter notebook
- GitLab/GitHub
- SpaCy
- qalsadi
- NLTK
- PyTorch
- Tensorflow

## Dataset Link
- [Amazon Reviews Dataset](https://nijianmo.github.io/amazon/index.html)

## Tutorial Reference
- [GPT-2 Tutorial](https://gist.github.com/mf1024/3df214d2f17f3dcc56450ddf0d5a4cd7)

## Conclusion
This lab provides hands-on experience with NLP tasks including text classification, regression, and generation using advanced models like RNN, GRU, LSTM, GPT-2, and BERT. The exercises help in understanding the practical applications of NLP techniques and the performance evaluation of various language models.