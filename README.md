# parse_excel

Demo project for parsing Excel files to CSV using pandas. The commands in this README are for Windows.

## Prerequitites

1. Install Visual Studio Code (or other IDE)
2. Install Python
3. Use pip to install virtualenv `pip install virtualenv`
4. Clone the repository
   - Go to https://github.com/jobdenotter/parse_excel, click on the green button 'Code' and copy the address for HTTPS.
   - Open a command line and navigate to the folder where you want to store the repository.
   - type `git clone [copied address]` (which should result in `git clone https://github.com/jobdenotter/parse_excel.git`).

## Create and activate your virtual environment

1. Navigate to the repository
2. Execute the command `virtualenv venv` (venv is a common name for a virtual environment)
3. Execute the command `source venv/Scripts/activate` to activate your virtual environment (you can deactivate it by simply using the command `deactivate`).
4. When activated, you can install all the requirements by executing the command `pip install -r requirements.txt`. This will read all the required packages from the file requirements.txt and install them in the virualenv (make sure it is activated).

## Running the program

You can run any Python file from the command line using `py [filename]`. E.g. `py main.py`.

## Exercise

When you execute the program, it will print the dataframe

|     | column 1 | column 2 |
| --- | -------- | -------- |
| 0   | a        | d        |
| 1   | b        | e        |
| 2   | c        | f        |

Your challenge is to use [pandas to_csv](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_csv.html) and [pandas rename](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.rename.html) to generate a CVS file `example.csv` which looks like.

| Instrument | Price |
| ---------- | ----- |
| TSLA       | 1     |
| AAPL       | 2     |
| MSFT       | 3     |

### Hints

- Try splitting the task into different steps.
- You can access and modify elements of the pandas dataframe using `df[<column name>][<row index>]`.
- Read the documentation of [pandas to_csv](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_csv.html) and [pandas rename](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.rename.html).
