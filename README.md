# Amazon Price Scraper

This project is a Python-based web scraper designed to fetch product details and track price changes on Amazon. It utilizes various libraries to handle HTTP requests and parse HTML content.

## Project Structure

```
amazon-price-scraper
├── src
│   ├── scraper
│   │   ├── __init__.py
│   │   ├── amazon_scraper.py
│   │   └── price_tracker.py
│   ├── utils
│   │   ├── __init__.py
│   │   └── helpers.py
│   └── main.py
├── tests
│   ├── __init__.py
│   └── test_scraper.py
├── requirements.txt
├── .gitignore
└── README.md
```

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/amazon-price-scraper.git
   ```
2. Navigate to the project directory:
   ```
   cd amazon-price-scraper
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

To run the scraper and start tracking prices, execute the following command:
```
python src/main.py
```

## Features

- Fetch product details from Amazon.
- Track price changes over time.
- Utility functions for making HTTP requests and parsing HTML.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.