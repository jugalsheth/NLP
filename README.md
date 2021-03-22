# NLP
NLP is a very interesting topic for me, it is something which in todays time is helpful to understand human sentiment and used in creation of chatbots, AI assistants, sentiment analysis and forcasting and much more, i am trying to practice and upload everthing i have learned and worked on in NLP

## Tokenization:Process and library 
- NLTK is an important library for Natural Language processing
- we use Punkt package: Punkt Sentence Tokenizer. This tokenizer divides a text into a list of sentences, by using an unsupervised algorithm to build a model for abbreviation words, collocations, and words that start sentences. It must be trained on a large collection of plaintext in the target language before it can be used.

## Stemming and Lemmatization 
- Stemming and Lemmatization are generally performed to make the process faster by compressing, converting the words into its root words
- Stemming leads to root words which are actual words while lemmatization converts the words into actual root language* words
- We use nltk.corpus to import stopwords() which helps us remove the stopwords/filler words in the sentence 
- In the example we use  PorterStemmer() for Stemming and WordNetLemmatizer() for Lemmatization
- Again we may need to download punkt or wordnet packages 

## BagOfWords and TFIDS
- We use these two methods on a very high level to convert the stemmed/lemmetized words into numerical values in order to be easily ingested into a machine learning model
- The difference between them is that BagofWords converts words into numbers based on the frequrncy of occurance while to a certain extent TFIDF assigns weights to words so that we know which words are more important than the other
