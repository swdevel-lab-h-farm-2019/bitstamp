## Implementation of a Bitcoin price checker


In this repository you can find a file named ```bitstamp``` that implements the ```get_price(currency)``` function. It queries the ```bitstamp``` bitcoin exchange to receive the current BTC price in Euro or in U.S. Dollars, depending on the currency input parameter. This function is used in the ```main.py``` file to obtain the last price in both currency. If you run the program, executing the main file with: ```python main.py``` it will  give you results similar to the following: 

```
$ python main.py 
Last bitcoin price in EUR is: 7918.97
Last bitcoin price in $ is: 8720.53

```

Note that the project requires the ```json``` and ```requests``` module to run. [Bitstamp](www.bitstamp.com) is an on-line exchange that offers open APIs to access prices of various cryptocurrencies. The APIs are documented in a [API documentation page](https://www.bitstamp.net/api/) and can be accessed up to 8000 times in ten minutes. 

