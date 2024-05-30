# App JWT Generator

## Description

A python script for generate the app jwt from the private key.

## Usage

1. Create a Python virtual environment and activate it.

   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```

1. Install the dependencies

   ```bash
   pip install -r requirements.txt
   ```

1. Create a private key for the GitHub app.

   > *Private keys* can be generated in **General** scope of the setting page of the app,
   > which is different from *client secret*.

1. Run the Python script and pass the appropriate arguments.

   ```bash
   python main.py <private key path> <app client id>
   ```
