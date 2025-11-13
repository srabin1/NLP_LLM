# NLP_LLM – Natural Language Processing & Deep Learning Notebooks


# NLP Learning Roadmap – From Basics to Deep Learning

A **step-by-step journey** through Natural Language Processing, implemented in **Google Colaboratory**.

---

## Learning Path Overview

| Stage | Focus | Key Concepts |
|------|-------|-------------|
| 1️⃣ **Text Preprocessing** | Clean & vectorize text | Tokenization, Stemming, TF-IDF, Word Embeddings |
| 2️⃣ **Probabilistic Models** | Statistical text generation | Markov Chains, N-grams, Cipher decryption |
| 3️⃣ **Machine Learning** | Classical NLP tasks | Spam, Sentiment, Topic Modeling, TextRank |
| 4️⃣ **Deep Learning** | Neural NLP | ANN, CNN, RNN, CBOW, NER, POS Tagging |

---

## Detailed Roadmap

<details>
<summary><strong>1. Text Preprocessing</strong> – Foundational text cleaning & representation</summary>

| # | Notebook | Description |
|---|--------|-----------|
| 1 | [`01.NLP_Stemming_and_Lemmatization.ipynb`](NLP/code/01.Text_Preprocessing/01.NLP_Stemming_and_Lemmatization.ipynb) | Reduce words to root form |
| 2 | [`02.NLP_Count_Vectorizer.ipynb`](NLP/code/01.Text_Preprocessing/02.NLP_Count_Vectorizer.ipynb) | Bag-of-Words model |
| 3 | [`03.NLP_tfidf_recommender_system.ipynb`](NLP/code/01.Text_Preprocessing/03.NLP_tfidf_recommender_system.ipynb) | TF-IDF for similarity |
| 4 | [`04.NLP_TFIDF_Scratch.ipynb`](NLP/code/01.Text_Preprocessing/04.NLP_TFIDF_Scratch.ipynb) | Implement TF-IDF from scratch |
| 5 | [`05.NLP_Word_Embedding.ipynb`](NLP/code/01.Text_Preprocessing/05.NLP_Word_Embedding.ipynb) | Intro to dense vectors |

</details>

<details>
<summary><strong>2. Probabilistic Models</strong> – Generate text with statistics</summary>

| # | Notebook | Description |
|---|--------|-----------|
| 1 | [`01.NLP_Markov_Model.ipynb`](NLP/code/02.Probabilistic_Models/01.NLP_Markov_Model.ipynb) | N-gram probability chains |
| 2 | [`02.NLP_Poetry_Generator.ipynb`](NLP/code/02.Probabilistic_Models/02.NLP_Poetry_Generator.ipynb) | Generate rhyming poetry |
| 3 | [`03.NLP_Article_Spinner.ipynb`](NLP/code/02.Probabilistic_Models/03.NLP_Article_Spinner.ipynb) | Paraphrase using synonyms |
| 4 | [`04.NLP_Cipher_Decryption.ipynb`](NLP/code/02.Probabilistic_Models/04.NLP_Cipher_Decryption.ipynb) | Frequency analysis attack |

</details>

<details>
<summary><strong>3. Machine Learning Models</strong> – Classic NLP with scikit-learn & more</summary>

