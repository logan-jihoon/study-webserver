# Study Webserver

## Description
A Python web server study project for learning server-side development and RESTful API concepts.

## Technology Stack
- Python 3.10
- Poetry for dependency management
- FastAPI (planned)
- Uvicorn (planned)

## Project Setup

### Prerequisites
- Python 3.10.15 (using pyenv)
- Poetry (package manager)

### Installation
```bash
# Clone repository
git clone https://github.com/logan-jihoon/study-webserver.git
cd study-webserver

# Set Python version
pyenvy versions # List all installed versions
pyenv local 3.10 # set the python version to 3.10


# Set Dev Branch
git checkout -b dev # Switch to dev 
git push -u origin dev # Set up tracking relationship 

# Configure poetry to create virtualenv in project directory
poetry config virtualenvs.in-project true --local

# Install dependencies
poetry install

# Activate virtual environment
poetry shell