# HDFC-Stock-Price-Anomaly-Detection
A model to detect sudden highs or lows in the HDFC Bank stock prices based on the data of last two decades.(1996-2020)
- This model  is inpired by the work of https://github.com/susanli2016
- The model perfectly detected the market crash in March 2020 and the sudden increase in the stock prices in the following days.
- LSTM, autoencoder architecture was used with a memory shape of 30 days.
- Based on the trend from 1996-01-01 to 2018-01-01 a threshold value was found. The points above the threshld were treated as anomalies.
- The model was trained on the data from 2018-01-01 to 15th Sepetember, 2020.
- There is some issue regarding the data point from 27th October 2019. For all practical purposes consider it to be a glitch. I have cross-checked the validity of the data point from other sources. If you happen to figure out the glitch. Feel free to share. Kudos.
- Check out the dataset here https://github.com/Aayushk26/HDFC-Stock-Price-Anomaly-Detection/blob/master/HDFCBANK.NS.csv
