# The black box

## Introduction

We were ambitious. That was our mindset. Hard work was what we were doing but there is a quote that says “Work smart not just hard”
In 2019 we Start a project called Hemmat with a great team. Our goal was to design an Expert bot for the Iranian stock market but in our project, this bot could be even more expert. I'll tell you in a moment what I mean. We had a complete team of expert traders and also great developers with knowledge of software architecture.
In the beginning, let me explain what is an expert bot. Expert bots are an automation code for scanning the whole target stock market and listing the best available stocks for trading as export. Sometimes, AI scientists mixed automation codes and AI and Machine learning codes to gather and make a smart bot and not only an automation bot. Expert bots are available on the market for renting or buying but you have to be careful because most sellers are scammers and they give you a useless bot and then the only thing you achieve is bankruptcy. You can find it as Black Box trading bots, forex automation bots, and expert bots.



### Idea

Our main idea was to design an expert bot not only for detecting the best stocks bot to trade automatically. 
For starters, you have to recognize a pattern for trading that trading experts call the Strategy.

#### Strategy
Designing a strategy requires a lot of knowledge and experience in that specific market and also you must have great knowledge of traders and market behavior to recognize the patterns. As a result, you can discover a pattern for forecasting future happens in the market, but these strategies are not always accurate and they have the amount of errors percentage but competitions are about the percentage of accuracy. There is a conceptual formula for accuracy percentage “ in a strategy always we have failures and errors, but let's say we want to calculate accuracy or interest percentage per month, then you have to multiply your earned money in that month by 100, and divided by your base money (money you had at the start of the month) so it is your interest percent per month”, most of the beginner traders have 1% profit or in other meaning, they have no much profit also they lose their money. In addition, a lot of the expert traders have between 10% to 20% profit and that is amazing interest percent because for example if you trade with 1000$ and keep your interest percent at 10% for every month in a year. Also, add your monthly profit to your trading money. At the end of the year, you have a 213% interest rate and your total money would be 3,138$, but with a regular interest rate after a year you got 2,200$ and 120% interest.



![](https://github.com/samuelarjasbi/The_black_box/blob/main/1643646379821.jpg)

#### A = final amount
#### P = initial principal balance
#### r = interest rate
#### n = number of times interest applied per time period
#### t = number of time periods elapsed



In our case, we had an experienced trader team which they have more than 10 years of experience in the Tehran stock market, so also they had a specific and amazing strategy, and our duty was to convert the strategy logic to codes. However, I'm not going to explain the strategy details because of the NDA contract for the reason that that is such a hard thing to achieve so traders have the right to keep it dark.

#### Stack
* Python is one of the best languages for data analysis and data processing also automation.
* Python has simple syntax so our main focus was on logic and the codes were not going to disrupt us.
* We were could fast to change the codes for testing more scenarios.
* Python has a lot of handy libraries for data processing and data visualization.

Also, we were forced to use Selenium and some web scraping methods and get some data, not through the APIs.
For the server-side we tried to use Django and MongoDB for the database, also we had to use some machine learning libraries to filter some data, and last but not least we used Microservices Architecture for the reason we had multi-services to keep the project more reliable.

### Comparison

#### Expert Bots
If you hit Google and search for Trading Bots, Trading Automation, Forex Bots, etc … you will get some sites they are all offering you to rent or buy one of they bots. After purchase, you will get a panel or in some cases, you will get an application that you can select your target market for example USD/JPY then it will show you when is the best time to Buy or Sell. These bots are not necessarily scamming or malicious applications in fact in most cases they are legit but as I said before competition is about accuracy. In most cases, let me say in 98% cases you will get a bot that checks the price actions logic in the market, every second, and behaves according to the concepts of price actions methodologies (Technical Trading).


#### Personal Bots (Special Bots)
Personal bots are Strategy bots. As I said before most traders have their own strategy for trading on the market. In fact, the strategies are the specific order of the price actions methods. Let me break it down for you.

We know that every market works based on Supply and Demand law, so traders with economic knowledge can watch the demandants' behaviors and also use technical trading methods and connect those concepts together in order to increase accuracy. Then they test it on the market for a period of time and check the results. It's a trial and error process and it may take in some cases a couple of years and take a lot of effort.

In some cases bots combine with more smart services for example they design methods for observing influential people's tweets, Instagram feeds, or their media activities because it could have a great effect on the market. For example, in February 2021 Elon Musk announced that Tesla bought bitcoins worth $1.5 billion. The cryptocurrency rose by 20 percent in one day, or in another scenario, in March 2021 Elon Musk tweeted ‘I’m getting a Shiba Inu’, on June 25 he said ‘My Shiba Inu will be named Floki’ and finally he tweeted again ’Floki has arrived’ with the picture of his dog sleeping on the rug. As a result of these tweets, Floki Inu rose by 1,000 percent by Sep 15.

#### Whale Bots
These bots are designed specifically for the whales in the market. Whales are those who have lots of wealth on the market and their activities have a remarkable effect on the market. So the question is why whales need bots for trading. Actually, there is a lot of scenarios we can talk about but let me break down one scenario as an example.

| Cumulative tradings        |
| -------------              |
| In the Iranian stock market, the volume of the market is not that too much rather than the international market. For example, the average market value of a well-known but normal company in Iran is 800,000$ so a whale can easily affect to market if he/she wants to. In a real scenario, a whale can buy a huge amount of company stock with different accounts, for example, buy 10% trading shares with a hundred accounts in close periods of time, so the other traders who watch the stock market going to affected by actions and they follow the way (they get carried away with price actions) and buy the same stock. When this state happens the price goes high and the whale will get for example 100% of profit and then the whale suddenly starts to sell their stocks very quickly and take it’s found out of the market. So let's say whales enter the market with 80,000$ then they can get out with almost 16,000$ in almost 2 hours. |
