 QA Automation - Chat Translator (Playwright)

This repository contains an automated frontend testing script for the [PixelsSuite Chat Translator](https://www.pixelssuite.com/chat-translator). The script is built using Python and Playwright. It reads test cases from an Excel file and automates the browser interactions to verify the system's output.

## Prerequisites

Before running the script, ensure you have the following installed on your machine:
* Python 3.10 or higher
* Pip (Python package manager)

## Installation & Setup

1. **Install required Python packages:**
   Open your terminal and run the following command to install Playwright and OpenPyxl (for handling Excel files):
   ```bash
   pip install playwright openpyxl
2.Install Playwright browsers:
Run the following command to download the necessary browser binaries (Chromium):

Bash
playwright install chromium
How to Run the Tests
To execute the automation script, open your terminal, navigate to the project directory, and run the following command:

Bash
python test_automation.py --excel "tesings.xlsx"
Note: Make sure the tesings.xlsx file is in the same directory, or provide the full file path.

Repository Structure
test_automation.py : The main Python automation script using Playwright.

tesings.xlsx : The Excel file containing the Singlish to Sinhala test cases (Inputs and Expected Outputs).
