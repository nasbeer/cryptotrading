# cryptotrading

### Getting Started

```
git clone https://github.com/nasbeer/cryptotrading.git
```


### Description

- This is a crypto currency trading bot used to parse data from Binance and determine when to buy and sell crypto curencies. 
- When a test trade is made an alert is sent to a discord webhook.
- Trade logic is left out in this project, but the methods for the api calls, discord calls, key values, and binance exchange data are available to be built off of.
- Note: this is set up to communicate with Binance.us, if you are planning to use this with Binance.com; you will need to update the exchange_id value to 'binance' instead of 'binanceus', however the api endpoints are the same.


### Setup Instructions

- to run the application, you will need to use "pip install" to install the following dependancies
    - json
    - requests
    - DateTime
    - time
    - ccxt

- in the BinanceClient file, update the api key and api secret with your information
- in the DiscordClient file, update the webhook url with your webhook url




### Support and Feedback

    Want to see a new feature or additional functionality? Feel free to send me an email at : nazbeer.ahammed@gmail.com
    If you are creating a new account for Binance.com to use this bot feel free to use this referral code: 
    https://www.binance.com/?ref=Z90E2SQ1 || You will get commission too.
    My Website: https://nasbeer.com
    
    
