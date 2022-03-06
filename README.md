# IOS-2021-Tradelog
IOS - 1. Project 2021 <br />

Project Tradelog uses data from stock trading and filters through them. <br />

Usage: <br />
       tradelog [-h | --help] <br />
       tradelog [FILTER] [COMMAND] [LOG [LOG2 [...]] <br />
       Possible commands: <br />
       (There can be only one) <br />
       list-tick                  Prints list of all existing tickers. <br />
       profit                     Shows profit from closed positions. <br />
       pos                        Shows value of positions that are currently opened. Sorted by amount from high to low. <br />
       last-price                 Prints last known price for every ticker. <br />
       hist-ord                   Prints histogram of numbers of transactions for given ticker. <br />
       graph-pos                  Prints graph of amount of positions being hold at the moment for given ticker. <br />
       Possible filters: <br />
       (DATETIME stocks in filters is in YYYY-MM-DD HH:MM:SS format) <br />
       -a DATETIME , after:       Program takes information only after given date. (Not including given date). <br />
       -b DATETIME , before:      Program takes information only before given date. (Not including given date) <br />
       -t TICKER                  Program takes information only for given ticker. If there's more tickers than one, program considers all of them. <br />
       -w WIDTH                   Set width of longest line in graph to WIDTH. WIDTH must be a positive whole number. More uses of WIDTH may cause incorrect outputs. <br />
