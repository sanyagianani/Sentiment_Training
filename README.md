# Sentiment Training Model

This repository contains a Jupyter Notebook for training and evaluating a sentiment analysis model on financial headlines.

# Overview
The notebook `Sentiment_Training.ipynb` walks through:
- Loading and preparing sentiment-labeled datasets
- Cleaning and preprocessing text
- Training a machine learning model for sentiment classification
- Evaluating model accuracy and performance

# Requirements
Install dependencies:
```bash
pip install -r requirements.txt
```

Minimal dev dependencies included in `requirements.txt`:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter
- nltk


# How to Run Locally
1. Unzip the project and `cd` into the folder:
   ```bash
   unzip Sentiment-Training.zip -d .
   cd Sentiment-Training
   ```
2. Create a virtual environment and install:
   ```bash
   python -m venv .venv
   source .venv/bin/activate    # macOS/Linux
   .\.venv\Scripts\activate  # Windows PowerShell
   pip install -r requirements.txt
   ```
3. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
4. Open `Sentiment_Training.ipynb` and run the cells.

## ▶️ How to Push to GitHub (quick)
- Option A (web): Create a repo on GitHub, then drag-and-drop the zip contents or individual files into the repo via **Add file → Upload files**.
- Option B (git): See the instructions below in the companion `HOW_TO_PUSH.md` or follow the steps in the project homepage.

## ⚠️ Notes
- If your dataset or model files are large (>100 MB), consider storing them outside the repo or use Git LFS.
- Clean the notebook outputs if you prefer smaller file size: in Colab use `Edit → Clear all outputs` before saving.

## 📜 License
MIT License — feel free to use and adapt.

## Author
Your Name — update the `README.md` with your name and GitHub link.
