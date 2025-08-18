Natural language processing that is used by machines to understand, analyze , manipulate , and intepret human's language 
Applications are : Language Translation, Language detection,Spelling Check(in msword,chatbot,google),mail spam or not spam detection
We will mail under spam in gmail
We can  make the robot to study about the data ,books and we can ask the questions regarding any question
Huge amount of knowledge would be given and train the model from the language When we interpret it we get answer based on the feedback
## Components of Nlp
3 components:
natural language understanding :text is converted When we are clicking same text in the search bar we will direct get the output based on the everything
Natural language generation:Generating into other language
Challenges of nlp:
1) Contextual words and phrases and homononyms
2) synonyms
3) Irony and sarcasm
4) Ambiguity
5) errors in text or speech
6) colloquialisms and slangs(When we want to specify something other thing would be specified)
7) domain specific language
8) low resource language
9) lack of research and development
   Nlp Library
   scikit learn, ntlk,spacy,textblob allennlp,tensorflpw
   What is nlp pipeline?
   A) data collection -> text cleaning->preprocessing->feature engineering ->modelling ->evaluation->deployment->monitoring  and model Updating
   ##  Data Acquistion:
1)    Api to get the data
 2)  by   Web Scraping we can get data
3) survey
## Text Preprocessing :
Text Cleaning : In-text cleaning we do HTML tag removing emoji handling 
Basic Preprocessing : In basic Preprocessing , we do tokenization(word or sent tokenization , remove digit ,lower casing_
Advance Preprocessing : In this step we do POS tagging, Parsing , and Coreference resolution.
Feature Engineering :
One hot Encoder
Bag of Word(BOW)
n-grams, 
Tf-id
Word2vec
 # Modelling / Model Building:
 Approaches to building model:
 Heuristic Approach
 Machine Learning Approach
 Deep Learning Approach 
 Cloud API
 ## Model Evaluation: Accuracy of The model.
 There are 2 types of evaluation:
 1) Intrinsic Evaluation: In this evaluation we use multiple metics to check our model such as Accuracy ,Recall,Confusion Metrics , Perplexity , etc
 2) Extrinsic Evaluation: This evaluation is done after the deployment . This is the business centric approach.
## Deployment:
We can deploy it by web ,application and even on aws server
## Understanding the textual data
Elements of text:
1)Hierachacy of text : No of words and no of alphabets(n gram)
2) Tokens: The words are tokenized 
They are two types of tokenization:
a) Sentence Tokenization
b) Word Tokenization
3) Vocabulary :About the noun
4) Punctation: No of punctation (?,.< > " '; :) 
5) Parts of Speech(Noun,pronoun,adjective)
6)Roots of the word: Study is root word to studies ,student
7 ) Base of a word : originial word can be seen
8) Stopping word: a , the ,an ',' These are not important related to topic
pos_tag gives the parts of speech
## Text Pre-Processing Techniques:
1) LowerCasing
2) Remove Html Tage
3) Remove Urls
4) Removing Punctuation
5) Chat Word Treatment
6) Spelling Correction
   Some other techniques which satisify the constraint and we want to change
1) Tokenization
2) Stops Word Removal
3) N-Grams
4) Stemming
5) Word Sense Disturbution
6) Count Vectorizer
7) Lemmatization
8) TF-IIDF Vectorization
9) Hashing Vector
     ## what is Tokenization:
   Tokenization is used in nlp to split para and sentences into smaller unit that can be easily assigned meaning.
   The first step of the Nlp process is gathering the data( a sentence ) and breaking it into understandable parts (words)
   There are 2 types of tokenization:
   Sentence Tokenization
   Word Tokenization
   Nltk library
   sent_tokenize: It break into tokens
   word_tokenize :It breaks into words
   ## Stop Word Removal:
   These are actually te most common words language and does not add much information to the text .
   For ex: Of a few stop Words in English are "the" ,"a" ,"an", "so" ,"what"
   If sentence is "as well as realize its importance " After removing stop words: " well" ,"realize" ,"importance "
``` python
from nltk.corpus import stopwords
from string import punctation

stop=stopwords.words("english")
stop_words=list(punctation)+stop
for i in var_name:
   if i not in stop_words ::
print(i)
stop
```
   # Stemming and Lemmatization:
  ##  STemming:
  It is a technique used to extract the base form of the words by removing affixes from them.
   changing ,changed ,change-> chang,chang,chang We are only  related with prefix and suffix of the work
   VArious Stemming Algorithm:
   ### Stem():
   Porterstemmer 
   Regexstemmer: Mostly it wont work
   SnowBallstemmer
   Lancasterstemmer
   ## Lemmatization :
   It is like stemming The output we will get after lemmatization is called lemma
   After lemmatization we will getting valid words that means the same thing.
   It will give the right word after cutting
   If we will give mice it will give mouse
   # ngram:
   ngrams  are contigous sequence of words or symbols or tokens in the document in a document in technical terms
   They can be defined as the neighbouring sequence of items in document 
   I works in based on the probability
   It uses :
   Chain PRobability
   Bigram PRobability
   N-gram Probability
   ## Unigram -
   It pairs each word letterwise
   Something like positive is word 
   Then po ,si ,ti ,ve is the pair
  ## Count Vectorizer :
  Nlp inputs we can give it to artifical neuron network
  Count Vectorizer means breaking down a sentence or any text int o words by performing preprocessing tasks  like converting all words to lowercase thus
  removing special character
  It will be given number based on the number
  ## Word Sense Disambiguation:
  Mouse is running
  Mouse is working 
  In first case it mice 
  Second case it would be compupter mouse
  Word Sense Disambiguation: It is an important method of nlp by which the meaning of a word is determined whic his used in a particular context
  I can hear bass sound
  He likes to eat grilled bass
  
