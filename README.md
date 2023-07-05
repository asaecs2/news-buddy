# news-buddy

The project involves the following components:

1. News Articles Retrieval:
   - Utilizes the News API to fetch top headlines from a specific news source (in this case, 'google-news-in').
   - The user provides a search query, and the script collects relevant articles based on that query.

2. Text Processing and Embedding:
   - Implements data cleaning and preprocessing functions to remove special characters and convert text to lowercase.
   - Utilizes the BERT model and its associated tokenizer to encode the user's search query and article titles into numerical embeddings.

3. Similarity Calculation:
   - Utilizes the cosine similarity metric to calculate the similarity scores between the user's query and each article title.
   - Sorts the articles based on the similarity scores to identify the most relevant ones.

4. Chatbot Integration:
   - Implements a Chat class that uses the OpenAI API for generating responses to user messages.
   - Enables users to interact with a coding tutor bot by asking queries related to the recommended articles.

5. User Interface:
   - Presents the top recommended articles to the user, including their titles and URLs.
   - Facilitates user interaction by allowing them to ask queries or proceed to the next article.

Overall, this project combines news article retrieval, text processing, similarity calculation, and chatbot integration to provide users with relevant articles based on their search queries.
