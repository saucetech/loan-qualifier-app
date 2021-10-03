# loan-qualifier-app

This is a command line application that matches applicants with qualifying loans based on their financial information. The loan qualification criteria is based on the applicant's credit score, loan size, debt to income ratio, and loan to value ratio. 

---

## Technologies

This project leverages Python 3.7 with the following packages:
* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entry-point.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

---

## Installation Guide

In this section, you should include detailed installation notes containing code blocks and screenshots.

Before running the application first install the following dependencies.

```python
  pip install fire
  pip install questionary
```

---

## Usage

To use the loan qualifier app, simply clone the repository and run the **app.py**. When prompted, select the path for the daily_rate_sheets.csv that you would like to use. An example has been provided in the package. A series of prompts will follow where you can input the applicant's financial information (credit score, monthly debt, monthly income, desired loan size, and estimate home value) which are used to calculate the qualification criteria. A csv file will be returned with the qualifying loans.

---

## Contributors

Brought to you by Austin Do and Columbia University. AustinDoTech@gmail.com.

---

## License

MIT
