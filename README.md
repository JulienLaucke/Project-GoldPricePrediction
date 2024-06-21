# Gold Price Prediction
![Bildbeschreibung](gold_image.png)
This project aims to predict future gold prices using historical data and various economic indicators. The prediction model is built using a Random Forest Regressor and is evaluated based on its accuracy and performance.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)
- [Next Steps](#next-steps)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The prediction of gold prices is a significant challenge in financial analysis, as gold is considered a safe haven and a hedge against economic uncertainties. Accurate predictions can help investors and analysts make informed decisions and better manage risks.

This analysis utilizes historical gold price data and economic indicators such as the SPX index, oil price (USO), silver price (SLV), and the EUR/USD exchange rate to build a predictive model. A Random Forest Regressor is chosen for its robustness and ability to handle complex datasets with many variables.

## Data

The dataset includes the following features:
- Date
- SPX (S&P 500 Index)
- GLD (Gold Price)
- USO (Oil Price)
- SLV (Silver Price)
- EUR/USD (Euro to US Dollar Exchange Rate)

The data is split into training and testing sets to evaluate the model's performance.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gold-price-prediction.git
   cd gold-price-prediction
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Jupyter Notebook to see the data analysis and model training:
   ```bash
   jupyter notebook Gold_Price_Prediction.ipynb
   ```

2. To execute the script directly:
   ```bash
   python gold_price_prediction.py
   ```

## Results

The model's performance is evaluated using the R² score and visual comparison between actual and predicted gold prices. An interactive Plotly graph is used to allow users to toggle between actual and predicted values for detailed analysis.

## Conclusion

In this analysis, we examined gold price data and built a Random Forest Regressor model to predict future gold prices. The model achieved an R² score of \( \text{error_score} \), indicating its capability to explain a significant portion of the variance in the gold price data. However, there is still room for improvement through hyperparameter tuning and the inclusion of additional relevant features.

## Next Steps

- **Model Improvement**: Further tune the model using hyperparameter optimization and cross-validation.
- **Feature Engineering**: Incorporate additional economic indicators and seasonal features that may influence gold prices.
- **Long-term Predictions**: Evaluate the model's performance for longer-term gold price predictions.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue for suggestions and improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```

### Hinweise:
1. Ersetzen Sie `https://github.com/yourusername/gold-price-prediction.git` durch die tatsächliche URL Ihres GitHub-Repositories.
2. Stellen Sie sicher, dass Sie eine `requirements.txt`-Datei im Repository haben, die alle benötigten Python-Pakete auflistet.
3. Fügen Sie eine `LICENSE`-Datei hinzu, falls diese fehlt.

Diese README-Datei bietet eine klare und umfassende Anleitung zur Nutzung Ihres Projekts und hilft Benutzern, das Projekt schnell zu verstehen und zu nutzen.
