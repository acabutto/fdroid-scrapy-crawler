# fdroid-scrapy-crawler
F-droid.org APKs crawler built over scrapy.

The purpose of this crawler is to download the full set of APKs published on [F-droid](https://f-droid.org).

## Dependencies
Please install [scrapy](https://doc.scrapy.org/en/latest/intro/install.html) and its dependencies before running the crawler.

## Usage
Run the crawler by executing the following command line:
`scrapy runspider fdroid_spider.py`

APKs will be saved into ./apks directory.