| # | Notebook | Description |
|---|--------|-----------|
| 1 | [`01.NLP_Spam_Detection.ipynb`](NLP/code/03.Machine_Learning_Models/01.NLP_Spam_Detection.ipynb) | Naive Bayes classifier |
| 2 | [`02.NLP_Sentiment_Analysis.ipynb`](NLP/code/03.Machine_Learning_Models/02.NLP_Sentiment_Analysis.ipynb) | Positive/negative prediction |
| 3 | [`03.NLP_Text_Summarization.ipynb`](NLP/code/03.Machine_Learning_Models/03.NLP_Text_Summarization.ipynb) | Extractive summarization |
| 4 | [`04.NLP_Text_Rank.ipynb`](NLP/code/03.Machine_Learning_Models/04.NLP_Text_Rank.ipynb) | PageRank for keywords |
| 5 | [`05.NLP_Latent_Dirichlet_Allocation.ipynb`](NLP/code/03.Machine_Learning_Models/05.NLP_Latent_Dirichlet_Allocation.ipynb) | Topic modeling (LDA) |
| 6 | [`06.NLP_Non_Negative_Matrix_Factorization.ipynb`](NLP/code/03.Machine_Learning_Models/06.NLP_Non_Negative_Matrix_Factorization.ipynb) | NMF topics |
| 7 | [`07.NLP_Latent_Semantic_Analysis.ipynb`](NLP/code/03.Machine_Learning_Models/07.NLP_Latent_Semantic_Analysis.ipynb) | SVD for semantics |
| 8 | [`08.NLP_Linear_Regression_Tensorflow.ipynb`](NLP/code/03.Machine_Learning_Models/08.NLP_Linear_Regression_Tensorflow.ipynb) | Regression in TF |
| 9 | [`09.NLP_TF2_Classification.ipynb`](NLP/code/03.Machine_Learning_Models/09.NLP_TF2_Classification.ipynb) | TensorFlow basics |

</details>

<details>
<summary><strong>4. Deep Learning Models</strong> – Neural networks for NLP</summary>

| # | Notebook | Description |
|---|--------|-----------|
| 1 | [`01.NLP_ANN_with_TFIDF.ipynb`](NLP/code/04.Deep_Learning_Models/01.NLP_ANN_with_TFIDF.ipynb) | ANN + TF-IDF |
| 2 | [`02.NLP_Text_Preprocessing_TF.ipynb`](NLP/code/04.Deep_Learning_Models/02.NLP_Text_Preprocessing_TF.ipynb) | TF text pipeline |
| 3 | [`03.NLP_Continuous_Bag_of_Words.ipynb`](NLP/code/04.Deep_Learning_Models/03.NLP_Continuous_Bag_of_Words.ipynb) | CBOW in Keras |
| 4 | [`04.NLP_CNN_Text_Classification.ipynb`](NLP/code/04.Deep_Learning_Models/04.NLP_CNN_Text_Classification.ipynb) | CNN for sentiment |
| 5 | [`05.NLP_RNN_Shapes.ipynb`](NLP/code/04.Deep_Learning_Models/05.NLP_RNN_Shapes.ipynb) | RNN input shapes |
| 6 | [`06.NLP_RNN_Text_Classification.ipynb`](NLP/code/04.Deep_Learning_Models/06.NLP_RNN_Text_Classification.ipynb) | RNN classifier |
| 7 | [`07.NLP_Parts_of_Speech_Tagging.ipynb`](NLP/code/04.Deep_Learning_Models/07.NLP_Parts_of_Speech_Tagging.ipynb) | Sequence labeling |
| 8 | [`08.NLP_Named_Entity_Recognition.ipynb`](NLP/code/04.Deep_Learning_Models/08.NLP_Named_Entity_Recognition.ipynb) | NER with BiLSTM |
| 9 | [`09.NLP_CNN_Many_to_Many.ipynb`](NLP/code/04.Deep_Learning_Models/09.NLP_CNN_Many_to_Many.ipynb) | Many-to-many CNN |

</details>

---

## 🛠 Tech Stack

- **Python** (3.8+)
- **Jupyter Notebook**
- **Libraries**:
  - `numpy`, `pandas`
  - `scikit-learn`
  - `nltk`, `spaCy`
  - `tensorflow` / `keras`
  - `gensim`, `matplotlib`, `seaborn`
 
  ---
## How to Use This Roadmap

1. **Start from the top** → Build strong foundations
2. **Run each notebook in order** within its module
3. **Experiment!** Modify parameters, datasets, or models

