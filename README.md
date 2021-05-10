# TechnicalAnalysis_Twilio
'''The function below responds to an incoming text message from the user. It is designed to provide the user with trading signals
and other information on a requested stock. If the user says Hello/Bye the function will respond
with a hi/goodbye. In addition to that, any other text messages from the user will prompt an automated response of:

Hi, if you would like to know trading signals about a specific stock, please reply back with XTSE/ticker name, start_date 
and end_date. 
Please follow this format: XTSE/BMO, 2019-12-31, 2021-1-25 
Please do not forget the commas!
Please provide a min of 33 days difference between start & end dates.
Please note: Info will only be provided for stocks on XTSE.

If the user follows the specified format as stated above, the function will take the ticker and date information and 
calculate the RSI, Stochastic indicator, simple moving average and the Bollinger Bands. It will then reply to 
the customer with all the indicators, the high, low & closing prices for the end date and where the stock price is moving
with respective to the Bollinger bands on the requested end date  (ie. upper, lower etc.).

For this assignment, I have made use of the starter code provided by Twilio.
'''
