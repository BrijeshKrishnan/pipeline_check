# Welcome to the pipeline discussion

This branch contains files/project which is based on python programming. There
are potential improvement which will be the topic for pipeline discussion 

## Prerequisite

This project requires python 3.8.

Please download & install python 3.8  from here

All dependencies can be installed from here

To run the project, follow these steps:

Clone the repository using command
git clone git@github.com:BrijeshKrishnan/pipeline_check.git

## Run the project

Install dependencies:
python -m pip install -r requirements.txt

Test:
python -m pytest test --capture=sys --cov-report "html" --cov=src

linting:
python -m pylint src test




