# Web Scraping - tiendeo.co.id - Indomaret and Alfamart
<p align="center">
  <img width="200" height="200" src="https://play-lh.googleusercontent.com/xd6wHVA1e4FJS3A1NtbbifQhYLSVzspYTvRZfKH4ZT8cdiirSzTWIzJMn3qXOsz08C0=s180-rw">
</p>
Tiendeo is the most popular app among consumers looking for brochures and store deals in their area.Present in 44 countries, over 10 million users worldwide use it daily to save on their purchases. The Tiendeo portal focuses on digitizing and geolocating catalogs and offers from retailers. Tiendeo has been downloaded 4 million times and the website has more than 25 million unique users.

# What is Web Scraping?
Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites. Web scraping a web page involves fetching it and extracting from it. Fetching is the downloading of a page (which a browser does when a user views a page). Therefore, web crawling is a main component of web scraping, to fetch pages for later processing. Once fetched, then extraction can take place. The content of a page may be parsed, searched, reformatted, its data copied into a spreadsheet or loaded into a database. Web scrapers typically take something out of a page, to make use of it for another purpose somewhere else. An example would be to find and copy names and telephone numbers, or companies and their URLs, or e-mail addresses to a list (contact scraping).

# Web Scraping Techniques
In general, there are two ways you can do this:
- Manual: a method where you copy data by copy-pasting from a website
- Automatic: a method that uses code, an application, or a browser extension.

Web scraping is now made easier with the help of browser extensions and applications. There are six commonly used web scraping techniques, namely:
1. Copying data manually
2. Using regular expressions
3. HTML parse
4. Analyze DOM
5. Using XPath
6. Using Google Sheets

# Benefits and Problems of Web Scraping
Following are the four main advantages:
1. Getting Leads
2. Comparing Massive Data
3. Optimization of Reviews, Product Pricing and Service
4. Looking for Company Information

Although web scraping is a very helpful technique in extracting site data, there are also problems to its implementation. At least, the following five things you need to remember if you want to do it:
1. No web scraping technique is 100% effective
1. The data obtained is not always neat
1. Understanding of the structure of the website page remains an obligation
1. Your access to a website may be blocked
1. Not all websites are easy to extract data

# About The Project
The major goal of this project is to collect information on the names of Indomaret and Alfamart stores in two cities: East Jakarta and Jember City, where each minimarket is given its full address. The web scraping process can be obtained from the tiendeo.co.id site, then the data that has been accommodated in the data frame will be extracted into a dataset and exported as excel and CSV files.

# Built with
- [**pandas**](https://pandas.pydata.org/)
- [**NumPy**](https://numpy.org/)
- [**Request**](https://docs.python-requests.org/en/latest/)
- [**Beautiful Soup**](https://beautiful-soup-4.readthedocs.io/en/latest/)

# Getting Started
Beautiful Soup is a Python library for pulling data out of HTML and XML files. It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree. It commonly saves programmers hours or days of work. While the Requests allows you to send HTTP/1.1 requests extremely easily. There’s no need to manually add query strings to your URLs, or to form-encode your POST data. Keep-alive and HTTP connection pooling are 100% automatic, thanks to urllib3.

Read more for [**Beautiful Soup documentation**](https://beautiful-soup-4.readthedocs.io/en/latest/) and [**Request documentation**](https://docs.python-requests.org/en/latest/)
### **Prerequisites**
Here is how to run the library used in this project. First Install the list of libraries below on your device or kernel:
- Beautiful Soup <br>
  ```
  pip install beautifulsoup4
  ```
- Request <br>
  ```
  pip install requests
  ```
