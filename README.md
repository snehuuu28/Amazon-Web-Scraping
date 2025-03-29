# Amazon Web Scraping: Laptops & iPhone Reviews  

## Overview  
This project automates the extraction of **laptop product details** and **iPhone customer reviews** (including **iPhone 15 and iPhone 16**) from **Amazon** using Python, leveraging **BeautifulSoup** and **Selenium**. The scraped data is structured and stored in CSV format for further analysis.  

## Features  
✅ Scrapes **laptop product details** (name, price, rating, specifications, etc.)  
✅ Scrapes **iPhone customer reviews** (**iPhone 15 & iPhone 16**: review text, rating, date, user details, etc.)  
✅ Handles **pagination** to scrape multiple pages efficiently  
✅ Saves data in **CSV format** for analysis  
✅ Supports **BeautifulSoup** and **Selenium** for handling dynamic content  
✅ Enables **trend analysis** of laptop pricing and iPhone customer sentiment  
✅ Useful for **competitive research and pricing strategies**  

---

## Why Web Scraping?  
Web scraping is a powerful technique for extracting valuable information from websites. It enables:  
- **Price tracking**: Monitor price fluctuations over time.  
- **Sentiment analysis**: Analyze customer feedback on products.  
- **Market research**: Gather competitive intelligence on pricing and specifications.  

### Ethical Considerations  
When scraping websites, it is crucial to adhere to ethical guidelines:  
✔ **Respect `robots.txt`**: Always check if scraping is allowed.  
✔ **Avoid excessive requests**: Use delays (`time.sleep()`) to prevent server overload.  
✔ **Use data responsibly**: Scraped data should not be misused for commercial gain.  
✔ **Acknowledge data ownership**: The information belongs to Amazon and its users.  

---

## Usage  

### 1️⃣ Scrape Laptop Products  
```bash
jupyter notebook Laptop_Products.ipynb
```
The scraped data will be saved as [`data/Laptop Products.csv`](https://github.com/snehuuu28/Amazon-Web-Scraping/blob/main/data/Laptop%20Products.csv).  

[View Laptop Scraper Notebook](https://github.com/snehuuu28/Amazon-Web-Scraping/blob/main/Laptop_Products.ipynb)  

### 2️⃣ Scrape iPhone 15 Reviews  
```bash
jupyter notebook Iphone15_Review.ipynb
```
The scraped data will be saved as [`data/Iphone 15 Amazon Reviews.csv`](https://github.com/snehuuu28/Amazon-Web-Scraping/blob/main/data/Iphone%2015%20Amazon%20Reviews.csv).  

[View iPhone 15 Review Scraper Notebook](https://github.com/snehuuu28/Amazon-Web-Scraping/blob/main/Iphone15_Review.ipynb)  

### 3️⃣ Scrape iPhone 16 Reviews  
```bash
jupyter notebook Iphone16_Review.ipynb
```
The scraped data will be saved as [`data/Iphone 16 Amazon Reviews.csv`](https://github.com/snehuuu28/Amazon-Web-Scraping/blob/main/data/Iphone%2016%20Amazon%20Reviews.csv).  

[View iPhone 16 Review Scraper Notebook](https://github.com/snehuuu28/Amazon-Web-Scraping/blob/main/Iphone16_Review.ipynb)  

---

## Project Structure  
```
Amazon-Web-Scraping/
│── Laptop_Products.ipynb           # Scrapes laptop details from Amazon
│── Iphone15_Review.ipynb           # Scrapes iPhone 15 reviews from Amazon
│── Iphone16_Review.ipynb           # Scrapes iPhone 16 reviews from Amazon
│── README.md                       # Project documentation
│── data/                           
│   ├── Laptop Products.csv         # Scraped laptop data
│   ├── Iphone 15 Amazon Reviews.csv  # Scraped iPhone 15 reviews
│   ├── Iphone 16 Amazon Reviews.csv  # Scraped iPhone 16 reviews
```

---

## Notes  
⚠ **Disclaimer:** This project is for educational purposes only. Scraping Amazon may violate its **terms of service**.  
🔹 Use **headers** and **request delays** (`time.sleep()`) to reduce the risk of getting blocked.  
🔹 For JavaScript-loaded content, **Selenium** is recommended over BeautifulSoup.  
🔹 The extracted data can be leveraged for **price monitoring, sentiment analysis, and competitor analysis**.  

---

