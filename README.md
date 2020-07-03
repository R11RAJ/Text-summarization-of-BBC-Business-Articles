# Text-summarization-of-BBC-Business-Articles
Summarizing BBC business articles using Extractive and Abstractive summarizers.

# Datasets used
BBC business articles withs its respective summaries.

# Dependencies
Sumy library
Textblob library

# Text Representation
Plain text parsing

# Text summarization
<ul>
<li>Extractive Summarizer : Text Rank </li>
<li>Abstractive Summarizer : Lex Rank</li>
<li>Sentence counts taken are 10,15,20,25</li>
</ul>

# Performance Metrics
Rouge 1 and Rouge 2 scores.

Best scores for Lex rank:
<ul>
  <li>For sentence count: 25</li>
  <li>Average Rouge 1 score: 0.9927635451570361</li>
  <li>Average Rouge 2 score: 0.9902403055537793</li>
</ul>

Best scores for Text rank:
<ul>
  <li>For sentence count: 25</li>
  <li>Average Rouge 1 score: 0.9965085581123175</li>
  <li>Average Rouge 2 score: 0.9950434965358156 </li>
</ul>


