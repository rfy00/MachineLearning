<b><i>Intro</i></b> - Public companies sell stocks on stock markets so that investors can invest their money in a company, their profits, and have voter rights at shareholder meetings.  It is one way a person can build wealth and companies can raise money for products, services, and other initiatives.  A person can buy or sell a company’s stock for either a profit or loss (O’Shea, 2020) https://www.nerdwallet.com/article/investing/what-are-stocks-how-they-work  

Stocks can have high returns, but they also have risks if the price goes down due to unforeseen circumstances 
   - Good or bad news that was made public about a company
   - Profits were not as high as expected
   - Widespread viruses affecting the world
   - Company downsizing or restructuring 
   - Bankruptcies

<b><i>Tools</i></b> - Python, CSV, PowerPoint

<b><i>Data</i></b> - Retrieved the Kroger (KR) historical stock prices from the “Stock Market Dataset” that appeared on Kaggle.com. Data contains stock information up to April 1, 2020 

Data Fields
   - Date - specifies trading date
   - Open - opening price
   - High - maximum price during the day
   - Low - minimum price during the day
   - Close - close price adjusted for splits
   - Adj Close - adjusted close price adjusted for both dividends and splits
   - Volume - the number of shares that changed hands during a given day

<b><i>Methods/Evaluation/Techniques</i></b> - Since stock prices and stock markets are volatile and there are many unknowns, it is hard to tell whether the models can be reliable or not. With the information that I reviewed for the Linear Regression and Decision Tree models, I would think they would be more reliable if stocks did not fluctuate as much. As with most things, experience and researching the various models and methods will help with making the models more accurate. The Decision Tree seemed to be the most accurate as it seemed to follow more of the fluctuations in predicting the future stock close price. I did use some statistical significance when I was evaluating the data by comparing the Open and Close prices, High and Low prices, and the Volume to see if I could see any patterns that appeared.    

<b><i>Conclusion</i></b> - Overall, it is tough to try to predict future stock Close prices based on many unknowns that factor into the prices. I believe with more experience and research, machine learning can help with stock price forecasts. While it seems like machine learning has been used a lot with trying to predict stocks, people should consider other methods outside of machine learning.  The other information may be able to show patterns in the data that may not appear in machine learning models and methods. When there is more historical data that is used, it seems to help predict the stock Close prices better. When there is not as much data that is used, there could be issues with the training of the datasets as it will not have a lot of the historical data. The forecasts will be skewed when there is stock volatility based on recent and past history and the time frame that is used. These models may be better used when the data is not as unpredictable. Overall, it is possible when more preprocessing tasks are completed, the models can be trained to create more of an accurate picture.

<b><i>Navigation</i></b> - 

<b>Kroger Stock Price Prediction.ipynb</b> is the main Python file on the GitHub website

<b>KR.csv</b> is the file that is uploaded into the ipynb file 

<b>Can Machine Learning Predict Stocks.pptx</b> is a PowerPoint presentation
