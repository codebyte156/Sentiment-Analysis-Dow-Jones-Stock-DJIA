# Sentiment Analysis: DJIA Stock Using News Headlines

This repository contains a project focused on sentiment analysis of the Dow Jones Industrial Average (DJIA) stock using news headlines. The goal of this project is to explore the relationship between news sentiment and stock market performance, and to predict stock market trends using machine learning models.

## Features
- **Data Preprocessing**: Cleaning and preparing news headline data for analysis.
- **Sentiment Analysis**: Using natural language processing techniques to extract sentiment from news headlines.
- **Exploratory Data Analysis (EDA)**: Visualizing and analyzing the relationship between news sentiment and stock price movements.
- **Machine Learning Models**: Implementing predictive models to forecast stock trends based on sentiment analysis.

## Dataset
The dataset used in this project contains:
- **News Headlines**: Historical news headlines that potentially impact DJIA performance.
- **Stock Market Data**: Historical DJIA index data.

The dataset is included in this repository under the `data/` directory. Ensure that the dataset is in the correct path before running the notebook.

## Getting Started

### Prerequisites
To run this project, you will need the following:
- Python 3.7+
- Jupyter Notebook or any compatible IDE
- Key Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `nltk`
- ML Algorithms: `Random Forest`, `Multinomial Naive Bayes` & `Logistic Regression`

You can install the required libraries using:
```bash
pip install -r requirements.txt
```

### How to Run
1. Clone this repository:
    ```bash
    git clone https://github.com/codebyte156/Sentiment-Analysis-Dow-Jones-Stock-DJIA.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Sentiment-Analysis-Dow-Jones-Stock-DJIA
    ```
3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook stock-sentiment-analysis.ipynb
    ```
4. Run the notebook cells sequentially to execute the analysis.

## Project Structure
```
Sentiment-Analysis-Dow-Jones-Stock-DJIA/
├── data/
│   └── Stock-Headlines-DataSet.csv     # Dataset for the project
├── stock-sentiment-analysis.ipynb      # Main notebook
├── README.md                           # Project description
├── requirements.txt                    # Python dependencies
└── LICENSE.txt                         # License
```

## Results
The analysis provides insights into how sentiment in news headlines correlates with DJIA performance. Predictive models demonstrate the feasibility of using sentiment data for stock market trend forecasting. Visualizations in the notebook highlight key findings.

## Future Scope
- Incorporating real-time news feeds for live sentiment analysis.
- Testing additional machine learning models for improved accuracy.
- Expanding the dataset to include other stock indices or global markets.

## Contributing
Contributions are welcome! If you have ideas for improving this project, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the [MIT LICENSE](LICENSE) file for more details.

## Contact
For questions or suggestions, please reach out via [rahulraut.techuse@gmail.com](mailto:rahulraut.techuse@gmail.com) or open an issue on this repository.

---
Thank you for exploring this project. Happy analyzing!

