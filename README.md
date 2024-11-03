## Dynamic PDF reports with Jinja and Playwright/Puppeteer

To generate a PDF with some dummy data, run `python3 homepage-banners-report.py`. The command writes dynamically-generated html to a file and renders the html file to pdf using the Playwright Python library. 
To use the JS Puppeteer library to render html to pdf, run `node render-pdf.mjs`.

To use real data, update the get_context function in the `homepage-banners-report.py` file.

