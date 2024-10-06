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
