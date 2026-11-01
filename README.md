# Natural Language Processing & Sequence Models

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![NLTK](https://img.shields.io/badge/NLTK-3.x-green?style=for-the-badge)](https://www.nltk.org/)
[![spaCy](https://img.shields.io/badge/spaCy-3.x-09A3D5?style=for-the-badge&logo=spacy&logoColor=white)](https://spacy.io/)
[![HuggingFace](https://img.shields.io/badge/Hugging%20Face-Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

<p align="center">
  A comprehensive repository covering foundational NLP preprocessing, text representations, classical sequence architectures (RNN/LSTM/GRU), Attention Mechanisms, and modern Transformer models.
</p>

</div>

---

## 📌 Repository Architecture

```text
NLP-Repository/
│
├── 📁 01_Text_Preprocessing & Pre-processing Utilities
│   ├── 📜 Tokenization.ipynb                   # Basic Tokenization Techniques
│   ├── 📜 String_Tokenization_NLP.ipynb         # String-level Tokenization Mechanics
│   ├── 📜 Lemmatization_&_Stemming.ipynb       # Stemming & Lemmatization Algorithms
│   ├── 📜 Regular_Expression.ipynb             # Regex Patterns for Text Normalization
│   └── 📜 Annotator_NLP.ipynb                  # Text Annotation Tools & Utilities
│
├── 📁 02_Text_Representation & Embeddings
│   ├── 📜 Frequency.ipynb                      # Bag-of-Words & TF-IDF Vectors
│   ├── 📜 Co_Occurence_Vectors.ipynb           # Co-occurrence Matrix Building
│   ├── 📜 Word_Embedding.ipynb                 # Foundational Word Vectors
│   ├── 📜 Word2Vec.ipynb                       # Continuous Bag-of-Words (CBOW) & Skip-gram
│   ├── 📜 Doc2Vec.ipynb                        # Paragraph & Document Level Embeddings
│   └── 📜 Sentence_Embedding.ipynb             # Sentence-level Vector Representations
│
├── 📁 03_NLP_Libraries & Framework Integration
│   ├── 📜 NLTK_&_Spacy.ipynb                   # Text Pipelines using NLTK and spaCy
│   ├── 📜 Stanford_(Stanza).ipynb               # Linguistic Analysis with Stanford Stanza
│   └── 📜 TextBlob.ipynb                       # Sentiment Analysis & Phrasal Processing
│
├── 📁 04_Recurrent Architecture & Sequence Models
│   ├── 📜 RNN.ipynb                            # Recurrent Neural Network Foundations
│   ├── 📜 LSTM.ipynb                           # Long Short-Term Memory Architectures
│   ├── 📜 GRU.ipynb                            # Gated Recurrent Unit Networks
│   └── 📜 Sequence_to_Sequence.ipynb           # Seq2Seq Architecture for Translation/Summarization
│
├── 📁 05_Attention & Modern Transformer Architectures
│   ├── 📜 Attention_mechanism_NLP.ipynb         # Sequence Attention Mechanisms
│   ├── 📜 Encoder_&_Decoder.ipynb              # Encoder-Decoder Frameworks
│   ├── 📜 Self_attnetion.ipynb                 # Scaled Dot-Product & Multi-Head Self-Attention
│   ├── 📜 Transformer.ipynb                    # Full Transformer Architecture Implementation
│   └── 📜 NLP_Network.ipynb                    # End-to-End Deep Learning NLP Networks
│
└── 📜 LICENSE                                   # MIT Open-Source License
