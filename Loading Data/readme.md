# Reading files into pandas #

This seems to be an evolving area of Pandas development.

   - For reading and writing csv files, see "Reading csv files.ipynb"
   - JSON files are best read using standard Python code and then converted into a `DataFrame` directly.
   - For writing web scrapers, I cannot recommend [Requests](http://docs.python-requests.org/en/master/) enough.
   - Furthermore, see [The Hitchhiker's Guide To Python: Web Scraping](http://docs.python-guide.org/en/latest/scenarios/scrape/).  They recommend [lxml](http://lxml.de/) as a parsing tool.  Having done such work in Java, I'd recommend getting some good tools.  You might also consider [html5lib](https://github.com/html5lib/html5lib-python).
   - Similarly, to read data from a database, use one of the many python libraries built to interact with databases.  I've used the mongoDB driver, and it's very easy.