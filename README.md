# StackOverflow Developer Survey Analysis

A comprehensive data science project analyzing the StackOverflow Annual Developer Survey using the CRISP-DM methodology. This project explores developer trends, builds predictive models, and provides actionable insights about the software development industry.

## Project Overview

This project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework to analyze developer survey data and answer key business questions:

- **What are the most important features** that drive developer outcomes?
- **What unusual or creative insights** can we discover from the data?
- **How accurate** are our predictive models?
- **What future scenarios** can we predict using our trained models?

## Dataset

**Source**: StackOverflow Annual Developer Survey  
**Size**: 
**Features**: 
**Target Variable**: 

The StackOverflow Developer Survey is one of the largest and most comprehensive surveys of people who code around the world, providing insights into developer demographics, technologies, career satisfaction, and compensation.

## Methodology

Following the **CRISP-DM** process:

1. **Business Understanding**: Define prediction goals and success criteria
2. **Data Understanding**: Exploratory data analysis and quality assessment
3. **Data Preparation**: Cleaning, transformation, and feature engineering
4. **Modeling**: Train and evaluate multiple machine learning models
5. **Evaluation**: Assess model performance and business value
6. **Deployment**: Create actionable insights and recommendations

## Technologies Used

- **Python 3.9+**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib & Seaborn** - Data visualization
- **Scikit-learn** - Machine learning models and evaluation
- **Jupyter Notebook** - Interactive development and analysis
- **SciPy** - Statistical analysis

## Project Structure

```
stackoverflow-survey-analysis/
│
├── data/                          # Data files (not tracked in git)
│   ├── raw/                       # Original survey data
│   └── processed/                 # Cleaned and preprocessed data
│
├── notebooks/                     # Jupyter notebooks for analysis
│   ├── 01_exploratory_analysis.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_modeling.ipynb
│   └── 05_evaluation_insights.ipynb
│
├── src/                          # Source code for reusable functions
│   ├── data_processing.py
│   ├── visualization.py
│   └── modeling.py
│
├── models/                       # Trained model artifacts
│
├── reports/                      # Analysis reports and blog post
│   └── blog_post.md
│
├── requirements.txt              # Python dependencies
├── environment.yml              # Conda environment file
└── README.md                   # Project documentation
```

## Getting Started

### Prerequisites

- Python 3.9 or higher
- Conda (recommended) or pip for package management

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/dmarcano11/udacity-dsnd-project-1.git
   cd udacity-dsnd-project-1
   ```

2. **Create conda environment**
   ```bash
   conda env create -f environment.yml
   conda activate ml_env
   ```

   Or using pip:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the data**
   - Visit [StackOverflow Survey Data](https://insights.stackoverflow.com/survey)
   - Download the latest survey data
   - Place `survey_results_public.csv` in the `data/raw/` directory

4. **Run the analysis**
   ```bash
   jupyter notebook notebooks/01_exploratory_analysis.ipynb
   ```

## Key Findings

### Initial Discoveries

### Model Performance
- **Best Model**: [Model Name]
- **Accuracy**: [Performance Metric]
- **Key Features**: [Top predictive features]

## Blog Post

A detailed blog post explaining the analysis, methodology, and insights is available in `reports/blog_post.md`. The blog post is written for a general audience and covers:

- The story behind the data
- Key insights and surprises
- Model accuracy and reliability
- Creative predictions and scenarios
- Actionable recommendations


## Contact

**David Marcano**
- GitHub: [@dmarcano11](https://github.com/dmarcano11)
- LinkedIn: [David's LinkedIn](https://linkedin.com/in/dmarcano)
- Email: david11marcano@gmail.com

---

*This project is part of the Udacity data science nanodegree and demonstrates my proficiency in the complete data science pipeline from exploration and model development to sharing my findings via a blog post.*