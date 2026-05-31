# seo-analysis-tool

[![Link Check](https://github.com/hihipy/seo-analysis-tool/actions/workflows/links.yml/badge.svg)](https://github.com/hihipy/seo-analysis-tool/actions/workflows/links.yml)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**Built with**

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![requests](https://img.shields.io/badge/requests-2C2D72?style=flat&logoColor=white)](https://requests.readthedocs.io)
[![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-0E7C61?style=flat&logoColor=white)](https://www.crummy.com/software/BeautifulSoup/)
[![pdfkit](https://img.shields.io/badge/pdfkit-EC1C24?style=flat&logoColor=white)](https://pypi.org/project/pdfkit/)
[![markdown2](https://img.shields.io/badge/markdown2-000000?style=flat&logo=markdown&logoColor=white)](https://pypi.org/project/markdown2/)

A Python tool for SEO analysis that generates PDF reports. Analyzes title tags, meta descriptions, link structure, image alt tags, mobile-friendliness, load time, and more.

## Features

**SEO Analysis:**
- Title and meta description evaluation
- Word count analysis
- Link structure assessment
- Image alt tag checking
- Mobile-friendly detection
- Load time measurement
- Canonical tag verification

**PDF Reports:**
- Detailed metric explanations
- Custom formatting
- Automated recommendations
- Saved to Downloads folder

**Other:**
- Real-time logging
- Error handling
- Command-line interface

## Requirements

Python 3.6+ and the following libraries:

```bash
pip install requests beautifulsoup4 pdfkit markdown2
```

You also need wkhtmltopdf installed:

- **macOS:** `brew install wkhtmltopdf`
- **Ubuntu:** `sudo apt-get install wkhtmltopdf`
- **Windows:** Download from [wkhtmltopdf downloads](https://wkhtmltopdf.org/downloads.html)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/hihipy/seo-analysis-tool.git
cd seo-analysis-tool
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the script:
```bash
python seo_analyzer.py
```

## Usage

1. Run the script
2. Enter the URL when prompted
3. Wait for analysis to complete
4. Find the generated PDF report in your Downloads folder

## Analyzed Metrics

The tool analyzes these SEO metrics:

- Page Title
- Meta Description
- Word Count
- Total Links
- Alt Tags
- H1 Tags
- Mobile Friendliness
- Canonical Tags
- Load Time

## Technical Details

- **HTML Parsing:** BeautifulSoup4 for webpage analysis
- **PDF Generation:** pdfkit with wkhtmltopdf backend
- **Logging:** Logging system for debugging
- **Error Handling:** Handles various edge cases

## Acknowledgments

- [BeautifulSoup4](https://www.crummy.com/software/BeautifulSoup/) - HTML parsing
- [pdfkit](https://pypi.org/project/pdfkit/) - PDF generation
- [requests](https://docs.python-requests.org/) - HTTP requests
- [markdown2](https://pypi.org/project/markdown2/) - Markdown processing

## License

This project is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

You are free to:
- Use, share, and adapt this work
- Use it at your job

Under these terms:
- **Attribution** — Credit the original author
- **NonCommercial** — No selling or commercial products
- **ShareAlike** — Derivatives must use the same license
