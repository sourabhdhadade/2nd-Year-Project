# Bot Detection (Mini Project)

This project detects bots using machine learning and natural language processing techniques.
It processes data from multiple sources, trains models, and evaluates their performance.

## Datasets

* **dataspam.csv** – Contains labeled spam/bot detection data.
* **data file.csv** – Contains additional sample data for testing.

## Technologies Used

* **Python**
* Pandas, NumPy, Matplotlib, Seaborn
* scikit-learn (RandomForest, LogisticRegression)
* TextBlob (for text analysis)
* Selenium (for web automation and scraping)
* Requests (for HTTP requests)
* Joblib (for saving models)

## Installation

1. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn textblob selenium requests joblib
   ```

## Usage

1. Place `dataspam.csv` and `data file.csv` in the project folder.
2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Bots_Detection_mini_project.ipynb
   ```
3. Run the cells to train the model and evaluate results.

## Output

* Accuracy, precision, recall, and F1-score of the models.
* Confusion matrix and visualizations.
* Saved trained model for future use.

---
