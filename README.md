# twitter-sniper
A plugin that allows to perform actions based on monitored Twitter accounts and keywords with sentiment analysis support.

## Introduction
Use case:
  - If a monitored Twitter account makes a tweet
    - Check if the tweet contains monitored keyword
    - Run sentiment analysis on tweet and return score
    - User can then choose to perform action based on this score

Example: Influential person posting a positive tweet about a cryptocurrency, where the user then wants to open a buy order on their exchange through API call action.

## Features
- Config
  - Add monitored Twitters
    - Monitored keywords for this specific Twitter account
      - Actions based on sentiment analysis score for this tweet 
  - CRON tasks
    - Setup how often the plugin should run
- Twitter scraping
- Sentiment analysis
  - Perform analysis on string and return score
- Actions
  - API calls
  - Email, SMS or Pushbullet notifications
  - Discord webhook
