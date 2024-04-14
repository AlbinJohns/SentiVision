# SentiVision

SentiVision is a Python notebook for sentiment analysis on financial entities extracted from news articles. It leverages BERT models for Named Entity Recognition (NER) and sentiment analysis to provide insights into the sentiment surrounding various financial organizations.

## Usage

To use this notebook, follow these steps:

1. **Open in Colab**: Click on the [Open in Colab](https://colab.research.google.com/drive/1Dt1bKVszbSyfYA4Pb0icUP6zhy4mwWTf?usp=sharing) button to open the notebook in Google Colab.
   
2. **Install Dependencies**: Run the code cells to install required Python packages and modules.

3. **Input Data**: Choose one of the input methods:
   - Fetch news data by scraping CNBC website headlines.
   - Fetch data from uploaded files.

4. **View Sentences**: View the sentences fetched from the input data source.

5. **Making the Model**: Fetch BERT model tokenizer and weights for financial entity recognition.

6. **Extracting Organizations**: Display organizations with their sentences for further sentiment analysis.

7. **Sentiment Analysis**: Fetch Financial BERT for sentiment analysis on financial entities.

8. **Visualization Dashboard**: This code section defines two dictionaries (`positive_sentiments` and `negative_sentiments`) based on sentiment scores, sorts them, and then creates visualizations using bar charts and pie charts.

## Code Overview

- `SentiVision.ipynb`: The main Python notebook containing the code.
- `requirements.txt`: List of required Python packages.
- `data.txt`: Sample data file for demonstration purposes.

## Dependencies

- `pandas`
- `numpy`
- `transformers`
- `scipy`
- `matplotlib`
- `newspaper3k`
- `bs4`
- `lxml_html_clean`
- `requests`

## Acknowledgments

- This notebook was created as part of a project to analyze sentiment in financial news.
- Special thanks to the developers of the libraries and models used in this notebook.
