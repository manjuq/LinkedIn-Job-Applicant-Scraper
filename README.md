# LinkedIn Job Applicant Scraper

This project is a web scraper built with Python and Selenium to extract information about job applicants from LinkedIn. It automates the process of gathering data such as name, email, phone number, current title, current company, LinkedIn profile URL, and resume link from job applicants' profiles.

## Usage

To use the scraper, follow these steps:
1. Clone the repository to your local machine.
2. Open the Jupyter Notebook (scraper.ipynb) in your preferred environment (e.g., JupyterLab, Jupyter Notebook).
3. Ensure that you have installed the required dependencies by running pip install -r requirements.txt in your terminal or command prompt.
4. Run the cells in the Jupyter Notebook sequentially.
5. When prompted, enter your LinkedIn username and password as input.
6. The scraper will then proceed to authenticate using the provided credentials and scrape the desired data from LinkedIn.
7. The notebook will guide you through the scraping process and display the extracted data within the notebook interface.
8. You can customize and extend the scraping functionality within the notebook as needed for your specific requirements.

## Features

- Automatically navigates through multiple pages of job applicants.
- Extracts detailed information from each applicant's profile.
- Masks email addresses and phone numbers for privacy when printing.
- Stores extracted data in a list of dictionaries (`applicants_info`).

## Dependencies

- Python 3.x
- Selenium
- BeautifulSoup4

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to expand upon this template by adding more details about your project, such as installation instructions, usage examples, troubleshooting tips, and any other relevant information.
