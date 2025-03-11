# Stock Price Prediction Using LSTM

## Project Overview
This project leverages a Long Short-Term Memory (LSTM) model to predict stock prices using historical data. By employing machine learning techniques, the model generates accurate forecasts to help identify potential investment opportunities. Visualizations are integrated to showcase insights into stock trends and patterns, making complex data easier to understand.

## Project Preview
![Stock Prediction Visualization](Area_Chart.png)
![Stock Prediction Visualization](Candlestick_Chart.png)
![Stock Prediction Visualization](Faceted_Area.png)
![Stock Prediction Visualization](Line_Chart_with_Moving_Averages.png)
![Stock Prediction Visualization](LineChart.png)

## Key Features

### Model Development
- Implemented an LSTM model tailored for effective time series prediction.  
- Applied train-test splitting and data scaling techniques to enhance model accuracy.  
- Integrated performance evaluation metrics to track model effectiveness.

### Visualizations
- Plotted actual vs predicted stock prices to assess model accuracy.  
- Illustrated key trends and insights using clear and engaging visualizations.

## Tools & Technologies
- **Python Libraries:**  
  - `NumPy` & `Pandas` for data manipulation.  
  - `Matplotlib` & `Seaborn` for compelling data visualizations.  
  - `TensorFlow/Keras` for building and training the LSTM model.

# How to Use

1. **Download all the files**:
   - Download the repository and save it to your local system.

2. **Extract the Dataset Zip**:
   - Extract the zip file containing the dataset to a folder of your choice.

3. **Install the required libraries**:
   Run the following command in your terminal or command prompt:
   ```bash
   pip install numpy pandas matplotlib seaborn tensorflow keras
4. **Update the file path for the dataset:** In the Jupyter Notebook LSTM_prediction.ipynb, locate the following line and replace the path **r'C:\Users\Vedant\Desktop\Portfolio\Stock Price Forecasting\Dataset'** with the actual path to the folder where the dataset is located on your local machine:
    ```bash
    for dirname, _, filenames in os.walk(r'C:\Users\Vedant\Desktop\Portfolio\Stock Price Forecasting\Dataset'):
5. **Run the notebook:** Follow the step-by-step instructions to load the data, preprocess it, train the model, and visualize the results.
  
## Insights & Recommendations
- The model effectively captures stock price trends but may show limitations during volatile market conditions.  
- For improved accuracy, consider adding more features like trading volume or technical indicators.  
- Use the model's insights to guide investment decisions and identify profitable opportunities.  

## Future Enhancements
- Fine-tune the LSTM model by optimizing hyperparameters.  
- Integrate live data feeds to enable real-time stock price prediction.  
- Expand the model to predict multiple stock indices for comprehensive analysis.

## Contact

For questions or collaboration, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/vedantshinde25).
