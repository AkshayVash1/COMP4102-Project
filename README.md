## [Video demonstration](https://youtu.be/K5BvzzOsRXg) <a name="third"></a>


## How to Run <a name="run"></a>
- **THIS PROJECT CONTAINS A RUNNABLE .EXE FILE THAT REQUIRES NO EXTRA MODULE INSTALLATIONS**
  - Simply run dist/main/main.exe
- Alternatively set up an environment
  - Pre-requisites
    - python3
    - `pip install -r requirements.txt`
    - tkinter
      - For Windows: Should be included within your Python installation by default
      - For Ubuntu: sudo apt-get install python3-tk
      - For Fedora: sudo dnf install python3-tkinter
      - For MacOS: brew install python-tk
    - Google Cloud Credentials json file
      - It will either be attached or you can open an issue
  - To run
    - `python3 main.py`
    - Alternatively you can just run main.py in your code editor
    - If you just want to test Document AI, you can just run it's cell in testing.ipynb
  - Features
    - Select file to be processed
      - Project contains some test data in images/test_image*
    - Create Deck
      - Input desired deck name and select 'OK'
      - Created decks will be saved in ./saved_decks/
