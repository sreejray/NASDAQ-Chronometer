Stock Tracker App
```We create a project that you can search stock symbols and see change percentage```

## Warning
You need to get your own api key from ```www.alphavantage.co``` and replace it in index.js file on line 7 and 37 :

##### Line 7 :

```javascript
'https://www.alphavantage.co/query?function=SECTOR&apikey=YOUR_API_KEY'
```

##### Line 37 :

```javascript
'https://www.alphavantage.co/query?function=GLOBAL_QUOTE&symbol=${symbol}&apikey=YOUR_API_KEY'
```
