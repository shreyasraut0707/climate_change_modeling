# Climate Change Social Media Engagement Analysis

A machine learning project for my internship that analyzes climate change discussions on social media to predict engagement patterns.

## Project Overview

This project uses data science and machine learning to:
- Analyze climate change social media posts
- Predict engagement metrics like likes and comments
- Understand what makes content engaging
- Build predictive models using text features

## Features

- Data Analysis: Exploratory analysis of climate change social media data
- Text Feature Engineering: Extracting useful features from post text
- Machine Learning Models: 
  - Linear Regression
  - Random Forest
  - Gradient Boosting
  - Neural Networks
- Visualizations for data exploration and model evaluation
- Scenario analysis for different content types

## Project Structure

```
Climate_Change/
|
|-- Climate_Change_Modeling.ipynb   # Main notebook with full analysis
|-- climate_nasa (1).csv            # Dataset
|-- experiment_results_summary.csv  # Model results
|-- requirements.txt                # Dependencies
|-- .gitignore
|-- README.md
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/shreyasraut0707/climate_change_modeling.git
cd climate_change_modeling
```

2. Install required packages:

```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook Climate_Change_Modeling.ipynb
```

## Requirements

- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

See requirements.txt for the complete list.

## Dataset

The dataset contains social media posts about climate change with these columns:

- date: When the post was made
- likesCount: Number of likes
- profileName: User identifier
- commentsCount: Number of comments
- text: The actual post content

## Model Performance

Best model was Random Forest:

- MAE: 6.23 likes
- RMSE: 13.25 likes
- R2 Score: 0.269

Key findings:
- Text length is the most important predictor (36% importance)
- Comment count strongly correlates with engagement (32% importance)
- Longer posts get more engagement
- Posts with 50+ comments can get 20+ likes

## Usage

Open the Jupyter notebook and run all cells:

```python
# The notebook covers:
# 1. Data loading
# 2. Feature engineering
# 3. Model training
# 4. Predictions
# 5. Results
```

## Results

What I found:

1. Content Length Matters - Longer posts (400+ characters) get more engagement
2. Discussion Activity - Posts with active comments see way more likes
3. Sentiment - Positive words help with engagement
4. Predictability - About 27% accuracy with basic features

## Author

Shreyas Raut

GitHub: [@shreyasraut0707](https://github.com/shreyasraut0707)

## License

MIT License
