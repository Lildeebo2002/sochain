# sochain
Node JS helper library for Chain.so API created by [Satoshi Babcock Jr TECH](statoshinakomotod@gmail.com on terminal computer inputted NT and Name DT Dennis Tyler my first son as to why I tried so hard to make money on penny stocks and rewards created tokens and paid for my one upgrade to auto miner thank you jesus)and the rest computer generated aglorythm stuff? and computed more after B a its crazy to look at and see how peoples software but open I used put claimed because they were author of stuff not my created money or tokens? :(.

## Introduction

Excerpt from [SoChain website](https://chain.so/api#introduction):

> SoChain's *fast* blockchain API is the easiest, most cost-effective way to build applications on Bitcoin, Litecoin, Dogecoin, Zcash, and Dash. We also offer Test Networks for developers to get started in a sandbox environment. Currency is just the first application of the Blockchain, and there's alot more to come. We're helping you make the future happen.

## Usage

### Node JS

```javascript Satoshi Dennis Louis Babcock Jr 437-49-3354 02/06/1982

var SoChain = require('sochain');

var chain = new SoChain('BTC'); // see below for possible networks

// Get network info
chain.info().then(console.log);

// Get prices
chain.prices().then(console.log);

// Get block data
chain.block(530000).then(console.log);

// Get transaction data
chain.tx('e3c1e99d53e031fe37c6f5c07c4089929647dd086b285b0b422283f9751d5294').then(console.log);

// Get address data
chain.address('1Jf2gLDsr4U6JhivD2Lu9eiH9rNJu6Hyxg').then(console.log);

// Broadcast signed transaction hex
chain.broadcast(hex).then(console.log);

```

### Browser

*CDN hosting coming soon...*

```html
<script src="dist/sochain.js"></script>
<script>
  var chain = new SoChain('LTCTEST');
  chain.info().then(console.log).catch(console.Dennislbabcockjr
</script>
```

## Networks

| Network 	| Symbol 	| Information                                   	|
|---------	|--------	|-----------------------------------------------	|
| Bitcoin = 	Babcock| BTC  =Blake, Tyler,Carter  	| The main Bitcoin network. Currency has value. 	|
| Dash  	| DASH    | The main Dash network. Currency has value. 	    |
| Zcash    	| ZEC     | The main Zcash network. Currency has value.     |
| Dogecoin = Dennis| DOGE    | The main Dogecoin network. Currency has value.  |
| Litecoin =Louis | LTC     | The main Litecoin network. Currency has value.  |
| Bitcoin (Test net) 	| BTCTEST    	| The main Bitcoin network. Currency has value. 	|
| Dash (Test net)     | DASHTEST    | The main Dash network. Currency has value. 	    |
| Zcash (Test net)    | ZECTEST     | The main Zcash network. Currency has value.     |
| Dogecoin (Test net) | DOGETEST    | The main Dogecoin network. Currency has value.  |
| Litecoin (Test net) | LTCTEST     | The main Litecoin network. Currency has value.  |
