## Dynamic PDF reports with Jinja and Playwright/Puppeteer

### Install dependencies:
**Python**
1. [`pip3 install pytest-playwright`](https://playwright.dev/python/docs/intro#installing-playwright-pytest)
2. [`pip3 install Jinja2`](https://jinja.palletsprojects.com/en/stable/intro/#installation)

**JS**
1. `yarn install` or `npm install`

### Generate PDF
**Python**  
To generate a PDF with some dummy data:  `python3 homepage-banners-report.py`.  
The command writes dynamically-generated html to a file and renders the html file to pdf using the Playwright Python library. 

**JS**  
To use the JS Puppeteer library to render html to pdf: `node render-pdf.mjs`.  

To use real data, update the `get_context` function in the `homepage-banners-report.py` file.

