# Disease Tweets Analysis

## Introduction
In this project, I aim to analyze tweets related to four diseases: AIDS/HIV, cancer, Corona (COVID-19), and diabetes. The analysis involves preprocessing the tweets, extracting key information, and deriving insights through natural language processing (NLP) techniques.

## Data Files
- Four files containing tweets related to the diseases, each categorized by specific keywords.

## Preprocessing
- Remove user mentions and the word "LINK@" from the tweets.
- Preserve social media symbols as individual words to avoid separation into meaningless signs.

## Parts of Speech Analysis
### a. Grammatical Analysis using Spacy
- Utilize the Spacy package for grammatical analysis.
- Ignore stop words, perform lemmatization, and filter words based on the English dictionary.
- 
### b. Most Common Words 
- Report the 20 most common words for each disease.
- Discuss the relevance and value of the results.

### c. Most Common Adjective Words 
- Identify the 20 most common adjective words for each disease.
- Evaluate the logical and meaningful aspects of the results.

### d. Most Common Verbs
- Extract the 20 most common verbs for each disease.
- Provide insights into the logical and meaningful implications of the results.

### e. Most Common Noun Words 
- Analyze the 20 most common noun words for each disease.
- Discuss the sense and meaningfulness of the results.

## Parsing 
### a. Dependency Parsing Function
- Implement a function for checking words directly related to the disease names in tweets.
- Convert verbs to their base forms (lemmas) and summarize the 10 common verbs along with their relative frequency for each disease.
- Discuss differences between diseases and compare with results from section d of question 2.

### b. Most Common Adjective Heads for Disease Names 
- Find the adjectives for which the disease name is the most common head.
- Discuss differences between diseases and compare with results from section c of question 2.

## Conclusion
- Summarize key findings from the analysis.
- Reflect on any variations between diseases and the reasons behind them.

## How to Submit
- The code must be submitted in a Jupyter notebook file.
- Include a text file with the results and their discussion.
