# SP500 Predicts models

Project SP500 Predicts models checks whether simple classification models can predict price movements
the SP500 index. The model of Decision Trees, Linear Regression and Random Forests was tested.

## Strategy

Models were trained based on volume size, open, close, high and low of the day.
No technical analysis indicators were used.

## Technology

Standard Python libraries were used in the project. The yfinace and os libraries were used for data processing.
The classification models were taken from the sklearn library. The scoring method was precision_score

## Conclusions

None of the models achieved a precision greater than 50%. Models cannot be considered for trading. The models are
statistically insignificant.

