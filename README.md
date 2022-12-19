# TrCurrency

This library supporting version 13, 14, 15

## Install

`npm i tr-currency`

## Code usage

This package have an standalone pipe. If you wanto use it you have to add this standalone pipe your standalone component module or your module `TrCurrencyPipe` then you have this pipe. Just add your code, example `{{money | trCurrency}}`.

Output: `14505.50 ==> 14.505,00 ₺`
If you dont want to use ₺ symbol, you can use parameter that.

Example: `{{money | trCurrency: '$'}}`