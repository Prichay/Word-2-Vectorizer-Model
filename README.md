# Word-2-Vectorizer-Model
Innitialization of Word 2 Vec model 

# Word to Vectors

Word2Vec is one of the word embedding technique that is used to convert the word into their corresponding vector representation.
With these numerical representations, you can do many things like identify similarity or dissimilarity between words.
these vectors are then used to carry out certain operationso on the words such as:
* Word Similarity
* Cosine Distance
* Cosine Similarity
* Document Similarity
* Probability assigned to words based on similarity.
and many more. The vectors try to capture various characteristics of that word with regard to the overall text. 
These characteristics can include the semantic relationship of the word, definitions, context, etc.

Data set used:
* Movie Transcript : " Beauty and the Beast "

Carried out operations in the project are:
* Data Scraping via Beautiful Soup.
* Data wragling
* Data Preprocessing using Spacy
  * Lemmatization
  * Regex
  * Lowercasing
  * Stopwords Removel
  * Punctuation Removel
  * Whitespaces and Blankspaces Removel
* Token Frequency to look for most used Words.
* Latent Derichlet Allocation to extract 10 topics to which movie revolves arround.
* Phrase Modulation using gensim to convert frequent words into Ngrams.
* Count Vectorization to convert tokens into Term-Document Frequenncy.
* Word2Vec model to look for word similarity in the context.
