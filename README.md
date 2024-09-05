# FreeImages Dog Image Scraper

## Description

This script automates the process of downloading dog images from FreeImages.com. It navigates through multiple pages of search results for "dog" images or what you want only chang src, extracts image URLs, and saves the images locally.

## Features

- Scrapes multiple pages of search results
- Uses BeautifulSoup for HTML parsing
- Handles SSL certificate verification
- Saves images with unique filenames including page numbers

## Requirements

- Python 3.x
- BeautifulSoup4
- Requests
- lxml

## Installation

1. Clone this repository or download the script.
2. Install the required packages:

```
pip install beautifulsoup4 requests lxml
```

## Usage

1. Run the script:

```
python image_scraper.py
```

2. The script will create an 'images' folder in the same directory and download images into it.

## Configuration

You can modify the following variables in the `main()` function:

- `save_folder`: Change the name of the folder where images are saved
- `base_url`: Change the search URL if you want to scrape different images
- `num_pages`: Adjust the number of pages to scrape

## Important Notes

- This script is for educational purposes only. Always respect the terms of service of the websites you're scraping.
- FreeImages.com may have restrictions on automated downloads. Use this script responsibly and in accordance with their policies.
- The script uses `ssl._create_unverified_context()` which bypasses SSL certificate verification. This can be a security risk in production environments.

 
