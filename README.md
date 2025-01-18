# Web Crawler Project

This project demonstrates a basic web crawler implemented in Python. The crawler starts from a base URL, extracts all the links, and saves them to text files. It handles HTTP errors, connection issues, and respects the politeness policy by adding delays between requests.

## Features

- Crawls web pages starting from a base URL.
- Extracts and saves all valid links from each page.
- Handles HTTP errors and connection issues gracefully.
- Respects the politeness policy with configurable delays.
- Saves extracted links in organized text files within a project directory.

## Prerequisites

Before running the project, ensure you have Python installed along with the required libraries:

- `requests`
- `beautifulsoup4`

Install the required libraries using pip:

```bash
pip install requests beautifulsoup4
