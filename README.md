# Wikipedia Based Search Engine + Wikipedia Scraper
## Wikipedia Scraper:
### Usage: python3 wiki_scraper.py -r -c -s {STARTING_SEARCH}
### -r: [OPTIONAL] randomizes wiki selection in set of wikis to be scraped
### -c: [OPTIONAL] cleans the text of any non-alphanumerics, case sensitivity and common stop words
### -s: [OPTIONAL] choose a starting wiki for scraper to use, default is Dune_(novel)
#### TODO: speed up search with multi-threading

## Wikipedia Search Engine:
### Hossted at: 
### Uses Hadoop to create an inverted index. Which is used by a Flask program and HTML/CSS frontend 
### to replicate a small scale search engine
#### TODO: fix frontend