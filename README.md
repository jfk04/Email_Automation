## Email Automation

A small Python program that I developed for my company. It should monitor the last modification time of a file and sends an email notification if the file has not been updated within a defined time threshold.

## 🚀 Features

- Monitors a specific file for inactivity
- Sends an email alert if the file was not modified within X minutes
- Reads configuration values from a `.ini` file
- Automatically creates a default `.ini` file if none exists
- Lightweight and easy to extend

## 🛠 Tech Stack

🐍Python  

Libraries:

- configparser
- os
- smtplib

## 🧠 What I Learned

- Reading and writing configuration files using `configparser`
- Handling missing configuration files by generating default settings
- Sending emails via SMTP, including authentication and TLS
- Structuring a small utility script in a clean and maintainable way
- Improving error handling and robustness for real-world usage
