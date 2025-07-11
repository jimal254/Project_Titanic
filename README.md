# Titanic Survival Analysis Project

![RMS Titanic](./Images/RMS.jpeg)

## Project Overview

This project explores the Titanic dataset to analyze the key factors that influenced passenger survival during the tragic RMS Titanic shipwreck. The dataset provides details such as passenger class, age, gender, fare, and other features.

Our goal was to perform a comprehensive data analysis and apply various statistical methods, including:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Probability distributions
- Hypothesis testing (Chi-Square, ANOVA, A/B Testing)
- Correlation and Covariance analysis
- Regression modeling

This analysis was conducted as part of our Phase 2 group project at Moringa School.

---

## Repository Structure

Project_Titanic/
├── Datasets/
│   ├── titanic.csv                # Original Titanic dataset
│   └── cleaned_titanic.csv        # Cleaned dataset after preprocessing
│
├── Images/
│   └── RMS.jpeg                   # Titanic RMS image used in README
│
├── Notebooks/
│   └── titanic_analysis.ipynb     # Main analysis notebook
│
├── Presentations/
│   └── (To be added)              # Slide decks or exports go here
│
├── README.md                      # Project documentation
└── .gitignore                     # Files/folders to exclude from version control


## Getting Started

To set up the project locally, follow the instructions below.

### 1. Clone the Repository

```bash
git clone https://github.com/jimal254/Project_Titanic.git
```
```bash
cd Project_Titanic
```
2. Set Up the Environment
Create and activate a virtual environment:

```bash
python -m venv learn-env
source learn-env/bin/activate  # On Windows: learn-env\Scripts\activate
```
### Install dependencies:


```bash
pip install -r requirements.txt
```
3. Run the Jupyter Notebook
Launch the analysis:

jupyter notebook titanic_analysis.ipynb
The notebook contains all sections of the analysis, including:

- Business Understanding

- Data Understanding

- Data Cleaning

- Exploratory Analysis

- Statistical Testing

- Regression Modeling

- Final Insights and Conclusions

**Branching Strategy** 

We used Git and GitHub to manage collaboration. Important branches include:

- main – Production-ready code

- Night_Notebook – Core statistical analysis

- Diana-Presentation – Final documentation and visuals

To switch to a branch:

```bash
git checkout Presentation
```
## Useful Links


**Tableau**
https://public.tableau.com/app/profile/mathews.odongo/viz/titanic_project_17486184752920/Dashboard1

Titanic dataset on Kaggle:
https://www.kaggle.com/competitions/titanic/data

## License
 **None**
 
This project is intended for academic and educational purposes only.


