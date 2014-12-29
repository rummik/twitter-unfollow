twitter-unfollow
================

## Quickstart
1. Create an app on https://apps.twitter.com/
2. Copy `config.example.json` to `config.json`
3. Edit `config.json` to use the keys from the 'Keys and Access Tokens' tab of your newly created app:

    ```
    {
    	"consumer_key": "YOUR CONSUMER KEY",
    	"consumer_secret": "YOUR CONSUMER SECRET",
    	"access_token": "YOUR ACCESS TOKEN",
    	"access_token_secret": "YOUR ACCESS TOKEN SECRET"
    }
    ```
    
4. Open a terminal and navigate to the location you've checked out twitter-unfollow, and run the following:

    ```
    npm install
    node unfollow
    ```
