# Titanic Data Analysis

## Table of Contents
1. [Description](#description)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Endpoints](#endpoints)
5. [Contributing](#contributing)

## Description
This project performs an exploratory data analysis (EDA) on the Titanic dataset. It aims to uncover patterns and insights about the passengers and their survival rates through various data analysis techniques.

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
    bash
    git clone https://github.com/baranidharan27/project.git
    
2. Navigate to the project directory:

    bash
    cd your-repo
    
3. Create a virtual environment:

    bash
    python -m venv env
    
4. Activate the virtual environment:

    - On Windows:
        bash
        .\env\Scripts\activate
        
    - On macOS and Linux:
        bash
        source env/bin/activate
        
5. Install the required packages:

    bash
    pip install -r requirements.txt
    

## Usage

1. Start Jupyter Notebook:
    bash
    jupyter notebook
    
2. Open the EDA.ipynb notebook and run the cells to perform the analysis.

## Endpoints
This project uses FastAPI to create endpoints for various modules:
- *PDF Module*: /pdf
- *PPT Module*: /ppt
- *Text Module*: /text
- *File Upload*: /upload
- *LLM Query*: /query

## Contributing

Contributions are welcome! 

