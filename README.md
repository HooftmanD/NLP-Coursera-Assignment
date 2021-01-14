# Task 0 

__What do the data look like?__
A data set of blogs, news articles and tweets in four different languages. The text seems to contain random sentences and connected sentences with words structures that seem logical. It also contains structures like: "So ...", emoticons and all caps sentences like "HAHAHAHAHAHA". 

__Where do the data come from?__
The data set was provided by SwiftKey. A company creating downloadable keyboards for Android and IOS with predictive capabilities. The corpus is web scraped and each entry is stored per line. It is also anonymise and half the content is removed so we do not know where the data came from.

__Can you think of any other data sources that might help you in this project?__
More well written and semi-structured data like books, papers and articles. Data sets containing tokenized words.

__What are the common steps in natural language processing?__
1. Tokenization. 
2. Removing relatively useless words like "and", "the" or "off". 
3. Removing pre- and post-fixes to words that do not add much meaning like "play" from "playing" and not "new" from "news".
4. Standardizing by putting words in the same tense like "went" to "go" and synonyms in a uniform way like "joyful" to "happy".
5. Topic modelling by identifying groups of words related to a topic, this can be done by for example a semi-supervised learning algorithm.

__What are some common issues in the analysis of text data?__
Many languages are very complex because they have different types of characters, structures and meanings. 

__What is the relationship between NLP and the concepts you have learned in the Specialization?__
A large part of NLP is cleaning the data, using it to train a predictive model and testing it using a test set. It is also useful to integrate into a application.

# Task 2

__Some words are more frequent than others - what are the distributions of word frequencies? ___

__What are the frequencies of 2-grams and 3-grams in the dataset?__

__How many unique words do you need in a frequency sorted dictionary to cover 50% of all word instances in the language? 90%? ___

___How do you evaluate how many of the words come from foreign languages? ___

___Can you think of a way to increase the coverage -- identifying words that may not be in the corpora or using a smaller number of words in the dictionary to cover the same number of phrases? ___

# Resources used:
- https://en.wikipedia.org/wiki/Natural_language_processing
- https://www.jstatsoft.org/article/view/v025i05
- https://towardsdatascience.com/your-guide-to-natural-language-processing-nlp-48ea2511f6e1