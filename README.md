# Climate Change Social Media Engagement Analysis

A machine learning project analyzing climate change discussions on social media to predict engagement patterns and understand public sentiment.

## 📊 Project Overview

This project uses data science and machine learning techniques to:
- Analyze climate change-related social media posts
- Predict engagement metrics (likes, comments)
- Extract insights about content characteristics that drive engagement
- Build predictive models using text features and engagement patterns

## 🚀 Features

- **Data Analysis**: Comprehensive exploratory data analysis of climate change social media data
- **Text Feature Engineering**: Extract meaningful features from text content
- **Machine Learning Models**: Multiple ML algorithms including:
  - Linear Regression
  - Random Forest
  - Gradient Boosting
  - Neural Networks (with hyperparameter tuning)
- **Visualization**: Rich visualizations for data exploration and model evaluation
- **Scenario Analysis**: Predict engagement for different content types

## 📁 Project Structure

```
Climate_Change/
│
├── Climate_Change_Modeling.ipynb   # Main Jupyter notebook with full analysis
├── climate_nasa (1).csv            # Dataset (social media posts)
├── experiment_results_summary.csv  # Model performance results
├── requirements.txt                # Python dependencies
├── .gitignore                      # Git ignore file
└── README.md                       # This file
```

## 🛠️ Installation

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

## 📦 Requirements

- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

See `requirements.txt` for complete list with versions.

## 🔍 Dataset

The dataset contains social media posts related to climate change with the following features:
- **date**: Post timestamp
- **likesCount**: Number of likes received
- **profileName**: User profile identifier
- **commentsCount**: Number of comments
- **text**: Post content

## 📈 Model Performance

Best performing model: **Random Forest**
- MAE: 6.23 likes
- RMSE: 13.25 likes
- R² Score: 0.269

### Key Insights:
- Text length is the most important predictor (36% importance)
- Comment count strongly correlates with engagement (32% importance)
- Longer, more detailed posts generate higher engagement
- Viral discussions (50+ comments) can generate 20+ likes

## 🎯 Usage

Open the Jupyter notebook and run cells sequentially:

```python
# The notebook includes:
# 1. Data loading and exploration
# 2. Feature engineering
# 3. Model training and evaluation
# 4. Scenario-based predictions
# 5. Results visualization
```

## 📊 Results

The analysis reveals:
1. **Content Length Matters**: Longer posts (400+ characters) get significantly more engagement
2. **Discussion Activity**: Posts with active comment sections see 10x more likes
3. **Sentiment Impact**: Positive sentiment words contribute to higher engagement
4. **Predictability**: Engagement can be predicted with ~27% accuracy using basic features

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 👨‍💻 Author

**Shreyas Raut**
- GitHub: [@shreyasraut0707](https://github.com/shreyasraut0707)

## 📝 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- NASA climate data sources
- Open source data science community
- Social media platforms for public data access

---

⭐ If you find this project useful, please consider giving it a star!
