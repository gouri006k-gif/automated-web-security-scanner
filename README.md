# Automated Web Security Header Scanner

## Project description
This beginner-friendly defensive cybersecurity tool checks selected HTTP security headers returned by a website. It reports whether each header is present and briefly explains its purpose.

## Problem statement
Security-related HTTP response headers can help websites reduce browser-side risks. Manually checking several headers can be tedious for beginners.

## Solution
The Python script sends a normal HTTP GET request and checks for:
- Strict-Transport-Security
- Content-Security-Policy
- X-Content-Type-Options
- X-Frame-Options
- Referrer-Policy
- Permissions-Policy

## Technologies used
- Python 3
- requests library
- Jupyter Notebook

## Setup and run
1. Install Python 3 or open the notebook in Google Colab.
2. Install dependencies with `pip install -r requirements.txt` (or run `!pip install requests` in a notebook).
3. Open `Automated_Web_Scanner.ipynb` and run the cells.
4. Enter a website URL you own or have permission to assess.

## Files
- `Automated_Web_Scanner.ipynb` — notebook/code
- `requirements.txt` — Python dependency
- `Project_Report.docx` — project report

## Limitations
This is a basic educational checker, not a complete vulnerability scanner. Websites may apply security controls in other ways. A missing header is not proof of a vulnerability, and the tool does not test for exploitation.

## Ethical use
Only check websites you own or have explicit permission to assess. Do not use this project to attempt unauthorized access.

## Dataset
No separate dataset is required. The program reads HTTP response headers from the URL entered by the user.
