# Text Based Captcha

The Text Based Captcha project is a Python-based application utilizing Tkinter for a graphical user interface. It automatically generates and verifies the input text-based captchas for user authentication.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction
The Text Based Captcha project is designed to facilitate text-based captcha generation and authentication. It offers a simple yet effective way to validate user input against generated captchas.

## Features
- **Automatic Captcha Generation:** Generates random text-based captchas for user authentication.
- **Validation:** Allows users to verify against the generated captcha to grant access.
- **Registration Number Verification:** Validates registration numbers before allowing access to the system.
- **Logging:** Stores entry logs with registration numbers, timestamps, and IP addresses in an SQLite database.

## Installation
1. Ensure Python 3.x is installed on your system.
2. Clone this repository: `git clone https://github.com/annus3/text-based-captcha.git`
3. Install required dependencies: `pip install -r requirements.txt`

## Usage
1. Navigate to the project directory.
2. Run the application using Python: `python captcha_app.py`
3. Enter a valid registration number and the captcha code displayed in the GUI to gain access.

## Contributing
Contributions are welcome! Here's how you can contribute:
1. Fork the repository.
2. Create a new branch.
3. Make necessary changes or additions.
4. Commit your changes.
5. Push to the branch.
6. Create a new Pull Request.
