# NLP-Based-Reddit-Gaming-Analysis

This project explores the Gaming subreddit, one of the largest online communities for gamers.

The project aims to extract valuable insights from the posts and comments of the subreddit to understand the interests, preferences, and behaviors of the gamers in this community.

## Web Scrapping:

The data has been extracted from Reddit with the help of RedditExtractoR package.

## Data Collection:

Extracted the top 100 posts in the Gaming subreddit using functions such as find_thread_url and get_thread_content from the RedditExtractoR package.

## Natural Language Processing(NLP) Algorithms:

## 1. N-Gram Analysis:
  ## Steps: 
    Concatenate title and texts.
    Remove punctuation and special characters.
    Convert to lowercase
    Tokenization
    Remove stop words and user defined words.
    Stemming
    Generate bigram and trigram.
    Display top 10 bigram and trigram.
    
## 2. Topic Modeling Using Latent Dirichlet Allocation(LDA):
  ## Steps:
    Using the data from n-gram analysis, create a character vector.
    Create a document term matrix.
    Trial and error method to choose number of topics to run LDA.
    Identify top 10 terms in each topic.
    
## 3. Sentiment Analysis:
  ## Steps:
    Remove punctuations and special characters.
    Convert to lowercase
    Tokenization
    Remove stop words
    Stemming
    Converting the tokenized and preprocessed text back into character vectors.
    Afinn lexicon to get sentiment scores.
    
## Conclusion:

  Reddit's gaming communities provide a rich source of player feedback and insights, which can be harnessed using NLP techniques such as topic modeling, n-grams,
  and sentiment analysis. By applying these techniques to the vast amount of user-generated content, gaming companies can extract valuable information and turn it into   actionable tasks that can inform decision-making for video game companies. Through these methods, Reddit and other online forums can serve as crucial platforms for     understanding player preferences and improving video game development.
  
## Future Scope: 

  After sentiment analysis, a classification prediction model can be built that automatically classifies the comments into positive and negative comments. Topic         modeling can be used to identify themes that are relevant to a certain audience and develop content that is more likely to engage and convert customers.


## Contributors:

  Ashwathi Ajayan Nambiar (https://github.com/ashwathi28)
  
  Falgun Malhotra (https://github.com/FalgunMalhotra)
  
  Kshitij Jain (https://github.com/kshitij107)
  
  Mohammed Mafaz Nadherssa (https://github.com/mafazazhaar)
