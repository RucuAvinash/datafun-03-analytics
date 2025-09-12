# datafun-03-analytics

This project demonstrates how to fetch and process various types of 
files (Excel, JSON, text, and CSV) using Python. 

Import utils_logger for logging for the project.

CSV Fetcher:

Downloads the World Happiness 2020 dataset.

Command:

py rucu_get_csv.py

Excel Fetcher:

Downloads the Feedback .xlsx

Command:

py rucu_get_excel.py

Text Fetcher:

Downloads the rome text file

Command:

py rucu_get_text.py

Json Fetcher:

Downloads sample json file

Command

py rucu_get_json.py

Processors:

CSV Processor: rucu_process_csv.py
Json Processor: rucu_process_json.py
Excel processor: rucu_process_excel.py
Text processor: rucu_process_text.py

Master script: Launches fectchers and processors sequentially

Command: rucu_master_script.py

Installation:

Clone the project from remote git hub url: https://github.com/RucuAvinash/datafun-03-analytics
Create virtual environment: py -m venv .venv
.\.venv\Scripts\activate 
command to go to project root directory: cd datafun-03-analytics

Install external dependencies:
pip install requests
pip install openpyxl