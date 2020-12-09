# Big Data Final Project
## Information
### Training / Testing Data
* `~2018` for training, `2019` for testing
### Data for Building the Prediction Models
* 市場：`台北一`
* 作物種類
```
香蕉, 洋香瓜-網狀紅肉, 蓮霧-紅蓮霧, 鳳梨-金鑽鳳梨, 南瓜-木瓜形, 大蒜-蒜仁, 青蔥-日蔥, 小白菜-土白菜, 芽菜類-黃豆牙, 木瓜-網室紅肉
```

## Error Rate (MSE)
* Price


| Model |香蕉 |洋香瓜 |蓮霧 |鳳梨 |南瓜 |大蒜 |青蔥 |小白菜 |芽菜類 |木瓜 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| LSTM | 0.011 | 0.024 | 0.021 | 0.018 | 0.012 | 0.004 | 0.008 | 0.017 | 0.007 | 0.016 |
| Prophet |      |      |      |      |      |      |      |      |      |      |
| ARIMA | 0.022 |      |      |      |      |      |      |      |      |      |


* 3_day_return


| Model |香蕉 |洋香瓜 |蓮霧 |鳳梨 |南瓜 |大蒜 |青蔥 |小白菜 |芽菜類 |木瓜 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| LSTM | 0.048 | 0.040 | 0.047 | 0.050 | 0.017 | 0.028 | 0.061 | 0.061| 0.017 | 0.045 |
| Prophet |      |      |      |      |      |      |      |      |      |      |
| ARIMA |      |      |      |      |      |      |      |      |      |      |


## Difference between 3 day return prediction
|香蕉 |洋香瓜 |蓮霧 |鳳梨 |南瓜 |大蒜 |青蔥 |小白菜 |芽菜類 |木瓜 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| 10.89% | 21.18% | 19.12% | 18.2% | 11.61% | 4.52% | 28.62% | 33.85% | 1.13% | 25.78% |
