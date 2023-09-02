# LinkedIn Profiles Finder 🎯

This Python script finds LinkedIn profiles based on company names and job titles. It uses Google Dorks queries to search for LinkedIn profiles and extracts names, job titles, and LinkedIn profile links.

## Getting Started 🚀

1. **Python Installation:** Ensure you have Python installed on your machine.

2. **Library Installation:** Install the required libraries by running the following command:

   ```bash
   pip install requests beautifulsoup4 httpx pandas
   ```

3. **Prepare Your Data:**
   Create a CSV file containing companies name.

## Usage 📋

Customize Queries: Customize the queries list with the job titles you want to search for.

```bash
queries = ["CEO", "Digital Marketing Manager", "Product", "Whatever you want"]
```

Specify CSV Details: Specify the name of your CSV file and the column where the company names are located.

```bash
csv_file = "your_companies.csv"
companies_name_column = "company_name_column"
```

Start Scraping: Run the script to start scraping LinkedIn profiles with the following command:

```bash
python linkedin.py
```

The script will initiate the scraping process and generate a JSON file with every companies and related LinkedIn profile information.

## Features ✨

- Searches and scrapes LinkedIn profiles based on company names and job titles.
- Filters out irrelevant search results.
- Extracts names, job titles, and LinkedIn profile links.
- Outputs the results in a JSON file.

## Customization 🛠️

You can customize the script by adjusting the queries, CSV file details, or other parameters to fit your specific requirements.

## Credits 🙌

- The script uses the requests library for making HTTP requests.
- HTML parsing is performed using BeautifulSoup.
- Google Dorks queries are used for LinkedIn profile searches.
- Data processing and output are managed with pandas.
- This is an updated version of [@Rreddington\_](https://twitter.com/Rreddington_)'s script

## Author 👤

[titi]
