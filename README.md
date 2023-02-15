# Natural Language Processing

## First assignment
Developing a Naïve Bayas Classifier able to distinguish between english documents and not-english documents.  

## Pipeline
- Extracting english and not-english documents from the europarl dataset
- Creating the sets of stopwords for the languages used
- Tokenizing, stemming and removing the stopwords
- Doing some data preprocessing 
- Training the Naïve Bayas Classifier of nltk
- Tests
- Calculating the confusion matrix 
- Calculating precision, recall and F-measure 
- Displaying accuracy and most informative features

## Second assignment
The assignment consists in the development a pipeline that, starting from a text in input, in a given language (English, French, German, Italian) outputs the syntactic tree of the sentence itself.

We can assume the following:

- Adjectives in English and German are prefixed to nouns
- Adjectives in Italian and French are postponed to nouns
- Verbs are all at present tense
- No pronouns are admitted
- Only one adverb is admitted and is always postponed with respect to the verb

For this assignment I decided to write a simple context free grammar that fits the sentences that I give as inputs, I used spacy for pos tagging and NLTK for grammar parsing and tree generation.
