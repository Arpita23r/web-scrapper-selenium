
# Web Scraper

This is a web scraping project that extracts text, images, and links from a list of websites provided in an Excel file. The scraped data is then saved to a new Excel file for further analysis or use.

## Features

- Scrapes text, image URLs, and hyperlinks from specified web pages.
- Reads a list of URLs from an Excel file.
- Outputs the scraped data into a new Excel file.
- Uses Selenium for web automation and OpenPyXL for Excel file manipulation.

## Technologies Used

- Python
- Selenium
- OpenPyXL
- WebDriver Manager (for ChromeDriver)

## Prerequisites

- Python 3.7 or higher
- Chrome WebDriver
- Excel file with website links

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/sgindeed/your-repo-name.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd your-repo-name
   ```

3. **Install the required packages:**

   ```bash
   pip install selenium openpyxl webdriver-manager
   ```

4. **Ensure you have the Chrome browser installed on your machine.**

## Preparing the Excel File

1. Create an Excel file named `data.xlsx` in the `C:\Users\ASUS\Desktop\project\web scrapper\` directory.
2. In the first sheet named `Sheet1`, enter the website links in the first column starting from the second row.

## Running the Scraper

To run the web scraper, execute the following command in your terminal:

```bash
python your_script_name.py
```

Replace `your_script_name.py` with the name of the Python file containing the scraping code.

The scraped data will be saved in a new Excel file named `result.xlsx` in the same directory.

## Handling Errors

- If the input Excel file (`data.xlsx`) is not found, an error message will be displayed.
- If there is any issue during the scraping process for a specific URL, an error message will be shown.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Selenium](https://www.selenium.dev/) - For web scraping and automation.
- [OpenPyXL](https://openpyxl.readthedocs.io/en/stable/) - For reading and writing Excel files.
```

