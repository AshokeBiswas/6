Q1. What is Web Scraping? Why is it Used? Give three areas where Web Scraping is used to get data.
Web Scraping is the process of automatically extracting data from websites. It involves fetching web pages, parsing the HTML, and extracting useful information for further processing or analysis.

Why is it Used?:

Data Collection: Gather large amounts of data from websites quickly and efficiently.
Market Research: Analyze competitors, prices, and market trends by collecting data from multiple sources.
Automation: Automate repetitive tasks, such as checking for updates or retrieving specific information from websites.
Three Areas Where Web Scraping is Used:

E-commerce: To monitor product prices, availability, and reviews from various online stores.
Real Estate: To collect data on property listings, prices, and trends from real estate websites.
Social Media: To gather data on user engagement, trends, and sentiment analysis from social media platforms.
Q2. What are the different methods used for Web Scraping?
Different Methods for Web Scraping:

Manual Copy-Pasting: The simplest form of scraping where data is manually copied from websites. Not scalable or efficient for large datasets.
HTTP Requests: Using libraries like requests in Python to fetch web pages' HTML content.
Parsing HTML: Using libraries like Beautiful Soup or lxml to parse HTML and extract data.
Browser Automation: Using tools like Selenium or Puppeteer to simulate user interactions with websites and extract data.
APIs: Using available APIs provided by websites to access structured data directly.
Q3. What is Beautiful Soup? Why is it used?
Beautiful Soup is a Python library used for parsing HTML and XML documents. It creates a parse tree from page source code that can be used to extract data in a hierarchical and readable manner.

Why is it Used?:

Ease of Use: Simplifies the process of navigating, searching, and modifying the parse tree.
Integration: Works well with other libraries like requests for fetching web pages.
Flexibility: Supports different parsers, including the built-in Python parser and lxml, allowing users to choose based on their needs.
Q4. Why is Flask used in this Web Scraping project?
Flask is used in web scraping projects for several reasons:

Web Interface: To create a web interface that allows users to input URLs, set parameters, and initiate scraping tasks.
API Development: To develop RESTful APIs that can be used to trigger scraping tasks and retrieve the scraped data.
Data Presentation: To present the scraped data in a structured and user-friendly manner through web pages.
Q5. Write the names of AWS services used in this project. Also, explain the use of each service.
Assuming a typical web scraping project, the following AWS services might be used:

Amazon EC2 (Elastic Compute Cloud):

Use: To run the web scraping scripts on scalable virtual servers. EC2 provides the computing resources needed to execute the scraping tasks.
Amazon S3 (Simple Storage Service):

Use: To store the scraped data. S3 offers scalable storage solutions where data can be stored in various formats (CSV, JSON, etc.) and accessed when needed.
Amazon RDS (Relational Database Service):

Use: To store structured data in a relational database. RDS can be used to manage databases like MySQL, PostgreSQL, and others, making it easier to query and analyze the scraped data.
AWS Lambda:

Use: To run scraping scripts without provisioning servers. Lambda functions can be triggered by events, such as HTTP requests or scheduled intervals, to perform scraping tasks.
Amazon SNS (Simple Notification Service):

Use: To send notifications about the status of scraping tasks. SNS can notify users or systems when a scraping task starts, completes, or encounters an error.
AWS CloudWatch:

Use: To monitor the performance and logs of the scraping tasks. CloudWatch can track metrics, collect log files, and set alarms to ensure the scraping tasks run smoothly and identify issues promptly.
