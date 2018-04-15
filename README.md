# cryptocurrencytools.org
Open Source JavaScript Client-Side toolset for multisig address generation and other things.

With this set of tools you can generate 2 of 3 multisig addresses for Monero and Bitcoin
without the need to download the Blockchain or using the command line wallets.

cryptocurrencytools.org provides an all-in-one HTML document with embedded
JavaScript/CSS/Images. Just download the HTML file and run it locally. 
No Internet connection is needed. The code is published on GitHub.

Please send DONATIONS for this project to ony of the following addresses:
* Bitcoin: 3FoAsyP4xugwDRten5K2twCby73ykTwuHM or bc1q0axyvcjy5ey57jcug98pd6cf8n69mv5mk82783
* Monero: 48kTWUFTXPk9ELgJizvGciEvRZeWogEU5eZSZudcRcL3VagcZBg4zRLhSAs1VYFAMVUx1BwT14sd7LVrfygVG6CuA4z23Gk

cryptocurrencytools.org is available under The MIT License (MIT)
Copyright (c) 2018 cryptocurrencytools.org

## Features

### Bitcoin:
* Generate addresses (Legacy, SegWit, Bech32 format)
* Generate brain wallet addresses
* Generate 2 of 3 multisig address (Legeacy, SegWit, Bech32 format)
* Convert private keys into SegWit and Bech32 format for Electrum import

### Monero:
* Generate wallets
* Generate brain wallets
* Generate 2 of 3 multisig address
* Calculate subaddresses for a given wallet

### Upcoming features:
* I will continue to extend and improve this toolset.
* Feel free to request additional features and improvements!  

## Usage:
* Download cryptocurrencytools.zip from https://github.com/cryptocurrencytoolsdotorg/cryptocurrencytools.org/
* Verify the signature
  `gpg --verify cryptocurrencytools.zip.sig cryptocurrencytools.zip`  
* Run locally (without Internet connection)

## Credits:
* jQuery: v3.3.1: https://jquery.com/
* BigInteger: v0.9.1: http://silentmatt.com/biginteger/
* js-sha3: v0.7.0: https://github.com/emn178/js-sha3/
* BitcoinJS: v3.3.2: https://github.com/bitcoinjs/bitcoinjs-lib
* CSS Normalize: v8.0.0: https://necolas.github.io/normalize.css/
* Loading spinner: v1.2.5: http://tobiasahlin.com/spinkit/
* Mymonero core js: https://github.com/mymonero/mymonero-core-js/
* Cryptonote address tests: https://github.com/luigi1111/xmr.llcoins.net
* Moneroaddress.org: https://github.com/moneromooo-monero/monero-wallet-generator/

## PGP Key:
```
-----BEGIN PGP PUBLIC KEY BLOCK-----

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
sBkWLUCse80HcKQYNKnt1qeFuZE=
=PZZp
-----END PGP PUBLIC KEY BLOCK-----
```