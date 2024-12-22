# Selenium Projects

This repository contains three Python scripts utilizing Selenium to automate various web interactions. Each script demonstrates specific Selenium functionalities, including web element selection, form automation, and event extraction.

## Project Overview

### 1. `challenge.py`
Automates form submission on a sample website.
- **Website**: [Secure Retreat](https://secure-retreat-92358.herokuapp.com/)
- **Features**:
  - Fills out the form fields: First Name, Last Name, and Email.
  - Submits the form by clicking the "Sign Up" button.

### 2. `interaction.py`
Interacts with the Wikipedia homepage.
- **Website**: [Wikipedia](https://en.wikipedia.org/wiki/Main_Page)
- **Features**:
  - Extracts and prints the article count using CSS selectors.
  - Finds the "Content portals" link and simulates a click.
  - Uses the search bar to query "Python" and simulates the Enter key.

### 3. `main.py`
Explores element selection and extracts event details from the Python.org homepage.
- **Website**: [Python.org](https://www.python.org/)
- **Features**:
  - Demonstrates various Selenium selectors: `By.NAME`, `By.ID`, `By.CSS_SELECTOR`, `By.XPATH`.
  - Extracts upcoming event dates and names from the events widget.
  - Prints the event data in a dictionary format.

## Setup and Installation

### Prerequisites
1. **Python**: Ensure Python 3.x is installed on your system. [Download Python](https://www.python.org/downloads/)
2. **Google Chrome**: Install the latest version of Google Chrome. [Download Chrome](https://www.google.com/chrome/)
3. **ChromeDriver**: Download the matching version of ChromeDriver for your Chrome version. [Download ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/)

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/selenium-projects.git
   cd selenium-projects
   ```
2. Install required dependencies:
   ```bash
   pip install selenium
   ```
3. Ensure `chromedriver` is in your system's PATH or specify its path in the scripts.

## How to Run

### General Instructions
- Each script is independent and can be run directly using Python:
  ```bash
  python script_name.py
  ```

### Example
Run the `challenge.py` script:
```bash
python challenge.py
```


## Features Demonstrated

1. **Automating Form Submission**:
   - Example: Filling out and submitting forms on `challenge.py`.

2. **Element Selection Techniques**:
   - CSS Selectors, XPath, `By.NAME`, `By.ID`, etc.
   - Demonstrated in `main.py` and `interaction.py`.

3. **Event Extraction**:
   - Extracting and formatting event data as dictionaries in `main.py`.

4. **Keyboard Simulation**:
   - Sending keys like `ENTER` for searches in `interaction.py`.


## Key Libraries
- **Selenium**: For web browser automation.

## Notes
- Ensure the `chromedriver` version matches your installed Chrome version to avoid compatibility issues.
- Use `chrome_options.add_experimental_option("detach", True)` to keep the browser open after the script ends.

