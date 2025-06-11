# eBay Scraper Project

## Description
The `eBay Scraper` project is designed to retrieve product data from the eBay platform based on defined search criteria. The application is written in Python, using the Flask framework, and communicates with a MongoDB database that stores the scraping results.

## Features
- Search for products on eBay according to criteria such as price, product name, and shipping options.
- Save search results to a MongoDB database.
- Filter saved results based on price and other options.

## Technologies
- Python 3.12
- Flask
- MongoDB
- Docker
- BeautifulSoup4
- PyMongo

## Installation
To run the project locally, follow these steps:

1. Clone the repository:

	https://github.com/Jagoda150/Scraper-Ebay

2. Run the MongoDB and Flask servers using Docker Compose:

	docker-compose up --build


## Usage

To use the application, go to your web browser and enter the address:

  https://localhost:27017/

## Database GUI managment

To manage your database from GUI tool (e.g noSQLBooster, MongoDB Compass), connect them to the address:

  http://localhost:27017/

## License

This project is available under the MIT license.

## Authors
- Jagoda150
- Kajciuch
