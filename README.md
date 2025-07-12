# Flight Price Prediction Model

A machine learning project to predict flight prices using various features such as airline, departure/arrival locations, flight duration, and booking timing.

## 📊 Project Overview

This project implements a flight price prediction system using machine learning techniques. The model analyzes historical flight data to predict ticket prices, helping users make informed decisions about when to book flights for the best deals.

## 🎯 Objectives

- Predict flight prices based on various features
- Identify key factors that influence flight pricing
- Provide insights into optimal booking strategies
- Compare different machine learning algorithms for price prediction

## 📁 Project Structure

```
FlightPrediction/
├── Flight_Predicition_Model.ipynb    # Main Jupyter notebook with complete analysis
└── README.md                         # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- Required Python packages (see Installation section)

### Installation

1. Clone or download this repository
2. Install required dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn kagglehub
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook Flight_Predicition_Model.ipynb
```

## 📋 Dataset

The project uses a flight price dataset that includes:

- **Airline**: Different airline companies
- **Date_of_Journey**: Travel date
- **Source**: Departure city
- **Destination**: Arrival city
- **Route**: Flight route details
- **Dep_Time**: Departure time
- **Arrival_Time**: Arrival time
- **Duration**: Flight duration
- **Total_Stops**: Number of stops
- **Additional_Info**: Extra flight information
- **Price**: Target variable (flight price)

## 🔬 Methodology

### 1. Data Collection & Loading
- Dataset acquisition using Kaggle API
- Initial data exploration and structure analysis

### 2. Exploratory Data Analysis (EDA)
- Statistical summary of the dataset
- Data visualization using matplotlib and seaborn
- Identification of patterns and trends in flight pricing

### 3. Data Preprocessing
- Handling missing values
- Feature engineering and extraction
- Data type conversions
- Categorical variable encoding

### 4. Feature Engineering
- Time-based feature extraction (hour, day, month)
- Duration parsing and conversion
- Route analysis and encoding
- Stop categorization

### 5. Model Development
- Multiple algorithm implementation and comparison
- Model training and validation
- Hyperparameter tuning
- Performance evaluation

### 6. Model Evaluation
- Accuracy metrics calculation
- Cross-validation
- Feature importance analysis
- Model comparison and selection

## 📈 Key Features

- **Data Visualization**: Comprehensive charts showing price distributions, trends, and correlations
- **Feature Engineering**: Advanced preprocessing techniques for optimal model performance
- **Multiple Models**: Implementation of various machine learning algorithms
- **Performance Metrics**: Detailed evaluation using appropriate regression metrics
- **Insights**: Clear interpretation of results and feature importance

## 🛠️ Technologies Used

- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib/Seaborn**: Data visualization
- **Scikit-learn**: Machine learning algorithms
- **Jupyter Notebook**: Interactive development environment
- **Kaggle API**: Dataset acquisition

## 📊 Results

The notebook provides:
- Detailed analysis of factors affecting flight prices
- Model performance comparisons
- Feature importance rankings
- Practical insights for flight booking decisions

## 🔍 Key Insights

Based on the analysis, the model reveals:
- Impact of different airlines on pricing
- Seasonal and temporal price variations
- Effect of booking timing on flight costs
- Relationship between flight duration and price
- Influence of number of stops on ticket prices

## 📝 Usage

1. Open the Jupyter notebook
2. Run cells sequentially to reproduce the analysis
3. Modify parameters or add new features as needed
4. Use the trained model to predict prices for new flight data

## 🤝 Contributing

Feel free to contribute to this project by:
- Adding new features or algorithms
- Improving data preprocessing techniques
- Enhancing visualizations
- Optimizing model performance

## 📧 Contact

For questions or suggestions regarding this project, please feel free to reach out.

## 📄 License

This project is available for educational and research purposes.

---

*This project demonstrates the application of machine learning techniques to real-world pricing prediction problems, providing valuable insights into the airline industry and consumer decision-making.*
