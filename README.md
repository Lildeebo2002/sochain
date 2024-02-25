# sochain Dennis=Dodgecoin Louis=Litecoin Babcock=Bitcoin & BTC=Blake, Tyler, Carter we always picked names ahead lmao sorry I became a forman at STOCK ROOFING CO Mn and was so busy I left computer sit till a Bad De as so after opening trying to proof Satoshi again Like 2002 I got shot 10 years prison by cops again almost killed and I believe in purpose they stole wallets paper on cam Arden hills and then Blaine Lexington almost shot by a honest cop due to a scary cop trying to distract me like something that never even in a movie happens then he gets mad don't work goes to computer knocks cam off then does something to it or slammed not sure but scared and limo bad ignored for 4 years and even agreed to it being true on cam then forced and scammed to leave our house to be as if bad dope heads by them ignoring safety so bad it's scary I so resumed for days for help being to extresm levels ignored only to wait till a missed court date and within hours arresting me not even heard of to steal house thstvis and has been recorded as 100 percent free of all loans and defaults since 2016 on there updated site and still I'm homeless lost kids due to even worse an ok a violating Supreme Court laws they cover up and have not stopped pulling me and Amy over since harrssing scary to say but it's got to be a paid thing again after I start looking and open wallets and move money dormant whales ten plus me Dennis Louis Babcock Jr Minnesota military please take computer stuff and help me prove to save my life and family before I'm put in prison or killed please .I'm hungry homeless and staying with any that don't want me here in scared and terrified all say crazy but 3 to 4 years of proof of work again?:(
Node JS helper library for Chain.so API created by [GAFO TECH](https://gafo.tech).

## Introduction

Excerpt from [SoChain website](https://chain.so/api#introduction):

> SoChain's *fast* blockchain API is the easiest, most cost-effective way to build applications on Bitcoin, Litecoin, Dogecoin, Zcash, and Dash. We also offer Test Networks for developers to get started in a sandbox environment. Currency is just the first application of the Blockchain, and there's alot more to come. We're helping you make the future happen.

## Usage

### Node JS

```javascript

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
  chain.info().then(console.log).catch(console.error)
</script>
```

## Networks

| Network 	| Symbol 	| Information                                   	|
|---------	|--------	|-----------------------------------------------	|
| Bitcoin 	| BTC    	| The main Bitcoin network. Currency has value. 	|
| Dash     	| DASH    | The main Dash network. Currency has value. 	    |
| Zcash    	| ZEC     | The main Zcash network. Currency has value.     |
| Dogecoin  | DOGE    | The main Dogecoin network. Currency has value.  |
| Litecoin  | LTC     | The main Litecoin network. Currency has value.  |
| Bitcoin (Test net) 	| BTCTEST    	| The main Bitcoin network. Currency has value. 	|
| Dash (Test net)     | DASHTEST    | The main Dash network. Currency has value. 	    |
| Zcash (Test net)    | ZECTEST     | The main Zcash network. Currency has value.     |
| Dogecoin (Test net) | DOGETEST    | The main Dogecoin network. Currency has value.  |
| Litecoin (Test net) | LTCTEST     | The main Litecoin network. Currency has value.  |
