# Cookie Clicker Bot

This Python script utilizes Selenium to automate clicking the cookie and purchasing upgrades in the "Cookie Clicker" web game.

## Output


https://github.com/sarvesh-2109/Cookie-Clicker/assets/113255836/d0839b30-963f-4159-aff3-f5fa1e2067b7



## Overview

The Cookie Clicker Bot interacts with the Cookie Clicker web game hosted on [Orteil's website](https://orteil.dashnet.org/experiments/cookie/). It continuously clicks the cookie and purchases upgrades to maximize cookie production.

## How It Works

1. **Initialization**: The script starts by launching a Chrome browser using Selenium and navigates to the Cookie Clicker game page.

2. **Clicking the Cookie**: The bot locates the cookie element on the web page and clicks it repeatedly.

3. **Upgrade Purchase Strategy**: Every 5 seconds, the script checks for available upgrades in the store. It extracts upgrade prices and the current cookie count to determine which upgrades are affordable. The bot then selects and purchases the most expensive affordable upgrade.

4. **Bot Termination**: After 5 minutes of operation, the bot stops and retrieves the current cookies per second count.

## Technologies Used

- **Python**: The scripting language used to develop the bot.
- **Selenium**: A Python library for automating web browser interactions.
- **Chrome WebDriver**: The Chrome browser automation tool used by Selenium to control the browser.

## Usage

To use the Cookie Clicker Bot:

1. Ensure you have Python installed on your system.
2. Install the Selenium library using `pip install selenium`.
3. Download the Chrome WebDriver compatible with your Chrome browser version.
4. Adjust the Chrome WebDriver path in the script to match your system.
5. Run the Python script.

## Disclaimer

This bot is for educational purposes only and should not be used to exploit or disrupt online games or services without proper authorization. Use it responsibly and ethically.
