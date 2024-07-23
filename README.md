# data-sourcing-challenge

used online resources like chatgpt to find out why my url wouldnt build corretly and found I needed to import quote from the library urllib.parse
from urllib.parse import quote 
I then needed to make sure I use the quote function on the filter_query like so 
quote_query = quote(filter_query)