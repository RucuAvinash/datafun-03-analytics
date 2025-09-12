# datafun-03-analytics

This project demonstrates how to fetch and process various types of 
files (Excel, JSON, text, and CSV) using Python. 

The repository includes:

- Four example fetchers: Scripts to retrieve data from the web.
- Four example processors: Scripts to analyze and process the fetched data.

Start by running the examples to understand their functionality, and then build your own scripts to fetch and process data of your choice (using each of these example types).

## Project Requirements

- VS Code
- Git
- Python 

```powershell
py -m venv .venv
.\.venv\Scripts\activate
py -m pip install --upgrade pip setuptools wheel
py -m pip install --upgrade -r requirements.txt
```
## Commands to Run Python Scripts

Remember to activate your .venv (and install packages if they haven't been installed yet) before running files.
Verify that all required packages are included in requirements.txt (and have NOT been commented out).


```shell
py rucu_get_csv.py
py rucu_get_excel.py
py rucu_get_json.py
py rucu_get_text.py

py rucu_process_csv.py
py rucu_process_excel.py
py rucu_process_json.py
py rucu_process_text.py

```

## Commands to Git add-commit-push

```shell
git add .
git commit -m "fetch data and process results"
git push -u origin main
```

## Create and Run Your Data Fetchers
1. Find data files on the web for each type (CSV, Excel, JSON, and text).  
2. Create your own Python script to fetch each type of data and save it in a folder named **data**.
3. Name your scripts:
   1. rucu_get_csv.py
   2. rucu_get_excel.py
   3. rucu_get_json.py
   4. rucu_get_text.py
4. Implement your data-processing logic in small steps:
   - Fetch data for one file type.
   - Test, verify, and Git add-commit-push.
  
## Create and Run Your Data Processors
1. Determine a simple metric from each of your data files.  
2. Create your own Python script to read the data, process it, and save it in a folder named **data_processed**.
3. Name your scripts:
   1. rucu_process_csv.py
   2. rucu_process_excel.py
   3. rucu_process_json.py
   4. rucu_process_text.py
4. Work incrementally, using git add-commit-push after each bit of progress. 

5. fetchers: a. 2020_happiness.csv - a .csv file based to calculate happiness score based on certain criteria for several countries.
6.           b. astros.json - is a json document that has astronaut name and their respective carriers(space craft)
7.           c. Feedback.xlsx- Feedback from students on submission of coding projects 
8.           d. romeo.txt -It is a Romeo Juliet play from Shapesphere
9. processors: a. happiness_ladder_score_stats- The processor uses the statistics package to analyze the data in csv and get some ladder metrics.
10.            b. json_astronauts_by_craft - the processed file counts astronauts by their respective spacecraft by parsing the json document and dynamically building the count using disctionaries.
11.            c. excel_feedback_github_count - Counts the number of time 'GitHub' occurrs in a column
12.            d. text_romeo_word_count - counts the number of times the word 'Romeo' occurs in the text file.       
    

    Execution for Fetchers:
    py rucu_get_csv.py
    py rucu_get_excel.py
    py rucu_get_json.py
    py rucu_get_text.py

    Execution for processors:
    py rucu_process_csv.py
    py rucu_process_excel.py
    py rucu_process_json.py
    py rucu_process_text.py

    Execution of master script:

    py rucu_master_script.py

Note: files in rucu_data are used for self exploration and practice. 