# Big Data Final Project
## Information
### Training / Testing Data
* `~2018` for training, `2019` for testing
### Data for Building the Prediction Models
* 市場：`台北一`
* 作物種類
```
鳳梨-金鑽鳳梨, 香蕉, 青蔥-日蔥, 蓮霧-紅蓮霧, 芽菜類-黃豆牙, 南瓜-木瓜形, 大蒜-蒜仁, 小白菜-土白菜, 木瓜-網室紅肉, 洋香瓜-網狀紅肉
```

## Error Rate
* Price


| Model |香蕉 |洋香瓜 |蓮霧 |鳳梨 |南瓜 |大蒜 |青蔥 |小白菜 |芽菜類 |木瓜 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| LSTM | 0.011 | 0.024 |      |      |      |      |      |      |      |      |
| Prophet |      |      |      |      |      |      |      |      |      |      |
| ARIMA |      |      |      |      |      |      |      |      |      |      |


* 3_day_return


| Model |香蕉 |洋香瓜 |蓮霧 |鳳梨 |南瓜 |大蒜 |青蔥 |小白菜 |芽菜類 |木瓜 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| LSTM | 0.048 | 0.04 |      |      |      |      |      |      |      |      |
| Prophet |      |      |      |      |      |      |      |      |      |      |
| ARIMA |      |      |      |      |      |      |      |      |      |      |