# Amazon Fine Food Reviews - Sentiment Analysis and Product Categorization

This project explores and analyzes user reviews from the **Amazon Fine Food Reviews** dataset. It includes two key Jupyter notebooks that work together to assess the sentiment of reviews and categorize them into meaningful product categories.

## Notebooks

### 1. `Amazon fine food reviews - sentiment analysis.ipynb`

**Purpose**:  
This notebook focuses on **sentiment classification** of individual words found in the reviews.

**Main Features**:
- Cleans and processes text data.
- Identifies and classifies frequently used words into three sentiment groups:
  - `Positive`
  - `Negative`
  - `Neutral`
- Provides an overall sentiment score based on the words' polarity.

**Goal**: To understand the general tone of the reviews using a word-level sentiment approach.

---

### 2. `Amazon fine food reviews - sentiment analysis and product categorization.ipynb`

**Purpose**:  
This notebook extends the sentiment analysis by mapping each review to a specific **product category** and aggregating sentiment at the category level.

**Main Features**:
- Categorizes reviews into 96 distinct **product groups** (e.g., Coffee, Chocolate, Dog Food, etc.).
- Aggregates overall sentiment for each product category.
- Helps identify which categories are most positively or negatively received by consumers.

**Goal**: To provide insights on customer sentiment across different food product types on Amazon.

---

## Technologies Used

- Python (Pandas, NLTK, Scikit-learn)
- Jupyter Notebook
- Text preprocessing and NLP techniques
- Sentiment analysis using lexicon-based methods

---

## Dataset

- [Amazon Fine Food Reviews Dataset](https://www.kaggle.com/snap/amazon-fine-food-reviews)  
  Contains over 500,000 food reviews from Amazon spanning several years.

---

## Use Cases

- Identify customer satisfaction trends across food product categories.
- Highlight top-performing and poorly received food items.
- Support product development and marketing strategies through review insights.

---

## How to Use

1. Clone the repository.
2. Install the required libraries from `requirements.txt` (optional).
3. Run the notebooks in sequence:
   - Start with sentiment classification (`sentiment analysis.ipynb`)
   - Then run product categorization (`sentiment analysis and product categorization.ipynb`)

