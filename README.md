# TrCurrency

This library supporting Angular version 13, 14, 15

## Install

`npm i tr-currency`

## Code usage

This package have an standalone pipe. If you want to use it you have to import `TrCurrencyPipe` your standalone component or your module.

Example:
`
imports: [ 
    TrCurrencyPipe
]
`

Use:
`{{money | trCurrency}}`.

Output: `14505.50 ==> 14.505,00 ₺`
Note: If you dont want to use `₺` symbol, you can use parameter that.

Example: `{{money | trCurrency: '$'}}`