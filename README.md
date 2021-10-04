# ai-trading-bot

I created 3 trials of 2 models.  Each time I used different rolling windows to calculate my models.  Model one used the SVM model.  Model two used the ADAboost model

SMA is what I am calling my rolling windows.

For trial 1 I used a 4 day rolling average for my short and a 100 for my long
For trial 2 I used a 5 day rolling average for my short and a 120 for long
For trial 3 I used a 5 day rolling average for my short and a 125 for long

The best model was model 1 SVA model from trial 3 with a 5 day short and 125 day long rolling window

Number 1
SMA 4 and 100

Model 1 SVM Model
SMA 4 and 100

![Screenshot](https://github.com/madhugirl/ai-trading-bot/blob/main/model_1.png)


Model 2 ADABoost Model

![Screenshot](https://github.com/madhugirl/ai-trading-bot/blob/main/model_2.png)

Model 1 performed slightly better than model 2.  Tuning the model using the ADA Boost performed slightly less accurate than model 1

Number 2
Adjusted SMA 5 and 120


Model 1

![Screenshot](https://github.com/madhugirl/ai-trading-bot/blob/main/model%201%20adjusted%20sma.png)

Model 2

![Screenshot](https://github.com/madhugirl/ai-trading-bot/blob/main/model%202%20adjusted%20sma.png)

Again model 1 performed better than model 2.


Number 3
Adjusted SMA 5 and 125


Model 1

![Screenshot](https://github.com/madhugirl/ai-trading-bot/blob/main/model%201%20sma%203.png)

Model 2

![Screenshot](https://github.com/madhugirl/ai-trading-bot/blob/main/model%202%20sma%203.png)

Model 1 from this trial performed the best out of all of them.  The 5 and 125 rolling windows made a huge difference in the accuracy of predicting the cumulative daily returns.