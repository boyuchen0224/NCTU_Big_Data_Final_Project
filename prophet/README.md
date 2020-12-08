# Results
## Seasonality, historical data & 1-year prediction:
* https://drive.google.com/file/d/1OeAkrS2aut36bCRgPUhS9ayYcl2RdSNb/view?usp=sharing
### Sample
#### 蓮霧-紅蓮霧 - historical data & 1-year prediction
![Imgur](https://imgur.com/AIZgNl7.png)
#### 蓮霧-紅蓮霧 - Seasonality
![Imgur](https://imgur.com/ehfzFuI.png)

## Prediction
csv (ground-truth, prediction & diff) and images (line charts)
* https://drive.google.com/file/d/1GifgYtFb-WdT6LsQ07X3Z08fcdMXNM9I/view?usp=sharing
### Sample
![Imgur](https://imgur.com/k4yltgR.png)
![Imgur](https://imgur.com/G0gXduJ.png)



# Todo
- [x] Analysis: `analysis.ipynb`
   - [x] Plot the 1-year prediction
   - [x] Seasonality analysis & save the results
- [x] Build the forecast models: `predict.ipynb`
   - [x] Build model for ~2018, and test for the first week of 2019
   - [x] Measure the time of fitting
   - [x] Repeat this procedure for whole 2018
- [x] Evaluate the forecast results: `evaluate.ipynb`
   - [x] Calculate the difference between prediction & ground-truth
   - [x] Plot with the ground-truth
   - [x] Save the results as dataframes & images
- [ ] Additional Regressors
   - [ ] Add `additional_regressor`
   - [ ] Collect the data with `additional_regressor`
- [ ] Online learning
   * Not available: need to re-fit the model if obtaining new data
   * But there are several ways to warm-start
       * Ref: https://github.com/facebook/prophet/issues/46

