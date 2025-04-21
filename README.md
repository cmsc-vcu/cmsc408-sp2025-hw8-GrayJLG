# Homework 8: #

## Overview ##

This assignment went full tilt with teaching how to write complex and effective SQL queries to extract meaningful information from a large bank of data. I was responsible for ensuring that proper syntax was used in creating these queries, and that the queries were able to be run in a timely manner. I also had to ensure that the queries were able to be run on a large dataset, and that they returned the correct results.

## How to view the report easily from here ##

Navigate to the repository below: 

[Repository Link](https://github.com/cmsc-vcu/cmsc408-sp2025-hw8-GrayJLG) 

To view the full analysis, including diagrams and relational schemas, navigate to the reports folder and open the report.html file in a browser

## If you want to regenerate the report from the source file (report.qmd) using the command line: ##

### Prerequisites: ###

-  [Set Up Link](https://vcu-ssg.github.io/ssg-quarto-python-setup/) 

- Follow the steps in this link VERY CAREFULLY and ensure that everything is downloaded and working before you begin interacting with the qmd files.

Clone the repository by entering the following in the command line of your choice:

```bash
gh repo clone cmsc-vcu/cmsc408-sp2025-hw8-GrayJLG

cd cmsc408-sp2025-hw6-GrayJLG

```

Now, activite your python virtual environment:

```bash
pyenv install 3.13.2

```

```bash
pyenv global 3.13.2

```

```bash
poetry shell

```
Next, create a .env file in the main folder. It should contain the following:

```bash
CMSC408_HW7_USER=YOURUSERNAME
CMSC408_HW7_PASSWORD=YOURPASSWORD
CMSC408_HW7_HOST=YOURHOSTDOMAIN
CMSC408_HW7_DB_NAME=YOURDBNAME
```

With everything replaced to your specific configuration. 

Then, navigate to the reports folder:

```bash
cd ./reports
```

and then render the report:

```bash
quarto render report.qmd
```

Open report.html in your browser.

## This can also be done through VSCode: ##

Use the links above in the prerequisites section to download VSCode, Quarto, and GIT

Use the search feature at the top of VSCode and type

`>clone`

and select the "Git:Clone" option

Save the repo to a desired folder on your computer

Open the folder in VSCode and navigate to report.qmd

Now, activite your python virtual environment:

```bash
pyenv install 3.13.2

```

```bash
pyenv global 3.13.2

```

```bash
poetry shell

```

Next, create a .env file in the main folder. It should contain the following:

```bash
CMSC408_HW8_USER=YOURUSERNAME
CMSC408_HW8_PASSWORD=YOURPASSWORD
CMSC408_HW8_HOST=YOURHOSTDOMAIN
CMSC408_HW8_DB_NAME=YOURDBNAME
```

With everything replaced to your specific configuration. 

Then, navigate to the reports folder:

```bash
cd ./reports
```

and then render the report:

```bash
quarto render report.qmd
```

in terminal, or by simply clicking the "preview" option at the top right when viewing report.qmd

# Further info #

- This report was built by Jacob Gray via scaffolding provided by John Leonard of Virginia Commonwealth University for the class CMSC 408

- [Repository Link](https://github.com/cmsc-vcu/cmsc408-sp2025-hw8-GrayJLG)


