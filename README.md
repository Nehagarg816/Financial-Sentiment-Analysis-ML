# Financial-Sentiment-Analysis - Invest smarter with sentiments

<h3>Machine Learning</h3>
<p>A Machine Learning Project to predict the sentiments (positive, negative, or neutral) on real-time financial news headlines through unsupervised textual data of big tech companies using NLTK, K-Means Clustering Algorithm, and LSTM RNN and thus performing the mismatch or divergence between both the models.</p>
<h3>Come, Visit the Site for a Better Choice of Stock Investment!&#127881;</h3>

# Tech Stack<br>
<details>
  <summary>Data Collection</summary>  <br>
  
  > Python's BeautifulSoup module is used to scrape real-time financial news data from finviz.
  > Following that, the headlines are cleaned and prepared for analysis.

</details>

<details>
  <summary>Preprocessing</summary>  <br>
  
  > Lemmatization and stopword elimination are two preprocessing techniques used on the headlines to get the data ready for sentiment analysis.

</details>


  # Analysis Techniques<br>
<details>
<summary>KMeans Clustering</summary>  <br>

  > CountVectorizer is used to create the bag of words model.

  > used to group similar data points together in a process known as clustering. There are three clusters for sentiments like <b>Positive, Negative, and Neutral</b>.

  > Results are visualized using matplotlib.
  <img src="https://github.com/Nehagarg816/Financial-Sentiment-Analysis-ML/assets/111566521/9c5ce2ef-a0fa-41d8-85df-4c0264501cec" alt="image" width=500/>


</details>

<details>
<summary>Vader lexicon NLTK</summary>  <br>
  
  > A suite of libraries and programs for symbolic and statistical natural language processing (NLP) for English written in the Python programming language. It supports classification, tokenization, parsing, and semantic reasoning functionalities.

  > Sentiment analysis is done using the NLTK library, more especially the VADER sentiment analyzer. Headlines are categorised as good, negative, or neutral based on the computation of sentiment scores.


</details>

<details>
<summary>LSTM RNN(Recurrent Neural Network)</summary>  <br>

  > A type of RNN with higher memory power to remember the outputs of each node for a more extended period to produce the outcome for the next node efficiently.
  
  > The preprocessed data is used to train an LSTM RNN model for more sophisticated sentiment analysis. Based on the patterns that were learned from the text input through K-Means clustering, the model classifies attitudes as positive, negative, or neutral, thereby confirming its predictions.

</details>

<h2>Features</h2>
<ul>
  <li>You can sign-up or log-in here to start creating your listings if you want others to visit the place and have the same fun.
  <br><br>
    <img src="https://github.com/Nehagarg816/Wanderlust/assets/111566521/82b5e05d-9476-417e-a09f-c4decd3f6503" alt="listing" width="550">
  </li>
  <li>Here you can create your listing and upload pictures.
    <br><br>
    <img src="https://github.com/Nehagarg816/Wanderlust/assets/111566521/33403274-8b99-4c5b-b88f-c54ba5782b57" alt="listing" width="550">
  </li>
  <li>You can explore the broader view of listings of other users and select your destinations.
    <br><br>
    <img src="https://github.com/Nehagarg816/Wanderlust/assets/111566521/4423a1f5-58c8-43ef-83e3-fff1c46d07fa" alt="listing" width="550">
  </li>
  <li>You can leave ratings and reviews on listing of other users.
  <br><br>
    <img src="https://github.com/Nehagarg816/Wanderlust/assets/111566521/728ef434-2b52-41eb-b349-07f7ceae01ab" alt="listing" width="550">
  </li>

</ul>

<h3>Deployment</h3>
<h5>Deployment is done using Streamlit</h5>
<p>
  Website Link: https://nehagarg.streamlit.app/
</p>
