# Survey Processing

This is the processing of the results from https://YarnSurvey.com.

# Getting Started 

## Prerequisites

- Python 3.1

## Installation

1. Clone the repo
   ```sh
   git clone https://github.com/MDeanLindsay/Survey-Processing.git
   ```
2. Create venv.
   ```sh
   python -m venv .venv
   ```
3. Initialize venv.
   ```sh
   .\.venv\Scripts\activate
   ```
4. Install requirements.
   ```sh
   pip install -r requirements.txt
   ```

## Export PDF

You can enter this in the notebook, or run this from the command line in the venv.
Just make sure to add a ! as a prefix before running inside the notebook.

``'
jupyter nbconvert --to webpdf Yarn_survey.ipynb --output All_PDF_Export --output-dir ./PDF --no-input --allow-chromium-download
```