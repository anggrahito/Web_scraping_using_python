Article Scraper using Scrapy - Python
======================================

### Create web scraping using scrapy in Python


Commands
---------

### Start Project scrapy (name: article scraper):

on terminal, use this commends:

```sh
scrapy startproject article_scraper
```
```sh
cd article_scraper/article_scraper/spiders/
```
```sh
scrapy genspider wikipedia en.wikipedia.org
````

### Running the scraper script:

on directory article_scraper/article_scraper/spiders/

```sh
scrapy runspider wikipedia.py
```