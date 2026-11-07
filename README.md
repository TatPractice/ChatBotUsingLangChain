# Chatbot Using LangChain

A small starter project for exploring LangChain with Python. The repository currently contains an introductory notebook; it does not yet implement a complete chatbot.

## Project contents

- `Section_Basics/LangchainBasic.ipynb` — introductory notebook with initial LangChain setup.

## Requirements

- Python 3.13 (or another Python version supported by the installed LangChain release)
- pip

## Setup on Windows

From the project directory, create and activate a virtual environment:

```powershell
py -3.13 -m venv .venv
.\.venv\Scripts\Activate.ps1
```

Install the packages needed to use LangChain and run the notebook:

```powershell
python -m pip install --upgrade pip
python -m pip install langchain notebook
```

Start Jupyter Notebook:

```powershell
jupyter notebook Section_Basics\LangchainBasic.ipynb
```

When you are finished, deactivate the virtual environment:

```powershell
deactivate
```

## Notes

- Keep your virtual environment local; it is excluded from Git by `.gitignore`.
- Do not commit API keys, passwords, or other secrets. If you add a model provider later, keep its credentials in environment variables or a local, untracked `.env` file.
