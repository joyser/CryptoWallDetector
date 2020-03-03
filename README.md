# CryptoWallDetector
Simple javasript tool for monitoring Cryptocurrency buy/sell walls across most exchanges. 

## How it works 
The script uses the browser version of ccxt to get order book info at 5 second intervals and shows any large orders above a threshold value set by the user.
![Demo](https://i.imgur.com/1Llb1N5.png)

## Live version
[Live version](http://cryptowalldetector.com)


### Bitmex and other exchange support.
Unfortunately Bitmex does not work with the browser version of ccxt, however mostly every other exchange should work.

### Cross-Origin proxy requirement
A proxy server is required for ccxt to bypass CORs. Current proxy server is https://cors-anywhere.herokuapp.com/ But feel free to set this to anything you like in the code.

### Major dependency
Thanks to the guys at [ccxt](https://github.com/ccxt/ccxt)  which makes the tool possible.


