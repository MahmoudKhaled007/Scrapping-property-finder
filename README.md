
# Property Finder Scrapper (Training)


This project demonstrates how to scrape data from a real estate website using Python libraries BeautifulSoup4 and Selenium. In this case, we will be scraping data from the Property Finder website.

## Project Dependencies

- Python 3.x
- Beautiful Soup 4
- Selenium
- Pandas
- Joblib

## Getting Started

1. Clone this repository to your local machine.
2. Download a compatible web driver for your preferred browser. We recommend [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/).
4. Enter the path of the downloaded web driver into the `driver_path` variable in the `property_finder_scrapper.ipynb` file.

## How it Works

The scraper uses Selenium to automate browsing the Property Finder website, and Beautiful Soup to parse the HTML data returned. The `scraper.py` script navigates the Property Finder search page by specifying various filters such as location, property type, and price range. Then it iterates through the search results pages, extracts the relevant fields, and writes them to a CSV file, and pkl file.

## Fields Extracted

The scraper extracts the following fields for each property:
- Title
- Location
- Property Type
- Bedrooms
- Bathrooms
- Area (in sqm)
- Price
- Date Added
- Amenties 
- Description


## Important Considerations

When engaging in web scraping, it's important to keep in mind that not all websites allow it. Some sites may block your IP address or take legal action if they detect automated scraping activity.

Additionally, web scraping can put a significant strain on the resources of the website being scraped, which may impact its performance and availability for other users.

Therefore, it's important to always be respectful of the website being scraped, adhere to any terms of use or access policies that they have in place and use appropriate methods to limit the load on their servers.


## Challenges
This website was using HoneyPot Trap for scrappers so, you cannot Request a normal request from Requests library you should act as a normal user thats why i used selenium with user agent

## Pros of this scrapper 
- Deque Algorithm to Reduce memory usage by half comparing to normal python lists 
- Joblib dumb and load to Continue scrapping from the last point if the scrapper interrupted
- Optimized Code 

## Conclusion

This project demonstrates how to scrape data from a real estate website using Python libraries BeautifulSoup4 and Selenium. By following best practices and using appropriate techniques, you can engage in responsible web scraping while minimizing the negative impact on others.
## Authors

- [@MahmoudKhaled007](https://www.github.com/MahmoudKhaled007)


## License

[GNU](https://www.gnu.org/licenses/gpl-3.0.en.html)

