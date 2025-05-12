# Whatsapp-Auto-Messenging-Bot

This project is an RPA (Robotic Process Automation) solution built with UiPath to automate message sending through WhatsApp Web. It simulates user actions to send personalized or scheduled messages to one or multiple contacts.

**Features**

🔄 Automated message sending on WhatsApp Web

🧑‍🤝‍🧑 Reads multiple contacts and messages from an Excel sheet

🕒 Delay and wait logic for message delivery confirmation

✅ Supports both individual and group messages

📋 Easy-to-edit input data file

💬 Logs message status (sent/failed)

**Dependencies**

1, UiPath Studio (2021 or later recommended)

2, UiPath Excel and UIAutomation Activities packages

3, WhatsApp Web account access (logged in via browser)

**How to Use**

1, Open UiPath Studio.

2, Load the project (WhatsAppAutoMessagingFinalEdit folder).

3, Update Input.xlsx with your contacts and messages.

4, Run the bot:
>>It will open WhatsApp Web.
>>Wait for QR code scan (if needed).
>>Send messages one by one with delay.
