# 🎵 Music Popularity Analysis

## 📌 Project Overview

This project analyzes **music popularity trends** using data-driven insights. The objective is to understand the factors influencing the success of a song and build models to predict a song's popularity.

## 📂 Project Structure

```
├── data/                 # Dataset files
├── notebooks/            # Jupyter Notebooks for analysis
├── src/                  # Python scripts for data processing & modeling
├── results/              # Outputs, visualizations, and reports
├── README.md             # Project documentation
├── requirements.txt      # Dependencies
```

## 🛠️ Installation

To run this project locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/yourusername/MusicPopularity.git
cd MusicPopularity

# Install dependencies
pip install -r requirements.txt
```

## 🔍 Data Exploration

- **Dataset Overview:** Includes song features such as **tempo, loudness, duration, genre, and popularity score**.
- **Missing Value Handling:** Address missing data using imputation techniques.
- **Feature Engineering:** Derived new features like tempo categories, loudness levels, etc.

## 📊 Machine Learning Models Used

- **Linear Regression**
- **Random Forest Regressor**
- **XGBoost Regressor**
- **Neural Networks**

### 📈 Model Evaluation Metrics

- **Mean Absolute Error (MAE)**
- **Root Mean Square Error (RMSE)**
- **R² Score**

## 📉 Data Visualization

- **Heatmaps** for correlation analysis
- **Histograms** for feature distributions
- **Scatter plots** to analyze relationships between song attributes

## 🚀 Running the Analysis

Launch the Jupyter Notebook:

```bash
jupyter notebook MusicPopularity.ipynb
```

## 🔗 References

- [Scikit-Learn Documentation](https://scikit-learn.org/stable/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Music Data Analysis Guide](https://towardsdatascience.com/music-data-analysis-guide)

## 🤝 Contributing

Contributions are welcome! Fork the repo and submit a pull request.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
