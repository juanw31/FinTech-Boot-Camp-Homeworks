In this homework, I built 2 deeplearning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurries than the normal closing  price data. It seems like using historical closing price privides a better signal for cyryptoucurrenices than FNG indicator. 

1. Which model has a lower loss?

The normal closing price model had a lower loss than the FNG values model. 

2. Which model tracks the actual values better over time?

The closing price model tracks the actual values better over time. The predicting line chart has the same trend line compare to real price line. 

3. Which window size works best for the model?

I tried 3 windows. The smaller the window size the better fitting the model. 
Window size = 10, loss value is 0.08
Window size = 5, loss value is 0.06
Window size = 1, loss value is 0.03