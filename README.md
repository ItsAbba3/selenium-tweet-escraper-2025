# TwitterScraper

TwitterScraper is a Python project that uses Selenium and BeautifulSoup to log in to Twitter, extract user profile information, and collect tweets from a given Twitter user ID.

## Important Notice

- **Educational & Practice Use Only:** This project is intended solely for educational and personal practice purposes. **Do not use this project for any commercial purposes.**
- **Credentials and ChromeDriver Path:**  
  **Before running the script, please update the following in the code:**
  - Your Twitter `username` and `password`.
  - The correct path to your `ChromeDriver` executable.
  
  **Note:** Ensure the version of ChromeDriver matches your installed Google Chrome version. You can download the appropriate version from [ChromeDriver Downloads](https://googlechromelabs.github.io/chrome-for-testing/).

## Features

- Automated login to Twitter.
- Extraction of tweets, user name, and bio from a Twitter profile.
- Scroll automation to load more tweets (up to a specified maximum).
- Save extracted data in a JSON file.

## Requirements

- Python 3.x
- [Selenium](https://pypi.org/project/selenium/)
- [BeautifulSoup4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- Google Chrome browser
- ChromeDriver (ensure that the version of ChromeDriver matches your installed version of Google Chrome)


## Installation

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/yourusername/TwitterScraper.git](https://github.com/ItsAbba3/selenium-tweet-escraper-2025.git)
   cd TwitterScraper
