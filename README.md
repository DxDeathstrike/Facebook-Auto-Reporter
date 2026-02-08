

# Facebook Auto Reporter

**Overview:**
This Python project automates the process of reporting Facebook accounts using Selenium. It logs into user account, navigates to a target account, and repeatedly submits reports based on user input. The script includes update checking, error/usage notifications, and a built-in updater utility.

**Note:** The selling or sharing of this code without direct permission is prohibited and will be met with consequences.

**Note:** The source code for this script will not be made publicly available; however, script is usable by exe.
![fb auto report](https://github.com/user-attachments/assets/c5784466-49cf-4327-b2e3-aea46732b956)


**Warning:** This tool is intended for educational and research purposes only. The author does not encourage or endorse misuse. By using this tool, you accept full responsibility for your actions and compliance with Facebook's terms of service and applicable laws. The author is not liable for any consequences, including account bans or legal issues. Use at your own risk.


## Table of Contents
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [How the Code Works](#how-the-code-works)
- [ChromeDriver Installation](#chromedriver-installation)
- [Contributing](#contributing)
- [Disclaimer](#disclaimer)

## Requirements
Requirments are pre-installed however if errors occur download the below
- Python 3.x
- Selenium library
- Google Chrome browser
- ChromeDriver (matching your Chrome version)

## Installation


1. **Sharing or Selling without Permission:**
   The selling or sharing of this code without direct permission is prohibited and will be met with concequences

2. **Install fbautoreporter.exe:**

3. **Check Anti Virus:**
    ```bash
    Settings
    Update and Security
    Windows Security
    Open Windows Security
    Virus and Threat Protection
    Protection History
    Then Allow most recent if it containts "fbautoreporter" or "updater"
    ```
## Usage
1. Download the Files of Repository.
2. Make sure download is successful and opens.
3. Enter your Facebook email and password when prompted.
4. Enter the Facebook account URL you wish to report.
5. Enter the number of reports to submit (0 for infinite).
6. Enter a delay in seconds between actions (recommended if you have slow internet or encounter issues) or 0 if normal.

The script will log in, navigate to the target account, and begin submitting reports automatically. Progress and status messages will be printed in the terminal.

## How the Code Works
- **Startup & Update Check:**
    - Checks for updates using a remote version file. If a new version is available, downloads and launches the updater.
- **Error & Usage Tracking:**
    - Sends error and usage notifications
- **User Prompts:**
    - Prompts for Facebook credentials, target account URL, number of reports, and delay.
- **Selenium Automation:**
    - Launches Chrome, logs in, navigates to the account, and automates the reporting process using robust element selectors and error handling.
- **Looping:**
    - Repeats the reporting process for the specified number of times (or infinitely).
- **Exit:**
    - Closes the browser and waits for user input before exiting.


## Updater Utility
The included `updater.exe` handle automatic updates:
- Downloads the latest version of the main executable if available.
- Safely replaces the old executable with the new one.
- Can be run directly or is triggered automatically by the main script when an update is detected.

## ChromeDriver Installation
Incase of Error make sure you have Chrome and ChromeDriver
To install ChromeDriver for your specific version of Chrome:

1. **Check your Chrome version:**
    - Open Chrome and go to `chrome://settings/help` to find your version number.

2. **Download the matching ChromeDriver:**
    - Visit the [ChromeDriver downloads page](https://chromedriver.chromium.org/downloads).
    - Click on the version that matches your Chrome version.
    - Download the appropriate file for your operating system.

3. **Extract and place the executable:**
    - Extract the downloaded file (if compressed) and place the `chromedriver.exe` in the root directory of your project.

## Contributing
Contributions are welcome! If you have suggestions for improvements or encounter any issues, please open an issue or submit a pull request.

---
## Disclaimer
**Disclaimer:** This tool is intended for educational and research purposes only. The author does not encourage or endorse misuse. By using this tool, you accept full responsibility for your actions and compliance with Facebook's terms of service and applicable laws. The author is not liable for any consequences, including account bans or legal issues. Use at your own risk.
