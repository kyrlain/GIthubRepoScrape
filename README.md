# GithubRepoScrape
This project will scrape the top 15 repositories, based on the number of stars today. This project is written in python with jupyter notebook. The scraping mechanism is written using the `requests` and `BeautifulSoup` modules. The dataframes is then loaded to a `SQLite` database and a `csv` file.

## Running the notebook
To run the notebook, an environment must be created and activated first. RUn the following commands
```
python -m venv .venv
source .venv/Scripts/activate
```
Next is to set the `.venv` as the kernel for the notebook.

Then run the cells in the notebook.

Once done, the `SQLite` database `github.db` and the `csv` file `github_table.csv` should be updated.

Sample queries is also included in the notebook to obtain the following:
- Top 10 Repositories based on number of Stars
- Top 10 Starred Repositories today
- Top 10 Programming Languages