# NLP-football-tweets

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contact](#contact)

## Features
### Sentiment Classification:
  - Classifies football-related tweets into three sentiments: positive, neutral, and negative.

### Data Preprocessing:
  - Handles:
    - Contractions and abbreviations removal.
    - Emoticons, URLs, and special characters cleanup.
    - Tokenization, stop-word removal, and case normalization.
    - Advanced techniques like stemming and lemmatization.

### Text Representation:
  - Implements Bag of Words (BoW), TF-IDF, and Bag of Bigrams for feature extraction.

### Visualization:
  - Generates word clouds to visualize frequently used terms in tweets.

### Machine Learning Models:
  - Experiments with Logistic Regression, Support Vector Machines (SVM), Random Forest, and Naive Bayes classifiers.

### Experimentation:
  - Multiple preprocessing and feature extraction combinations for model evaluation.
  - Detailed performance metrics like accuracy and classification reports.

## Installation

### Prerequisites  
- **Python**: Make sure you have Python 3.8 or higher installed.  
- **Libraries**: Required Python libraries are listed in `requirements.txt`.  

### Installation  

Follow these steps to set up the project locally:

1. Clone the repository:  
   ```bash
   git clone https://github.com/jinannisar/NLP-football-tweets.git

2. Navigate to the project directory: 
   ```bash
   cd project-name NLP-football-tweets

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

4. Install Jupyter (for running .ipynb files):
   ```bash
   pip install jupyter
   
5. Start Jupyter by running:
   ```bash
   jupyter notebook
   
## Usage

Once the project is set up, follow these steps to use the code:

1. **Run the Notebook**: Open the Jupyter notebook and run the individual cells to preprocess the data, train the models, and visualize the results.

2. **Sentiment Classification**: 
   - The notebook includes cells for running the sentiment classification model.
   - You can modify the data source or model parameters as needed.

3. **Data Preprocessing**: 
   - The preprocessing steps can be modified or extended to handle other types of data.

4. **Model Evaluation**: 
   - After training the models, you can evaluate their performance using metrics like accuracy, precision, recall, and F1-score.

5. **Visualization**: 
   - Word clouds and other visualizations are automatically generated based on the frequency of terms in the tweets.

## Contact

For any questions or feedback, feel free to reach out to the repository maintainer:  
**[Jinan Nisar](mailto:jinannisar02@gmail.com)**
