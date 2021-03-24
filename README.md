# NEWS OR NOISE? 
### or, identifying (reliable) algo trading signals for different asset classes

### Julia and TA
Julia - Github: juleskim / Email: juliajuleskim@gmail.com
Faith - Github: Faith0724 / Email: jiangyidan0724@gmail.com

### Team Members 
Mitchel Voloshin
Philip Waddilove
Phil Millspaugh
Rasha Mosaad
Rawlric Sumner 

## Team Lead
Committee

## Project Description/Outline

## Repo management
Jupyter notebook
Each have a notebook with in the repo
Move into master notebook

### Libraries and data sources:
Alpaca API
Kraken API
[News API if we incorporate sentiment analysis]
SciKit_Learn (train_test_split, StandardScaler)
Tensorflow.keras (Sequential, LSTM, Dense, etc)
LSTM and/or RandomForest model
* [ ] Fit the model(s) to the training data.

* [ ] Evaluate the trained model(s) using testing data. Include any calculations, metrics, or visualizations needed to evaluate the performance.

* [ ] Show the predictions using a sample of new data. Compare the predictions if more than one model is used.

* [ ] Save PNG images of your visualizations to distribute to the class and instructional team and for inclusion in your presentation and your repo's README.md file.

* [ ] Use one new machine learning library, machine learning model, or evaluation metric that hasn't been covered in class.

* [ ] Create a README.md in your repo with a write-up summarizing your project. Be sure to include any usage instructions to set up and use the model.




## Project Choice: Algo Trading
Project goal is to create an interactive bot that is able to accurately disperse noise related to chosen exchange traded funds and provide both quantitative and qualitative analysis to guide long term investment decisions.  By utilizing various APIs such as Alpaca, Kraken, and News API, we aim to produce a set of trading signals using 5 - 6 strategies and evaluate them for different asset classes.  We aim to employ machine learning to backtest these strategies [and potentially evaluate combinations of these strategies].

### Example assets:
S&P 500 ETF
T-Bond ETF
[BitCoin]

### Signals:
Simple Moving Average (SMA)
Weighted Moving Average (historically a high performer)
Relative Strength Index (RSI)
Moving Average Convergence/ Divergence (MACD)
Bollinger bands (BB)
[Sentiment analysis using VADER/ Tensorflow]

### Metrics:
Standard Deviation
Sharpe [and/or Sortino] Ratio
Total Returns
[Max Drawdown]

### Research questions to answer:
“I’m interested in the S&P 500 ETF, which signals are most reliable?”, i.e.
For a given asset: which strategy delivers the most reliable returns?
Does a combination of strategies work better?
How do the risks/ returns of these strategies compare?

### Research 

Datasets to be used
ETF price history going back to 1/1/10
Calculate 
Newsapi - tokenization dataset




