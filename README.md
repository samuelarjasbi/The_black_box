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

In the above scenario, we are faced with buying a lot of stocks or selling them with hundreds of accounts that belong to a person (Whale). Buying or selling those stocks with such accounts needs a hundred traders coordinated together for buying the same stock in a small amount of time. Nowadays we do that with bots. Bots are more accurate, fast, and reliable than human beings in those situations. Anyway, that was just one scenario that I tried to cover, there are a lot of thousand of methods and scenarios out there you can research about it, however, I tried to cover the technical side of these bots, not financial logic and more.


#### Business Side
As I said above there are three types of Bots. But just the Expert Bots are available for buying or renting, but two other types are exclusive and it's even hard for someone to tell you that they have such bots, because these two types of bots can help you to earn enough money so it does not make any sense to sell them to someone else, except for some cases that I'm going to cover in this part but it is not going to have so many details, after all my profession is programming. However you can use the below methods for better use of bots, also you may need more research about the business side.
* Portfolio Management (Portfolio Trading).
* Partnership with investors.
* Personal Trading with Risk management.


### Testing
There are certain ways for testing bots without losing any money that I'm going to cover in this part.

#### Expert Bots Testing
In fact in Expert Bots, there is no connection between your money or portfolio technically to the bot, Expert Bots simply give you some signal for Buying or Selling stocks. For testing it you can save, for example, a month's signals as the BackLogs then review the logs according to your knowledge of trading and calculate the accuracy. For calculating the profit percentage you can set an amount of portfolio or money and check how much interest you would earn with only the bot’s signals. However, you must not trade only with Expert Bot's signals. In fact, you must validate Bot’s signals with your trading knowledge then trade on the Market.


#### Personal Bots Testing (Strategy Bots Testing)
As we know Personal Bots are designed based on personal trading strategies. Also, they are a little bit similar to the way Expert Bots work, they both give you some signals for trading.
For testing these bots you have to compare your bot function with your strategy backlogs. For example, you have to run the bot for a month and save the backlogs then compare logs with your strategy logic.


#### Whale Bots
Whale bots are more different than other types. In all types, it is better to use microservices to avoid crashing the entire project debugging a part or a service of the project. The microservice structure is a good choice for designing Whale Bots.

For testing a Whale Bot according to Bot’s structure you have, Buying and Selling services with microservices. You must design a testing service with buying and selling service logic but the difference is, the test service is not going to actually buy or sell anything, it simply acts as the buying or selling service and after completing the tasks, it will return a message. It's like you give bots mock money and bots try to trade with it and return results. For example in the cumulative trading method (read the Comparison section, whale bots part), you have to trade with a lot of accounts and buy or sell the stock with these accounts in a small amount of time, so you must create mock accounts and do mock trades and return the time of selling or buying as the Backlog to calculate how much accurate is the bot.

#### Managing and Control
For better usage of the bots, it is better to design a panel for controlling the bot and watching the results. No one doesn't like a command prompt for controlling everything (except some programmers). In this topic, I'm going to cover some methods for designing panels or applications for controlling bots.

#### Chart Panel ( based on Web Application )
A better and more professional way to design a panel is to use charts in the management panel. You can use a lot of APIs for getting a professional chart for your site like TradingView API which is a site for observing the international market and you can use it for creating charts with different options such as candle charts, indicators, and so on. A great way to build a panel is to first design the bot as an API or RestAPI based on Microservices architecture and design a panel service and connect that to bot API. Also, always you can use Ajax or JS for the front-end of your service to instant show data.

#### Installable applications
In the above approach, we designed our bot based on a web application. But you can use almost the same architecture bot design a Windows, Android, or IOS GUI application. This way has its own advantages but my suggestion is to use both approaches, first design a web application then create native applications for different operating systems. In both approaches, APIs come handy.

#### Automation to Messengers
This is a creative but not always great approach. You can connect your bot to a messenger like a Telegram or Whatsapp messenger to send you a message as a signal. or you can design a Telegram Bot or Whatsapp Bot to control the bot. You can define commands for the bot so you can control bots through commands that you will send to the Telegram bot. But it is not a great way to control your but because you can't have much flexibility and functionality unless you use it as a utility besides your managing panel.

#### Suggestions
Don’t create a very complex panel because trading has its own complexity so a trader likes to focus on trading charts and indicators, not your difficult UI and UX. It makes sense for all people, not just traders.

### Main Course

#### Good shame
We had the above knowledge, Expert trading teams, System designers, and developers, we spent months creating an MVP and the result was great actually, but we faced a lot of shame at the same time, but there is a quote by Reid Hoffman said: “If you’re not embarrassed by the first version of your product, you’ve launched too late”. After the first MVP, we tried to test it, but the test process was a different challenge because our project was a combination of three types of bots that I said before. We spent a month diagnosing, saving, and analyzing backlogs. The final result was more than 10% compound interest. It was good but not enough.

#### Diagnosing Errors
After a couple of months of working on strategies and codes, we were able to debug the project and get a second test. In the second test that wasn’t that shameful and we faced a good result finally. We tested our second MVP for more than three months and we achieved more than 28% compound interest and it was actually great. However, there was a huge amount of errors. You must pay attention when you have 30% accuracy and also have 70% errors. So it was not reliable that much to let the bot trade by itself.

#### Lack of Tech
After almost a year of working on the project and facing the different challenges, we got a great result and a great percentage of compound interest.

Our idea was to let the bot trade for itself but for that goal, you must achieve more than 50% accuracy, which was unavailable with our budget. Even great companies and well-known brokers were not able to achieve this kind of thing. They all have bots working with traders together. A trading bot is not anything more than a signal bot or a stock spammer bot now and they are just designed to approve the decision of traders based on strategies and price actions concepts. We even tried to design a machine learning system for recognizing patterns but it was not helpful more than 2% or 5%.



### Last but not least
After all, we designed a great bot for trading but it was not the same as our first idea of trading automatically. However, you will not be going to achieve exactly what you want. Remember the Slack company was a game company and the Slack app was their internal app but they find out this small app could change their life rather than a game company.
In addition, always have in mind, You may not be the first one but may you be the big one in whatever you’ll do. Also at the beginning of the work and projects design a plan, but during working on the project think about your next step, not your final goal, you already have a plan for that.
