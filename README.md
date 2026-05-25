<div align="center">

<h1>Sentiment Analysis on Product Reviews</h1>

<p>
A Natural Language Processing project that analyzes Amazon product reviews, classifies customer sentiment, compares sentiment with star ratings, and visualizes review patterns using sentiment scoring, word clouds, and text analytics.
</p>

<p>
<a href="https://codeayan.com" target="_blank"><strong>Visit Codeayan</strong></a> •
<a href="https://codeayan.com/read" target="_blank"><strong>Read Articles</strong></a> •
<a href="https://codeayan.com/projects" target="_blank"><strong>See Other Projects</strong></a> •
<a href="https://codeayan.com/vader-sentiment-analysis-project/" target="_blank"><strong>Understand This Project</strong></a>
</p>

<hr>

</div>

<h2>Project Overview</h2>

<p>
This project focuses on building a sentiment analyzer for product reviews. The analyzer classifies reviews into <strong>positive</strong>, <strong>negative</strong>, and <strong>neutral</strong> categories using sentiment scoring techniques.
</p>

<p>
The project also compares predicted sentiment labels with customer star ratings to identify mismatches between written review text and numerical ratings.
</p>

<h2>Dataset</h2>

<table>
  <tr>
    <th>Dataset Name</th>
    <td>Amazon Product Reviews Dataset</td>
  </tr>
  <tr>
    <th>Source</th>
    <td>
      <a href="https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews" target="_blank">
        Amazon Fine Food Reviews on Kaggle
      </a>
    </td>
  </tr>
  <tr>
    <th>Description</th>
    <td>500k+ Amazon food reviews with ratings and text.</td>
  </tr>
</table>

<h2>Core Concepts Used</h2>

<table>
  <tr>
    <td><strong>NLTK</strong></td>
    <td>Used for NLP preprocessing such as stopword removal.</td>
  </tr>
  <tr>
    <td><strong>TextBlob</strong></td>
    <td>Included as part of the sentiment analysis concept stack.</td>
  </tr>
  <tr>
    <td><strong>VADER</strong></td>
    <td>Used for generating sentiment intensity scores.</td>
  </tr>
  <tr>
    <td><strong>Word Clouds</strong></td>
    <td>Used to visualize common words in positive and negative reviews.</td>
  </tr>
  <tr>
    <td><strong>NLP Preprocessing</strong></td>
    <td>Used to clean and prepare review text for analysis.</td>
  </tr>
  <tr>
    <td><strong>Sentiment Scoring</strong></td>
    <td>Used to classify reviews based on compound sentiment scores.</td>
  </tr>
</table>

<h2>Project Task</h2>

<p>
Build a sentiment analyzer to classify Amazon product reviews as:
</p>

<ul>
  <li><strong>Positive</strong></li>
  <li><strong>Negative</strong></li>
  <li><strong>Neutral</strong></li>
</ul>

<p>
Then compare the generated sentiment labels with the original star ratings to identify mismatches.
</p>

<h2>Workflow</h2>

<table>
  <tr>
    <th>Step</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><strong>1</strong></td>
    <td>Load a 10k sample using <code>pandas read_csv</code> with <code>nrows=10000</code>.</td>
  </tr>
  <tr>
    <td><strong>2</strong></td>
    <td>Clean review text by converting to lowercase, removing HTML tags, punctuation, and stopwords using NLTK.</td>
  </tr>
  <tr>
    <td><strong>3</strong></td>
    <td>Apply <code>VADER SentimentIntensityAnalyzer</code> to generate compound sentiment scores.</td>
  </tr>
  <tr>
    <td><strong>4</strong></td>
    <td>Classify reviews into Positive, Negative, and Neutral categories based on compound score threshold.</td>
  </tr>
  <tr>
    <td><strong>5</strong></td>
    <td>Compare sentiment labels with star ratings and identify mismatches.</td>
  </tr>
  <tr>
    <td><strong>6</strong></td>
    <td>Generate separate word clouds for positive and negative reviews.</td>
  </tr>
  <tr>
    <td><strong>7</strong></td>
    <td>Plot the distribution of sentiment scores by star rating using a boxplot.</td>
  </tr>
  <tr>
    <td><strong>8</strong></td>
    <td>Find the top 20 most common positive and negative words using <code>Counter</code>.</td>
  </tr>
</table>

<h2>Expected Project Outputs</h2>

<ul>
  <li>Cleaned review text</li>
  <li>VADER compound sentiment scores</li>
  <li>Positive, Negative, and Neutral sentiment labels</li>
  <li>Comparison between sentiment labels and star ratings</li>
  <li>Mismatch analysis between review sentiment and rating</li>
  <li>Positive review word cloud</li>
  <li>Negative review word cloud</li>
  <li>Boxplot showing sentiment score distribution by star rating</li>
  <li>Top 20 common positive words</li>
  <li>Top 20 common negative words</li>
</ul>

<h2>Explore More on Codeayan</h2>

<table>
  <tr>
    <th>Resource</th>
    <th>Link</th>
  </tr>
  <tr>
    <td><strong>Website</strong></td>
    <td><a href="https://codeayan.com" target="_blank">codeayan.com</a></td>
  </tr>
  <tr>
    <td><strong>Read Articles</strong></td>
    <td><a href="https://codeayan.com/read" target="_blank">codeayan.com/read</a></td>
  </tr>
  <tr>
    <td><strong>See Other Projects</strong></td>
    <td><a href="https://codeayan.com/projects" target="_blank">codeayan.com/projects</a></td>
  </tr>
  <tr>
    <td><strong>Understand This Project</strong></td>
    <td><a href="https://codeayan.com/vader-sentiment-analysis-project/" target="_blank">VADER Sentiment Analysis Project</a></td>
  </tr>
</table>

<h2>About Codeayan</h2>

<p>
Codeayan is a learning platform focused on practical projects, analytics, artificial intelligence, data science, and real-world technical learning.
</p>

<p>
If you found this project useful, explore more articles and projects on 
<a href="https://codeayan.com" target="_blank"><strong>codeayan.com</strong></a>.
</p>

<hr>

<div align="center">

<h3>Sentiment Analysis on Product Reviews</h3>

<p>
Built as a practical NLP project using NLTK, TextBlob, VADER, word clouds, preprocessing, and sentiment scoring.
</p>

<p>
<a href="https://codeayan.com/vader-sentiment-analysis-project/" target="_blank">
<strong>Understand the full project on Codeayan</strong>
</a>
</p>

</div>
