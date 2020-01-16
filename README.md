# Exercise csv2config

The script csv2config shout take the data from a csv file and generate for each entry a configuration file.

## ToDo1

The script `csv2config.py` has prepared three functions. Implement these three functions without changing the input and output structure. Otherwise the tests will fail. You can see in the docstring how the function should behave. Also check the tests in `test_csv2config.py`.

## ToDo2

Create a script `yaml2config.py` equivalent to the `csv2config.py` script.

## ToDo3 (optional)

Use the `argparse` module (https://docs.python.org/3/library/argparse.html) to make the scrips better usable from the command line.

## Setup

Use >= Python3.6

Windows (CMD):

```bash
> python.exe -m venv .venv
> .venv\Scripts\activate.bat
(.venv)> pip install --upgrade pip
(.venv)> pip install -r requirements.txt
```

Linux:

```bash
$ python -m venv .venv
$ source .venv/bin/activate
(.venv)$ pip install --upgrade pip
(.venv)$ pip install -r requirements.txt
```

## Test

```bash
(.venv)$ pytest --pep8
```

PEP8 = Style Guide for Python Code
https://www.python.org/dev/peps/pep-0008/
