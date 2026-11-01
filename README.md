# Natural-Language-Processing

📌 Repository Overview
This repository serves as a structured, end-to-end sandbox and reference manual for Natural Language Processing. It bridges theory and execution by demonstrating how text data transitions from raw unstructured strings into high-dimensional vector spaces, sequential representations, and attention-driven contextual embeddings.

📂 Repository Contents & Module Breakdown
The repository is logically categorized into core foundational processing, advanced statistical representations, deep learning sequence architectures, and state-of-the-art transformer mechanisms:

1. Fundamentals, Preprocessing & Tokenization
Tokenization_nlp.ipynb / String_Tokenization_NLP.ipynb: Breaking text into sub-word, word, and character tokens.

Lemmatization_&_Stemming.ipynb: Morphological normalization techniques to reduce words to their base roots.

Regular_Expression.ipynb: Pattern matching, cleaning, and regex-based text extraction.

Annotattor_NLP.ipynb: Text annotation and labeling workflows.

NLTK_&_Spacy.ipynb: Comparative pipelines utilizing industry-standard NLP libraries (nltk and spaCy).

TextBlob.ipynb: Quick exploratory data analysis, sentiment analysis, and basic parsing.

Word_NLP.ipynb: Foundational word-level lexical analysis.

2. Classical Vectorization & Distributed Representations
Frequency.ipynb: Frequency-based representations including Bag-of-Words (BoW) and Term Frequency-Inverse Document Frequency (TF-IDF).

Co_Occurrence_Vectors.ipynb: Building and analyzing word co-occurrence matrices for semantic context.

Word_Embedding.ipynb: Introduction to dense vector spaces.

Word2Vec.ipynb: Training and utilizing continuous distributed word representations (Skip-Gram and CBOW architectures).

Doc2Vec.ipynb: Paragraph and document-level embeddings.

Sentence_Embedding.ipynb: Sentence-level semantic vector extraction.

3. Sequential Deep Learning Architectures
NLP_Network.ipynb: Custom neural network layers tailored for text classification.

RNN.ipynb: Vanilla Recurrent Neural Networks for sequence modeling.

LSTM.ipynb: Long Short-Term Memory networks designed to mitigate vanishing gradients.

GRU.ipynb: Gated Recurrent Units for efficient sequential learning.

Encoder_&_Decoder.ipynb: Architecture blueprint for sequence-to-sequence translation and generation.

Sequence_to_Sequence.ipynb: Full seq-to-seq modeling implementation.

4. Advanced Attention Mechanisms & Transformers
Attention_mechanism_NLP.ipynb: Implementation of soft/additive attention mechanisms for sequence decoding.

Self_attnetion.ipynb: Scaled Dot-Product Self-Attention mechanics capturing intra-sequence dependencies.

Transformer.ipynb: End-to-end implementation of the Transformer block (Multi-Head Attention, Positional Encoding, and Feed-Forward networks).

Stanford_(Stanza).ipynb: Utilizing Stanford's Stanza toolkit for deep linguistic analysis and dependency parsing.

🛠️ Tech Stack & Dependencies
The notebooks are implemented in Python using standard data science and deep learning frameworks:

Core & Math: NumPy, Pandas

NLP Libraries: NLTK, spaCy, TextBlob, Stanza

Deep Learning: PyTorch / TensorFlow (depending on notebook configuration)

Environment: Jupyter Notebook / JupyterLab
