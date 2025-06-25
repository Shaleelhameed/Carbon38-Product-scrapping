
## Project Overview


This project is built using the Scrapy framework to extract structured product data from the [Carbon38](https://www.carbon38.com) website. The spider navigates through the *Activewear Tops* collection and scrapes key product information.

--
Extracted Fields

- **Product Name**
- **Price**
- **Product URL**

---

Files Included

- `carbon_spider.py` – Core spider logic
- `settings.py` – Scrapy project settings
- `products.csv` – Data in CSV format
- `products.json` – Data in JSON format
- `carbon38_submission.zip` – Zipped full project for submission

---
 How to Run

Run the spider with:

```bash
scrapy crawl carbon
