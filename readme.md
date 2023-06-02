
# Table Scraper

Table Scraper is a Python application that allows you to scrape table data from a webpage and store it in a Pandas DataFrame. It utilizes the requests library for making HTTP requests, BeautifulSoup for HTML parsing, and Pandas for data manipulation.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/table-scraper.git
   ```

2. Install the required dependencies using pip:

   ```shell
   pip install -r requirements.txt
   ```

## Usage

1. Update the `config.ini` file:

   The `config.ini` file contains the necessary configuration values for the Table Scraper. Update the following values as per your requirements:

   - `base_url`: The base URL of the webpage to scrape.
   - Any other configuration values specific to your use case.

2. Run the `main.py` script:

   ```shell
   python main.py
   ```

   The script will scrape the table data from the specified webpage and print the resulting DataFrame.

   **Note**: Ensure that you have the necessary permissions to access the webpage and that it contains a table with the required structure.

## Configuration

The `config.ini` file contains the configuration values for the Table Scraper. Update these values according to your needs. Below is an explanation of the available options:

- `base_url`: The base URL of the webpage to scrape. Make sure to include the necessary query parameters if required.

## Contributing

Contributions to Table Scraper are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. When contributing, please follow the existing coding style and guidelines.

## License

Table Scraper is released under the [MIT License](LICENSE).


This version includes sections on installation, usage, configuration, contributing, and licensing. It provides detailed instructions for each step and encourages contributions from other developers.