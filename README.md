# IMDb Top 250 Scraper

This Python project scrapes IMDb's Top 250 movies and exports the data to an Excel file. Due to certain limitations, this script currently scrapes only the first 25 movies. The data includes the movie ranking, name, release year, duration, and IMDb rating.

## Project Structure


- `imdb_top250_scraper.py` Main Python script to scrape IMDb and export data to Excel.
- `Top250.xlsx` Output Excel file with scraped data (generated by the script)

## Requirements

To run this project, you need the following Python packages:

-   `requests`
-   `beautifulsoup4`
-   `lxml`
-   `pandas`
-   `openpyxl`

You can install them using pip:

```bash
pip install requests beautifulsoup4 lxml pandas openpyxl
```

## How to Run

1.  Clone this repository.
2.  Install the required dependencies.
3.  Run the `imdb_top250_scraper.py` script. This will generate an Excel file (`Top250.xlsx`) containing the scraped data.

```bash
python imdb_top250_scraper.py 
```
## Note

-   This script scrapes only the first 25 movies from the IMDb Top 250 list. Due to certain issues, the complete list of 250 movies could not be scraped at this time.
