# NewProject
 Resume Selection using NLP and Machine Learning
This project is designed to identify and flag resumes based on their content using various NLP techniques and machine learning. It involves dataset cleaning, preprocessing, and exploratory data analysis (EDA) on a collection of resumes, with the goal of classifying them into flagged or not_flagged categories.

# 📁 Project Structure
kotlin
Copy
Edit
.
├── data/
│   └── resume_data.csv
├── notebooks/
│   └── Resume_Selection.ipynb
├── README.md
└── requirements.txt
🔍 Features
Text preprocessing (cleaning, tokenization, stopword removal)

# Text vectorization

Visualization (word clouds, frequency distributions)

Machine learning classification

Binary label mapping (flagged → 1, not_flagged → 0)

# 📦 Libraries Used
pandas

numpy

matplotlib

seaborn

nltk

gensim

sklearn

wordcloud

# Install them all at once:

bash
Copy
Edit
pip install -r requirements.txt
🧪 How to Run
# Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
# Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook notebooks/Resume_Selection.ipynb
# 📊 Dataset
Located in the data/ folder:

resume_data.csv: Contains resume_id, class, and resume_text.

# 📈 Sample Workflow
Import and install required libraries

Load and explore dataset

Clean and preprocess text

Label encode the target column

Create a "cleaned" column for vectorization

Train a classifier and evaluate results

# 👨‍💻 Author
Shreya Gupta
