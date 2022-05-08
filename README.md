# CS50X PROJECT: Finance
## Implement a website via which users can “buy” and “sell” stocks, a la the below.

## CS50X [Link](https://cs50.harvard.edu/x/2022/psets/9/finance/)<br>

You’re about to implement C$50 Finance, a web app via which you can manage portfolios of stocks. Not only will this tool allow you to check real stocks’ actual prices and portfolios’ values, it will also let you buy (okay, “buy”) and sell (okay, “sell”) stocks by querying IEX for stocks’ prices.

Indeed, IEX lets you download stock quotes via their API (application programming interface) using URLs like https://cloud-sse.iexapis.com/stable/stock/nflx/quote?token=API_KEY. Notice how Netflix’s symbol (NFLX) is embedded in this URL; that’s how IEX knows whose data to return. That link won’t actually return any data because IEX requires you to use an API key (more about that in a bit), but if it did, you’d see a response in JSON (JavaScript Object Notation) format like this:

--
{<br>
  "avgTotalVolume": 4329597,<br>
  "calculationPrice": "tops",<br>
  "change": 1.21,<br>
  "changePercent": 0.00186,<br>
  "closeSource": "official",<br>
  "companyName": "NetFlix Inc",<br>
  "currency": "USD",<br>
  "iexAskPrice": 662.59,<br>
  "iexAskSize": 8080,<br>
  "iexBidPrice": 652.65,<br>
  "iexBidSize": 102,<br>
  "iexClose": 652.66,<br>
  "iexCloseTime": 1636479523133,<br>
  "iexLastUpdated": 1636479523133,<br>
  "iexMarketPercent": 0.03419734093274243,<br>
  "iexOpen": 652.66,<br>
  "iexOpenTime": 1636479523133,<br>
  "iexRealtimePrice": 652.66,<br>
  "iexRealtimeSize": 30,<br>
  "iexVolume": 43968,<br>
  "lastTradeTime": 1636479523133,<br>
  "latestPrice": 652.66,<br>
  "latestSource": "IEX real time price",<br>
  "latestTime": "12:38:43 PM",<br>
  "latestUpdate": 1636479523133,<br>
  "marketCap": 288341929921,<br>
  "openSource": "official",<br>
  "peRatio": 58.85,<br>
  "previousClose": 651.45,<br>
  "previousVolume": 2887523,<br>
  "primaryExchange": "NASDAQ",<br>
  "symbol": "NFLX",<br>
  "week52High": 690.97,<br>
  "week52Low": 463.41,<br>
  "ytdChange": 0.2066202315388457<br>
}<br>

### Built With
- HTML <br>
- CSS (Flexbox) <br>
- Python<br>

#### [Live](https://artanmerko.github.io/homepage/)
