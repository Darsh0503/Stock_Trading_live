STEP 1: Use https://www.alphavantage.co/documentation/
        When stock price increase/decreases by 5% between yesterday and the day before yesterday then print("Get News").
        Get yesterday's closing stock price

STEP2 :Get the day before yesterday's closing stock price

STEP3: Find the positive difference between 1 and 2. e.g. 40 - 20 = -20, but the positive difference is 20.
       Work out the percentage difference in price between closing price yesterday and closing price the day before yesterday.

STEP4:  Instead of printing ("Get News"), actually get the first 3 news pieces for the COMPANY_NAME.
	Instead of printing ("Get News"), use the News API to get articles related to the COMPANY_NAME.
	If difference percentage is greater than 5 then print("Get News")

STEP:5  Use Twilio to send a seperate message with each article's title and description to your phone number.
