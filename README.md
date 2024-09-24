# News-Article-Insights
News Article Insights is a Python project that uses the NewsAPI to fetch articles on specific companies and keywords. It extracts content and performs text analysis, including sentiment analysis, named entity recognition, and topic modeling, to uncover trends and public sentiment, providing valuable insights into the media landscape.


## Overview

This project leverages the NewsAPI to fetch articles related to specific companies and keywords, extract their content, and perform various text analysis techniques. The primary goal is to gain insights into public sentiment and trending topics within the news articles.

## Features

- Fetch articles from the NewsAPI based on company and keyword searches.
- Extract and clean content from each article.
- Perform text analysis, including:
  - Word cloud generation
  - Visualization of the most common words
  - Sentiment analysis
  - Named entity recognition (NER)
  - Topic modeling using LDA

## Technologies Used

- Python
- Requests (for API calls)
- BeautifulSoup (for web scraping)
- NLTK (Natural Language Toolkit)
- SpaCy (for advanced NLP tasks)
- TextBlob (for sentiment analysis)
- Gensim (for topic modeling)
- Matplotlib & Seaborn (for data visualization)
- tqdm (for progress bars)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/news-article-analysis.git
   cd news-article-analysis
   ```

2. **Install the required packages**:
   Make sure you have Python installed. Then, run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download NLTK and SpaCy resources**:
   You can download the necessary resources using the following commands within a Python shell:
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   nltk.download('wordnet')

   import spacy
   spacy.cli.download("en_core_web_sm")
   ```

## Usage

1. **Run the main script**:
   Execute the main script to fetch articles and perform text analysis. You will be prompted to enter your NewsAPI key, the company name, the keyword to search for, and the number of articles you wish to fetch.
   ```bash
   python main.py
   ```

2. **Review the results**:
   After execution, the results will be saved to `article_results.txt`. You can also visualize the data through generated plots.

3. **Analysis**:
   The script generates:
   - A word cloud to visualize common words.
   - Bar plots for the top 20 most common words.
   - Sentiment analysis results printed to the console.
   - Named entities identified in the articles.
   - Topic modeling visualizations.

## Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, feel free to open an issue or submit a pull request.



## Acknowledgments

- [NewsAPI](https://newsapi.org/) for providing the news articles.
- Open-source libraries such as NLTK, SpaCy, Gensim, and others that facilitated the text analysis.

## Author

- Srikar Anudeep Remani  
  [LinkedIn Profile](https://linkedin.com/in/srikaranudeepremani)  
  [Email](mailto:remanisrikaranudeep@gmail.com)

```

