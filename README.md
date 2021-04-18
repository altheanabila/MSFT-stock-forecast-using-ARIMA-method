# MSFT-stock-forecast-using-ARIMA-method

I try to forecast the stock price of Microsoft using ARIMA method. The data is downloaded in range of period 5 years. By using Python libraries namely pandas, numpy and pmdarima, we could see the result through line graphs.
On the data processing, we use adjusted closing price in order to run ARIMA method.

1. Download the data of stock

   [MSFT](https://github.com/altheanabila/MSFT-stock-forecast-using-ARIMA-method/blob/main/MSFT.csv)

2. Import the data into panda dataframes

                        ![TestImage1](https://github.com/altheanabila/MSFT-stock-forecast-using-ARIMA-method/blob/main/pdmsft.png)


                        ![TestImage1](https://github.com/altheanabila/MSFT-stock-forecast-using-ARIMA-method/blob/main/pdmsft2.png)

3. Processing the lag features

                        ![TestImage1](https://github.com/altheanabila/MSFT-stock-forecast-using-ARIMA-method/blob/main/pdmsft3.png)


4. Define Data column, index features, training data and test data (must be less than total row)

                        ![TestImage1](https://github.com/altheanabila/MSFT-stock-forecast-using-ARIMA-method/blob/main/pdmsft4.png)

5. Define test data

                        ![TestImage1](https://github.com/altheanabila/MSFT-stock-forecast-using-ARIMA-method/blob/main/pdmsft5.png)

6. import pmdarima,and find the best fit of model 

                        ![TestImage1](https://github.com/altheanabila/MSFT-stock-forecast-using-ARIMA-method/blob/main/pdmsft6.png)


7. Run the forecast model to predict stock price

                        ![TestImage1](https://github.com/altheanabila/MSFT-stock-forecast-using-ARIMA-method/blob/main/pdmsft7.png)
