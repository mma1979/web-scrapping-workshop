## Web Scrapping using PyQuery
<img src="https://github.com/mma1979/web-scrapping-workshop/raw/master/web_scrapping.PNG" alt="Web Scrapping"/>

### Agenda:
<ul>
<li>What is Web Scraping?</li>
<li>What do I use for web scraping?</li>
<li>Are there any challenges I may want to know about?</li>
<li>What should I do to scrape some websites?</li>
<li>How does that look like in practice?</li>
<li>Code Time</li>
<li>Conclusion</li>
<li>What’s Next?</li>
<li>Thank You</li>
</ul>

### What is Web Scraping?
<p>
Web scraping is an art which is use to make data gathering automated and fast. Web scraping is also known as Web Data Extraction, Web Content Extraction, Web Harvesting, Web Data Grabbing, Web Data Mining and Screen Scraping.

</p>

### What do I use for web scraping?
<ul>
<li>Separate services that work through an API or have a web interface (Embedly, DiffBot etc.)</li>
<li>Various open source projects implemented in different programming languages (Python: Goose, Scrapy; PHP: Goutte; Ruby: Readability, Morph, etc.).</li>
<li>Also, you can always make your own web scraping tool. Luckily, there are plenty of libraries available. For example, you can use the Pyquery library to make a Python-based scraper.</li>
<li></li>

</ul>

### Are there any challenges I may want to know about?
<ul>
<li>Most of the websites are simply different layout-wise.</li>
<li>Amateurs or pros, not all web developers follow style guides. As a result, their code often contains various mistakes making it absolutely unreadable for scrapers.</li>
<li>Many websites are built with HTML5 in which any element can be unique.</li>
<li>Content copy protection, e.g. a multi-level layout, using JavaScript for content rendering, user-agent validations etc.</li>
<li>Depending on either the season of the year or the subject of the content itself, some websites can change their layouts. Keeping up with these changes requires a lot of time and effort.</li>
<li>The abundance of ads, floods of comments, too many navigation elements, etc.</li>
<li>In the web page code, there can be links to the same images of different size, e.g. image preview.</li>
<li>Since the choice of language on most of the websites is based on your location, the content may not always be displayed in English.</li>
<li>Websites can have their own encoding that is impossible to send back with a request.</li>
</ul>

### What should I do to scrape some websites?
<ul>
<li>If the number of websites you’re going to scrape the data from is small, it’s better to write your own scraper and customize it according to each specific website. The quality of the output content should be 100%.</li>
<li>If the number of websites to scrape goes beyond “small”, we suggest using a complex approach. In this case, the output content quality should be close to 95%.</li>
</ul>

### How does that look like in practice?
<p>
First, you would need to create a mechanism to receive HTML code with a GET request. Next, inspect the DOM structure of the website to identify the nodes containing the target data. After that, create a node processor to output the data in a normalized format. The choice of format is usually based on either your client’s requirements or your data processing preferences. For example, we use JSON. And that’s pretty much it — you can create the scraping system.

</p>
<p>
You need to know about <a href="https://www.w3schools.com/cssref/css_selectors.asp">CSS selectors</a>, which will allow you to query the DOM of the HTML you have got, to get the exact values you need.
</p>

### What’s Next?
<ul>
<li>Web Automation</li>
<ul>
<li>By time you will find some circumstance which will required to don an action at the page to get data, so you will need Selenium</li>
<li>For this part I recommend the course Provided By my Friend Abu Bakr Soliman https://www.youtube.com/playlist?list=PLvLvlVqNQGHD1XUJSYfYezvs9gLdaWHId</li>
</ul>
<li>Data Cleaning</li>
<ul>
<li>You will need some NLP skills to clean your text data</li>
</ul>
<li>Data Visualization</li>
<ul>
<li>Statistics and visualization is a main part of Data Science, which will covered by my colleague Dr. Emmad Tolba in next session.</li>
</ul>
</ul>

## Thank You

### Mohammed Abdelhay
<ul>
<li>Email:       mohammed_abdelhay@pg.cu.edu.eg</li>
<li>Mobile:    +201008983687</li>
<li>LinkedIn:  https://www.linkedin.com/in/mohammed-abdelhay/</li>
<li>GitHub:     https://github.com/mma1979</li>
</ul>
