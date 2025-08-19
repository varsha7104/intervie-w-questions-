## 1) Define Nlp?
A) Nlp means Natural Language Processing is the subfield of artificial intelligence and computational  linguistics which is used by the machines and computers to understand ,
anlyze and understand human language
## 2)  What are the main challenges in NLP?
A) The main challenges are :
a) Semantics  
b) Vocabulary
c) Synonyms
d) Contextual Understanding
e) Homononyms
f) Idioms and Phrases
## 3) different tasks in nlp :
A) Speech Recognisition ,Text Recognisition, Part of speech tagger, Chatbot simulation
## 4) )What do you mean by Corpus:
A) In NLP, a corpus is a large, structured collection of texts representing a language, domain, or topic.
It is used to train models, analyze language patterns, and support various NLP research tasks.
## 5)What do you mean by text augmentation in NLP and what are the different text augmentation techniques in NLP?
A) Text augmentation in NLP refers to the process that generates new or modified textual data from existing data in order to increase the diversity and quantity of 
training samples.Text augmentation techniques apply numerous alterations to the original text while keeping the underlying meaning.
1. Synonym Replacement

Replacing words with synonyms to maintain meaning while adding variation.

2. Random Insertion/Deletion

Adding or removing words randomly to mimic noisy or incomplete data.

3. Word Swapping

Shuffling word positions in a sentence to generate alternative structures.

4. Back Translation

Translating text to another language and back to introduce diverse phrasing.

5. Random Masking

Masking words with special tokens (like [MASK]) to train models for prediction.
6. Character-level Augmentation

Introducing spelling errors, substitutions, or noise at the character level.

7. Text Paraphrasing

Rewriting sentences with different structures while preserving meaning.

8. Rule-based Generation

Using grammar or linguistic rules to generate new synthetic text samples.

## 6)What are some common pre-processing techniques used in NLP?
Natural Language Processing (NLP) preprocessing refers to the set of processes and techniques used to prepare raw text input for analysis, modelling, or any other NLP tasks. The purpose of preprocessing is to clean and change text data so that it may be processed or analyzed later.

Preprocessing in NLP typically involves a series of steps, which may include:

Tokenization
Stop Word Removal
Text Normalization
Lowercasing
Lemmatization
Stemming
Removal of Special Characters and Punctuation
Removing HTML Tags or Markup
Spell Correction
## 7) What is text normalization in NLP?
Text normalization, also known as text standardization, is the process of transforming text data into a standardized or normalized form 
It involves applying a variety of techniques to ensure consistency,  reduce variations, and simplify the representation of textual information.

The goal of text normalization is to make text more uniform and easier to process in Natural Language Processing (NLP) tasks.
Some common techniques used in text normalization include:

Lowercasing:
Lemmatization: 
Stemming:
Abbreviation Expansion: 
Numerical Normalization:
Date and Time Normalization: 
## 8) What is tokenization

Tokenization in NLP is the process of splitting text into smaller units called tokens (words, subwords, or characters). It is a fundamental step in tasks like
sentiment analysis, translation, and text generation.

Common Types of Tokenization:

Sentence Tokenization: Splits text into sentences.

Word Tokenization: Splits text into words using spaces/punctuation.

Subword Tokenization: Breaks words into meaningful sub-parts (e.g., sub + word).

Character Tokenization: Splits text into individual characters for fine-grained analysis.

## 9)  What is NLTK and How it's helpful in NLP?
NLTK stands for Natural Language Processing Toolkit. It is a suite of libraries and programs written in Python Language for symbolic and statistical natural language processing.
It offers tokenization, stemming, lemmatization, POS tagging, Named Entity Recognization, parsing, semantic reasoning, and classification.
## 10 ) What is stemming how it is different from the lemmatization?
 A) Stemmization means finding the root word whereas lemmatization means finding the exact words from the thing

 ## 11) What is part of speech tagging?
 Part-of-Speech (POS) Tagging assigns grammatical tags (noun, verb, adjective, etc.) to words in a sentence based on their role and context.

Approaches:

Rule-based: Uses handcrafted linguistic rules (e.g., words ending in -ing → verb).

Statistical: Uses models like HMMs or CRFs trained on tagged corpora to predict tags.

Neural Network-based: Uses RNNs, LSTMs, or Transformers to learn word/context patterns for tagging.
## 12) 12. What is named entity recognition in NLP?
Named Entity Recognization (NER) is a task in natural language processing that is used to identify and classify the named entity in text. 
Named entity refers to real-world objects or concepts, such as persons, organizations, locations, dates, 
## 13). What is parsing in NLP?
In NLP, parsing is defined as the process of determining the underlying structure of a sentence by breaking it down into 
constituent parts and determining the syntactic relationships between them according to formal grammar rules. 

## 14) Types of Parsing? 
Parsing in NLP analyzes the grammatical structure of sentences. Main types include:

Constituency Parsing: Breaks a sentence into hierarchical constituents (phrases) using context-free grammar (e.g., CKY, Earley).

Dependency Parsing: Builds a graph of word-to-word grammatical relations (subject–verb, modifier–noun).

Top-down Parsing: Starts from the root and expands into smaller parts until leaves.

Bottom-up Parsing: Starts from words (leaves) and builds up to the root of the parse tree.
## 15)  What do you mean by vector space in NLP?
In natural language processing (NLP), A vector space is a mathematical vector where words or documents are represented by numerical vectors form. The word or document's specific features or attributes are represented by one of the dimensions of the vector. 
Vector space models are used to convert text into numerical representations that machine learning algorithms can understand.
##16. What is the bag-of-words model?
Bag of Words is a classical text representation technique in NLP that describes the occurrence of words within a document or not. It just keeps track of word 
counts and ignores the grammatical details and the word order.

## 16.) Define the Bag of N-grams model in NLP.
The Bag of n-grams model is a modification of the standard bag-of-words (BoW) model in NLP. Instead of taking individual words to be the fundamental units of representation,
the Bag of n-grams model considers contiguous sequences of n words, known as n-grams, to be the fundamental units of representation.
## 17) What is the term frequency-inverse document frequency (TF-IDF)?
A)TF-IDF (Term Frequency–Inverse Document Frequency) is a text representation metho

Term Frequency (TF): Frequency of a word in a document.

Inverse Document Frequency (IDF): Rarity of the word across all documents (downweights common words, upweights rare ones).

TF-IDF Score = TF × IDF, highlighting terms that are frequent in a document but rare in the corpus.
## 18) Cosine Similarity measures the similarity between two vectors by calculating the cosine of the angle between them. It is widely used in NLP to compare text documents represented as vectors.

Steps:

Text Representation – Convert text to vectors (BoW, TF-IDF, embeddings).

Normalization – Scale vectors to unit length.

Calculation –

Cosine Similarity
(𝑎,𝑏)=𝑎⋅b∣𝑎∣∣𝑏|


Range: -1 to 1 → (1 = identical, 0 = no similarity, -1 = completely opposite).d that measures how important a word is in a document relative to a corpus.
1. Rule-based Approach

Relies on manually crafted linguistic rules and grammar patterns.

High interpretability but requires manual updates for new language variations.

2. Statistical-based Approach

Uses statistical models (e.g., HMMs, CRFs) trained on data to learn patterns.

More flexible than rule-based, works across domains/languages but depends on labeled data.

3. Neural-based Approach

Uses deep learning models (RNNs, LSTMs, Transformers) to learn representations directly from text.

Captures complex semantics, requires large datasets, achieves state-of-the-art results.
