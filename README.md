**AMD, NVIDIA, and Intel – Consumer Sentiment Analysis**

This project explores and compares consumer sentiment toward the top three chip manufacturers — AMD, NVIDIA, and Intel — using data sourced from Reddit and YouTube. The goal is to uncover user opinions, brand strengths, and community trends through various NLP and network analysis techniques.

📌 Objective
To analyse public perception of AMD, NVIDIA, and Intel using unstructured user comments and identify which brand garners the most positive sentiment. The project also examines common discussion themes, aspect-based sentiment, and community behavior to understand brand perception in depth.

📥 Data Collection
- Extracted 80,000+ comments from Reddit threads and YouTube videos related to the three brands

- Focused on posts discussing product performance, pricing, customer support, and loyalty

- Used Python APIs and web scraping to collect and store text data in structured format

🧠 Key Techniques Used
- Sentiment Analysis: Classified comments as positive, neutral, or negative using VADER and TextBlob

- Aspect-Based Sentiment Analysis: Extracted opinions tied to specific product attributes like performance, pricing, and availability

- Word Clouds: Created separate visualisations for positive and negative terms for each brand

- Topic Modeling: Applied Latent Dirichlet Allocation (LDA) to uncover key themes discussed for each brand

- Community Detection (Network Graphs):

Built a user-comment network graph to analyse community structure

Detected clusters of brand followers and their discussion overlap

Found that many users interested in AMD, NVIDIA, and Intel followed similar subreddit communities, revealing shared interests

🏁 Key Insights
- NVIDIA showed the highest proportion of positive sentiment, particularly around performance and innovation

- AMD received praise for price-to-performance value, especially in the budget and mid-range segments

- Intel saw a mix of legacy loyalty and criticism regarding pricing and innovation pace

- Network analysis showed cross-brand engagement: users often participated in multiple brand subreddits, indicating brand comparison is common among enthusiasts

- Topic modeling revealed shared themes across brands: gaming, thermal efficiency, pricing, and hardware compatibility

🧰 Tools & Libraries
- Python

- pandas, nltk, spacy, textblob, vaderSentiment for NLP

- gensim for topic modeling (LDA)

- matplotlib, seaborn, wordcloud for data visualization

- networkx, pyvis for community detection and graph visualization

- Reddit API (PRAW) and YouTube Data API for data collection
