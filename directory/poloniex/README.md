## **Poloniex**
---

Poloniex is a digital asset trading service. It is a type of exchange through which users can transact in different digital currencies around the world. In this way, Poloniex is very similar to any of an ever-increasing number of digital currency exchanges headquartered in various countries.

Check out the [API-ENDPONIT](https://poloniex.com/public)

>### **Preview of poloniex query collection in Firecamp**

![poloniex queries list and debugging](https://raw.githubusercontent.com/shrey1608/firecamp-public-apis-directory/master/directory/poloniex/poloniex%20query%20collection%20Firecamp.gif)

***
### **List of queries**
------------------

#### **HTTP**
- returnTicker ---> Retrieves summary information for each currency pair listed on the exchange
- return24hVolume ---> Returns the 24-hour volume for all markets as well as totals for primary currencies.
- returnOrderBook ---> Returns the order book for a given market, as well as a sequence number used by websockets for synchronization of book updates and an indicator specifying whether the market is frozen. You may set currencyPair to "all" to get the order books of all markets. 
- returnTradeHistory ---> Returns the past 200 trades for a given market, or up to 1,000 trades between a range specified in UNIX timestamps by the "start" and "end" GET parameters.
- returnChartData ---> Returns candlestick chart data. Required GET parameters are "currencyPair", "period" (candlestick period in seconds; valid values are 300, 900, 1800, 7200, 14400, and 86400), "start", and "end". "Start" and "end" are given in UNIX timestamp format and used to specify the date range for the data returned.
- returnCurrencies ---> Returns information about currencies.
- returnLoanOrders ---> Returns the list of loan offers and demands for a given currency, specified by the "currency" GET parameter.
 
>### **Preview of poloniex websocket in Firecamp**

![poloniex websocket](https://raw.githubusercontent.com/shrey1608/firecamp-public-apis-directory/master/directory/poloniex/poloniex%20websocket%20Firecamp.gif)

------------------

#### **WebSocket**
------------------

- Subscribing and Unsubscribing ---> To receive updates from a channel you must subscribe to it. To subscribe to a public channel (all except the account notifications channel), determine its channel ID (provided with the description of each channel, and summarized here), send a JSON message
- Account Notifications ---> Notifications provided by the account to the user.
- Ticker Data ---> Subscribe to ticker updates for all currency pairs.
- 24 Hour Exchange Volume --->  Subscribe to 24 hour exchange volume statistics. Updates are sent every 20 seconds.
- Price Aggregated Book ---> Subscribe to price aggregated depth of book by currency pair

------------------ 

### Import [Firecamp collection](https://raw.githubusercontent.com/shreya-gr/firecamp-public-apis-directory/master/directory/poloniex/poloniex_firecamp.json) of poloniex queries to debug within seconds

Check out to learn [how to import queries](https://github.com/shreya-gr/firecamp-public-apis-directory#how-to-use-collection) collection in Firecamp