# 2016 Election Helper

Python3 script to generate sample absentee ballots for user defined canidates. This helper program is extremely useful if you want to distribute voting recommendations, and works with ballots from any of the electoral districts in New Hampshire. The program expects a folder with PDF versions of the ballots you want filled in and a CSV with all of the names you're interested in, by default located at `ballots/` and `names.csv` in the program directory.

## Dependencies

- PyPDF2
- pdfminer3k
- reportlab

```bash
pip install pypdf2 pdfminer3k reportlab
```

## Usage

Before running the program, ensure that there is a `ballots/` folder and a `names.csv` file in the root directory of the project.

```bash
python main.py
```