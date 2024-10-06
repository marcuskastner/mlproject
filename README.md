# mlproject

## Setup

### 1. Create New Environment

This ensures encapsilation of packages
`conda create -p venv python -y`

### 2. setup.py

The setup.py file defines the entry points and dependencies of the project.
It also makes the project modular and installable as a package.
This allows other developers or systems to install the project easily.

### 3. requirements.txt

The requirements.txt file lists all the external packages that are required for the project to run.
`pip install -r requirements.txt`
The -e . kicks off the entry point file that is setup.py

## Filestructure, Logging and Exceptions

### Filestructure

Within src there are two main folders components and pipeline. Components stores
files that I will use when building the model

Another useful file will be utils which will be used to store utility functions

### Logging

Custom logger.py file was created that creates a log file within the
logs directory that stores information about the error such as what file it
occured in and what the message is.

### Exception

Custom error message is created that contains useful information such as line number, file name and error message.
