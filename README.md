# CS50X PROJECT: Finance
## Implement a website via which users can “buy” and “sell” stocks, a la the below.

## CS50X [Link](https://cs50.harvard.edu/x/2022/psets/9/finance/)<br>

You’re about to implement C$50 Finance, a web app via which you can manage portfolios of stocks. Not only will this tool allow you to check real stocks’ actual prices and portfolios’ values, it will also let you buy (okay, “buy”) and sell (okay, “sell”) stocks by querying IEX for stocks’ prices.

Indeed, IEX lets you download stock quotes via their API (application programming interface) using URLs like https://cloud-sse.iexapis.com/stable/stock/nflx/quote?token=API_KEY. Notice how Netflix’s symbol (NFLX) is embedded in this URL; that’s how IEX knows whose data to return. That link won’t actually return any data because IEX requires you to use an API key (more about that in a bit), but if it did, you’d see a response in JSON (JavaScript Object Notation) format like this:

####{
  "avgTotalVolume": 4329597,
  "calculationPrice": "tops",
  "change": 1.21,
  "changePercent": 0.00186,
  "closeSource": "official",
  "companyName": "NetFlix Inc",
  "currency": "USD",
  "iexAskPrice": 662.59,
  "iexAskSize": 8080,
  "iexBidPrice": 652.65,
  "iexBidSize": 102,
  "iexClose": 652.66,
  "iexCloseTime": 1636479523133,
  "iexLastUpdated": 1636479523133,
  "iexMarketPercent": 0.03419734093274243,
  "iexOpen": 652.66,
  "iexOpenTime": 1636479523133,
  "iexRealtimePrice": 652.66,
  "iexRealtimeSize": 30,
  "iexVolume": 43968,
  "lastTradeTime": 1636479523133,
  "latestPrice": 652.66,
  "latestSource": "IEX real time price",
  "latestTime": "12:38:43 PM",
  "latestUpdate": 1636479523133,
  "marketCap": 288341929921,
  "openSource": "official",
  "peRatio": 58.85,
  "previousClose": 651.45,
  "previousVolume": 2887523,
  "primaryExchange": "NASDAQ",
  "symbol": "NFLX",
  "week52High": 690.97,
  "week52Low": 463.41,
  "ytdChange": 0.2066202315388457
}

### Built With
- HTML <br>
- CSS (Flexbox) <br>
- Python<br>

#### [Live](https://artanmerko.github.io/homepage/)
