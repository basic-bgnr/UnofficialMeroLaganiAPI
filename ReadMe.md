# Unofficial Library to Interface with https://www.merolagani.com 
### usage:   
```
>>> import asyncio
>>> from MeroLaganiLib import MeroLaganiAPI
>>> mero_lagani = MeroLaganiAPI()
>>> asyncio.run(mero_lagani.get_scrip_details('nlbbl'))
{'shares_outstanding': 7320000.0, 'sector': 'microfinance', 'one_year_yield': 0.0, 'eps': 6.78, 'book_value': 181.38, 'dividend': 0.0, 'bonus': 22.0, 'right_share': 0.0, 'symbol': 'nlbbl'}
```  
note:- tested on python3.11 (use responsibly)  

