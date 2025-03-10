Amazon Price Tracker
A Python script that scrapes Amazon product prices and sends an email alert when the price drops below a specified threshold.

Features
Scrapes product title & price from an Amazon product page
Sends an email notification when the price falls below a set amount
Uses .env file for secure credential storage
Bypasses bot detection with custom headers
Technologies Used
Python 🐍
requests & BeautifulSoup for web scraping
smtplib for email automation
dotenv for environment variable management
How It Works
Set the product URL in main.py.
Define a price threshold for alerts.
Run the script, and if the price is lower than expected, an email is sent.
