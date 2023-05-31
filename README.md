# Web-Crawling-Practice

This repository contains a script written in Python for crawling news articles from the VnExpress website using Selenium and ChromeDriver. The script follows these steps:

## 1. Initialize the Browser
The script initializes a Google Chrome browser using Selenium's ChromeDriver. It sets specific options for the browser, such as running in headless mode and disabling the sandbox.

## 2. Create a Folder
A folder is created to store the scraped articles. If a folder with the same name already exists, it is removed to ensure a clean start.

## 3. Retrieve Article URLs
The script accesses the table page of the VnExpress website to retrieve the URLs of the articles. It uses XPath to locate the specific elements containing the URLs.

## 4. Extract Article Content
For each article URL, the script accesses the corresponding article page. It locates the necessary elements, such as the title, description, content, and author, using XPath expressions.

## 5. Retrieve Article Content
The script extracts the content of the article, which may consist of multiple paragraphs. It retrieves the paragraphs using XPath and stores them in a list.

## 6. Save Article to .txt File
The extracted article content, including the title, description, content, and author, is saved to a .txt file. Each article is saved as a separate file with a unique filename.

## 7. Repeat for Multiple Pages
The script allows crawling data from multiple pages. The number of pages to crawl can be specified, and the script loops through each page to scrape the articles.

By following these steps, the script efficiently scrapes news articles from the VnExpress website and saves them to a designated folder for further analysis or processing.
