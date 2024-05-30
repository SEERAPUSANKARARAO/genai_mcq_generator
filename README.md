# Project Title:GenAI MCQ Generator

## Project Overview

MCQ Generator is a Python-based application designed to generate multiple-choice questions (MCQs) automatically. This project is structured to facilitate easy development, experimentation, and deployment of the MCQ generation capabilities.

## File Structure

Here is an overview of the project's file structure:

```
MCQGenerator/
│
├── .env                         # Environment variables
├── .ignore                      # Ignore patterns for the project
├── app.py                       # Main application script to run the app
├── folder_structure.txt         # This file, outlining the project's structure
├── README.md                    # This README file
├── requirement.txt              # List of dependencies for the project
├── Response.json                # Sample response output file
├── setup.py                     # Setup script for installing the package
│
├── Data/                        # Directory containing data files
│   └── text.txt                 # Sample text file
│
├── experiment/                  # Directory for Jupyter notebook experiments
│   └── experiment_1.ipynb       # First experiment notebook
│
├── mcqgenrator.egg-info/        # Package metadata directory
│   ├── dependency_links.txt
│   ├── PKG-INFO
│   ├── requires.txt
│   ├── SOURCES.txt
│   └── top_level.txt
│
└── src/                         # Source code directory
    ├── __init__                 # Init file for the src package
    │
    ├── mcqgenrator/             # MCQ Generator module
        ├── logger.py            # Logging utilities
        ├── MCQGenrator.py       # Main MCQ generation logic
        ├── utils.py             # Utility functions
        └── __init__             # Init file for the mcqgenrator module
```

## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/SEERAPUSANKARARAO/genai_mcq_generator.git
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirement.txt
   ```

## Usage

To run the main application, use the following command:

```bash
streamlit run app.py
```

This will start the application and allow you to generate MCQs based on the provided data.
