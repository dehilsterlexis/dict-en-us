# Dictionary for US English
The purpose of this repository is to generate, augment, and improve an English dictionary for the United States for use with the [NLP ENGINE](https://github.com/VisualText/nlp-engine) 

## History
The current dictionary used in the [NLP ENGINE](https://github.com/VisualText/nlp-engine) and by [VisualText](https://github.com/VisualText) comes from [WordNet from Princeton](https://wordnet.princeton.edu/). WordNext hasn't been updated since 2012 or there about and the current VisualText english dictionary was created more than 10 years before that. So it is in need of updating. One of the current tasks is to parse the dictionary.kb files to generate the raw dictionary data.

## Organization of this Repository
There are several folders in this repository:
- **VisualText Analyzer Folder**: All analyzers used to process or create dictionary data are found here.
- **Raw Data Folder**: Text files containing the raw data from which dictionaries can be generated using analyzers in the Analyzer Folder

## Short Term Goals
Short term goals for the English US dictionary:
- update and enhance the vocabulary
- number values
- gender
- other syntactic features like count etc.

## Text Repository
The purpose of the text repository is to

## Long Term Goals
- create a dictionary where each meaning for each word is deliniated
- create a faster dictionary lookup in the [NLP ENGINE](https://github.com/VisualText/nlp-engine)
