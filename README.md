# Welcome

This project will explore getting started developing with [Python](https://www.python.org) as quickly as possible using [Visual Studio Code](https://code.visualstudio.com).

## Local development

### Install dependencies and run our project

```sh
# Verify that you have Python installed on your machine
% python3 --version
Python 3.11.1

# Create a new virtual environment for the project
% python3 -m venv .venv

# Select your new environment by using the Python: Select Interpreter command in VS Code
#   - Enter the path: ./.venv/bin/python

# Activate your virtual environment
% source .venv/bin/activate
(.venv) %

# Install Python packages in a virtual environment
# EXAMPLE: Install simplejson - https://pypi.org/project/simplejson/
# % pip install simplejson
# ... continue to install packages as needed ...

# When you are ready to generate a requirements.txt file
# % pip freeze > requirements.txt

# What happens if you want to uninstall a package?

# Uninstall the package from your virtual environment
# % pip uninstall simplejson

# Remove the dependency from requirements.txt if it exists
# % pip uninstall -r requirements.txt

# Install the packages from requirements.txt
(.venv) % pip install -r requirements.txt
```

That's it! Now you should be able to execute your Python scripts 🤓

Here is an example of running [nhl_api.py](nhl_api.py) from your local machine:

```
(.venv) % python3 nhl_api.py

Let's explore the NHL API with Python 🐍

```


Here is an example of running [test_nhl_api.py](test_nhl_api.py) from your local machine:

```
(.venv) % python3 test_nhl_api.py

Let's explore the NHL API with Python 🐍

.....
----------------------------------------------------------------------
Ran 5 tests in 0.445s

OK

```
