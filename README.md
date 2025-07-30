# zkscraper
zkscraper is an open source automated tools. It allows you to scrape all jobs on Jobstreet website.

## Getting Started
1. `python -m venv venv` only for first time
2. `source venv/bin/activate`
3. `pip install -r requirements.txt` to install all necessary packages. For any additional packages installed, update the requirements file as such `pip freeze > requirements.txt`
4. Install chromedriver.exe based on your google chrome version.
5. Modify `keywords`, `headers`, and `path` in `zkscraper.py` based on your own local environment.
6. Run `python zkscraper.py` in the terminal to run the program.
