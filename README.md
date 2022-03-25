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
