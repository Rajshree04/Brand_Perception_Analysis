# Brand_Perception_Analysis

## Project Overview
Brand Perception Analysis is a project aimed at understanding public sentiment towards a brand by analyzing comments on its YouTube videos. The primary goal is to extract and classify user sentiments—positive, negative, or neutral. By leveraging Natural Language Processing (NLP) and machine learning techniques, this project provides valuable insights into consumer perceptions, helping brands identify strengths and areas for improvement.

## Technologies Used
- **Programming Language**: Python 3.x
- **Libraries**:
  - `pandas` for data manipulation
  - `numpy` for numerical computations
  - `nltk` for natural language processing tasks
  - `scikit-learn` for machine learning algorithms and model evaluation
  - `vaderSentiment` for sentiment analysis
- **Tools**:
  - Jupyter Notebook for interactive development
  - Selenium for web scraping YouTube comments
- **Operating System**: Windows 10 or Linux

## Setup Instructions
To set up the project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/brand-perception-analysis.git
    cd brand-perception-analysis
    ```

2. **Install the required Python libraries:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up your environment:**
    - Ensure that you have Python 3.x installed.
    - If scraping new data, ensure Selenium and the appropriate WebDriver (e.g., ChromeDriver) are installed.

4. **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    Open the notebook and execute the cells to perform the analysis.

## Usage Instructions
To use the project:

1. **Data Collection**: If you need to scrape new comments, use the Selenium script provided to collect comments from YouTube.
2. **Data Preprocessing**: Run the preprocessing scripts to clean and prepare the data for analysis.
3. **Sentiment Analysis**: Use the provided notebook to perform sentiment analysis on the comments. The analysis uses VADER for sentiment classification and supports oversampling to balance the dataset.
4. **Model Training and Evaluation**: Train machine learning models (Decision Tree, Random Forest, SVM) using the provided scripts. Hyperparameter tuning is available via grid search.
5. **Ensemble Model**: Evaluate the ensemble model, which combines predictions from the three classifiers to achieve higher accuracy.
