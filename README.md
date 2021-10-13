# IOS-2021-Tradelog
IOS - 1. Project 2021

Project Tradelog uses data from stock trading and filters through them.

Usage:
       tradelog [-h | --help]
       tradelog [FILTER] [COMMAND] [LOG [LOG2 [...]]
       Possible commands:
       (There can be only one)
       list-tick                  Prints list of all existing tickers.
       profit                     Shows profit from closed positions.
       pos                        Shows value of positions that are currently opened. Sorted by amount from high to low.
       last-price                 Prints last known price for every ticker.
       hist-ord                   Prints histogram of numbers of transactions for given ticker.
       graph-pos                  Prints graph of amount of positions being hold at the moment for given ticker.
       Possible filters:
       (DATETIME stocks in filters is in YYYY-MM-DD HH:MM:SS format)
       -a DATETIME , after:       Program takes information only after given date. (Not including given date).
       -b DATETIME , before:      Program takes information only before given date. (Not including given date)
       -t TICKER                  Program takes information only for given ticker. If there's more tickers than one, program considers all of them.
       -w WIDTH                   Set width of longest line in graph to WIDTH. WIDTH must be a positive whole number. More uses of WIDTH may cause incorrect outputs.
