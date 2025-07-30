# 🧑‍🔬 Kaggle: Predict the Introverts from the Extroverts

Welcome to the most insightful, data-driven personality prediction challenge!  
This repository is dedicated to solving the problem of classifying individuals as introverts or extroverts based on behavioral data, using advanced machine learning techniques and thorough data analysis.

---

## 🚩 Problem Overview

Given a person's behavioral data (such as time spent alone, stage fear, social event attendance, etc.), can we accurately predict if they're an **Introvert** or an **Extrovert**?  
This is a **binary classification** problem, perfect for both beginners and experienced data scientists who love practical, interpretable ML.

---

## 📂 Repository Structure

```
├── train.csv                 # Training dataset with labels
├── test.csv                  # Test dataset for inference
├── sample_submission.csv     # Sample format for Kaggle submission
├── submission.csv            # Example submission output
├── ML model training.ipynb   # End-to-end model training & EDA notebook
├── Inference.ipynb           # Inference & feature engineering notebook
├── README.md                 # 📄 You're here!
```

---

## 🔍 Data Description

The datasets include the following features:

| Feature                    | Description                                          |
|----------------------------|-----------------------------------------------------|
| id                         | Unique identifier                                   |
| Time_spent_Alone           | Hours spent alone per day                           |
| Stage_fear                 | Stage fear (Yes/No)                                 |
| Social_event_attendance    | Social events attended per month                    |
| Going_outside              | Times gone outside per week                         |
| Drained_after_socializing  | Feeling drained after socializing (Yes/No)          |
| Friends_circle_size        | Size of close friend circle                         |
| Post_frequency             | Social media posts per week                         |
| Personality                | Target variable (Introvert/Extrovert, in train.csv) |

---

## ✨ Notebooks

**1. ML model training.ipynb**  
- Problem definition, metric explanation, and in-depth EDA  
- Data cleaning, visualization, and feature engineering  
- Multiple ML models trained, tuned, and evaluated  
- Easy to follow, with annotated code and plots

**2. Inference.ipynb**  
- Loads the test data, applies feature engineering, and data cleaning  
- Imputation, outlier handling, encoding, scaling, and feature creation  
- Ready for model inference and Kaggle submission generation

---

## 🚀 How to Use

1. **Clone the repo**
    ```bash
    git clone https://github.com/TJ-programmer/Kaggle-Predict-the-Introverts-from-the-Extroverts.git
    cd Kaggle-Predict-the-Introverts-from-the-Extroverts
    ```

2. **Install dependencies**
    *(Recommended: Use a virtual environment)*
    ```bash
    pip install -r requirements.txt  # If requirements.txt is available
    # Or manually install: pandas, numpy, matplotlib, seaborn, scikit-learn, etc.
    ```

3. **Explore & Run Notebooks**
    - Open `ML model training.ipynb` for EDA, training, and model selection.
    - Open `Inference.ipynb` to run predictions on test data.

4. **Submit to Kaggle**
    - Generate your predictions and format them as in `sample_submission.csv` or `submission.csv`.

---

## 📈 Results & Insights

- Extensive EDA shows key behavioral features strongly correlate with personality.
- Feature engineering includes new features like `social_balance` and boolean indicators.
- Imputation and outlier handling ensure robust data quality.
- Model performance visualized and explained for full transparency.

---

## 🤝 Contributing

Want to add new models, features, or visualizations?  
Feel free to fork, open pull requests, or start discussions via Issues!  
All constructive feedback and collaboration are welcome.

---

## 📚 References

- [Kaggle Competition](https://www.kaggle.com/competitions/playground-series-s5e7)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)

---

## 💬 Contact

Questions? Ideas?  
Open an [issue](https://github.com/TJ-programmer/Kaggle-Predict-the-Introverts-from-the-Extroverts/issues) or connect via [GitHub](https://github.com/TJ-programmer).

---

> *Uncover the science of personality — one dataset at a time!*  
> *Let’s make ML explainable, practical, and fun!*
