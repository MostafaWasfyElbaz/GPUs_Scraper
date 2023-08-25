# GPUs_Scraper
This is a simple Python script that scrapes GPU information from Newegg's website based on user input and stores the data in a CSV file. It utilizes the BeautifulSoup library for web scraping.

## Usage
Install the required libraries by running the following command:

    pip install beautifulsoup4 requests

Run the script gpu_scraper.py using the command:

    python gpu_scraper.py

The script will prompt you to input the GPU you need. It will then scrape Newegg's website for GPUs matching your input and store the names and prices in a CSV file called GPU_Details.csv.

## Requirements
  <span style="font-size: 2em; line-height: 0; vertical-align: middle;">&bull;</span> Python 3.x

  <span style="font-size: 2em; line-height: 0; vertical-align: middle;">&bull;</span> beautifulsoup4

  <span style="font-size: 2em; line-height: 0; vertical-align: middle;">&bull;</span > requests

## Project Structure
<span style="font-size: 2em; line-height: 0; vertical-align: middle;">&bull;</span > gpu_scraper.py: The main Python script containing the web scraping logic.

<span style="font-size: 2em; line-height: 0; vertical-align: middle;">&bull;</span > GPU_Details.csv: The CSV file where the scraped GPU information will be stored.

<span style="font-size: 2em; line-height: 0; vertical-align: middle;">&bull;</span > README.md: This file, providing information about the project.

## License
This project is licensed under the MIT License

Feel free to use, modify, and distribute this code as needed.

## Disclaimer

This project is intended for educational purposes and personal use. Make sure to review and comply with the terms of use of any website you are scraping. Respect website terms and conditions and do not use this script for any malicious or unauthorized activities.
