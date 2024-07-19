# Corrected Claim Auto Keyer Bot ( Not an Open Source)

**Technologies:** VBA, Python, BeautifulSoup, Pandas, openpyxl, Tesseract

## Project Overview

The Corrected Claim Auto Keyer Bot is an automation solution developed to streamline the process of integrating modifications from corrected images into original claims using the Facets claim tool. The bot leverages various technologies to enhance efficiency, accuracy, and speed in handling claims data.

## Features

- **Automation Bot Development:** Utilized Python and Pywinauto to create a bot that interacts with the Facets claim tool, ensuring seamless integration of corrected images.
- **Efficient Copy-Pasting:** Implemented Pyperclip to manage copy-pasting operations, enhancing the bot's ability to handle data accurately and swiftly across different interfaces.
- **OCR Technology:** Leveraged Optical Character Recognition (OCR) to identify and target input fields within the Facets application, optimizing data entry and minimizing manual errors.
- **Image Element Identification:** Utilized BeautifulSoup for accurately identifying image elements, improving the bot's precision in data handling.
- **Data Extraction with Tesseract OCR:** Used Tesseract OCR to extract relevant data from the Facets tool, ensuring accurate data capture.
- **Excel Management:** Implemented Openpyxl to manage and document all claim numbers in Excel, maintaining organized and accessible records.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Corrected-Claim-Auto-Keyer-Bot.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Corrected-Claim-Auto-Keyer-Bot
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the main Python script to start the bot:
    ```bash
    python main.py
    ```
2. Follow the on-screen instructions to interact with the bot and the Facets claim tool.

## Dependencies

- Python
- Pywinauto
- Pyperclip
- BeautifulSoup
- Pandas
- openpyxl
- Tesseract OCR

