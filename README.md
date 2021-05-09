# Time Series Transformer
Train transformer model to forecast stocks prices at 1 minute timescale  
Compare transformer with [LSTM models](https://github.com/ctxj/Financial-Time-Series/blob/main/lstm_fb.ipynb) 

Using 10 timesteps of stock's movement to forecast 1 timestep in advance  
Transformer models trained faster with lesser training epochs while outperforming LSTM models  

___

## Prerequisites
Python 3.8.6  
Pytorch 1.81  
[Python libraries](https://github.com/ctxj/Time-Series-Transformer-Pytorch/blob/main/requirements.txt) pip install -r requirements.txt  

___

## Data
[Facebook's intraday data](https://github.com/ctxj/Time-Series-Transformer-Pytorch/blob/main/FB_raw.csv)  
[Boeing's intraday data](https://github.com/ctxj/Time-Series-Transformer-Pytorch/blob/main/BA_raw.csv)  
[JPMorgan's intraday data](https://github.com/ctxj/Time-Series-Transformer-Pytorch/blob/main/JPM_raw.csv) 

___

## Model
[Transformer notebook](https://github.com/ctxj/Time-Series-Transformer-Pytorch/blob/main/transformer_model.ipynb)  
[Trained Transformer model](https://github.com/ctxj/Time-Series-Transformer-Pytorch/blob/main/transformer_ts.pth)

___

## License
![Apache License 2.0](https://img.shields.io/badge/License-Apache--License--2.0-yellow.svg)