# Results
## LSTM prediction

* Objective :
    * Predict vegetable prices in 2019 in market 台北一

* Results : 
    * https://drive.google.com/drive/folders/11dLYxKxWgK_dvTaGlJ_fB0RcwblepoQp?usp=sharing


## Sample
#### 香蕉
* Training data: (2111 days)
    * input: 2012/01/01 ~ 2018/12/22
    * output: 2012/01/08 ~ 2018/12/30

* Testing data: (298 days)
    * input: 2018/12/23 ~ 2019/12/22
    * **output: 2019/1/1 ~ 2019/12/31**

## Prediction
csv (date-time, ground-truth, prediction)
* https://drive.google.com/drive/folders/1fmQuRe9Mp53-z0FqOLc-irRQO9Gc13cb?usp=sharing

### Sample
* 3 day returns prediction
![Imgur](https://i.imgur.com/KrESfgK.png)
* price prediction
![Imgur](https://i.imgur.com/MbS25jy.png)

### Feature Importance
* 3 day returns prediction (in day1)
![Imgur](https://i.imgur.com/IlUM3Wi.jpg)
* Price prediction (in day1)
![Imgur](https://i.imgur.com/8Dj6Uz6.jpg)

## Reference
* [LSTM](https://medium.com/@daniel820710/%E5%88%A9%E7%94%A8keras%E5%BB%BA%E6%A7%8Blstm%E6%A8%A1%E5%9E%8B-%E4%BB%A5stock-prediction-%E7%82%BA%E4%BE%8B-1-67456e0a0b)
* [Shap](https://gitee.com/mirrors/SHAP?fbclid=IwAR0csbYzN2Qmosyr73PRnuDGIjhFfsUYnawjlSyMP-0M0E0wSrIT_wuhlrQ)
