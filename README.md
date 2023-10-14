# scheduleUnification
Unification schedules of Program Engineering - 3 from Faculty of Informatics and 3rd course of Economics Faculty using Python.

## Used Libraries
### To run project this packages required:
    - Jupyter Notebook
    - Pandas
### To load them run these two commands:
    - pip install notebook
    - pip install pandas
Other packages are built-in.

## Running the project
    - Clone project from GitHub
    - Install required packages
    - Start Jupyter Notebook server
    - Run step-by-step cells from Unificator.ipynb

## Solution description:
### Below is a short breakdown of each step of the project
    - First, using Google Sheets, I transferred the schedule of the Faculty of Economics to an .xlsx format, which I used later.
    - Than, loaded two scedules as Pandas.DataFrame
    - Next, I used Pandas and the transformation to create schedules of the same table format
    - After preparation, I combined the schedules.
    - Finally, I merged the different columns into dictionaries containing dictionaries step by step and wrote the final result to a .json file

## Resulting file:
### Result.json have next structure:
    {
    "ФІ": [
        {
            "ІПЗ": [
                {
                    "Інструменти та принципи веб-розробки": [
                        {
                            "лекція": {
                                "День": "Середа",
                                "Час": "8:30-9:50",
                                "Тижні": "1-8",
                                "Аудиторія": "Дистанційно",
                                "Викладач": "ас. Д.В. Зважій"
                            }
                        },
                    ...
                    ]
                }
            ]
        }
    ]
    }
