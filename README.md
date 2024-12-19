AiMoneyMaker uses machine learning techniques to predict the stock market of cyclical stocks with clear results and is easily changed to accomodate for various stocks

# AiMoneyMaker

### Steps To Access and Run the code

1. Open code in git by clicking on the file name in this repo's home page.

2. Click on the blue "Open in Colab" button

3. Make sure you are signed in to google

4. Under the file name in the top left corener of the window, click on the "Runtime" tab

5. Click "Run All" 

6. It may take a minute to run all the code cells however you can watch as they run

### How to Interpret Graphs, Change Input, and Which Stocks Work Best
1. In the second cell, in the parentheses, you can change what stock is being predicted and when the predictions are based on by using the format
    * ('yfinance stock abbreviation', start= 'start date in YYYY-MM-DD format', end= 'end date in YYYY-MM-DD format')
    * To see the new stock results, click the "Runtime" tab, then click "Run All"

2. To find the yfincance stock abbreviation just look it up in your browser of choice and it should be there

3. The Blue Line is the stock between the start and end dates

4. The Orange Line is the predicted stock

5. In the very last cell, the Orange Line that extends past the Blue Line is the prediction for the stock after the previously entered end date

6. This prediction works best with cyclical stocks such as the DAC or Danoas Corporation stock which is a shipping stock that goes down in winter and back up in the summer. Acyclical stocks will most likely be inaccurate



