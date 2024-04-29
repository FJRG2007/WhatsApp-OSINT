# WhatsApp OSINT Tool

![example](./img/doc1.PNG?raw=true)

Welcome to the first WhatsApp OSINT tool. This was developed in early 2019 but I decided to restart the project now for fun. 

# How to Install

First, install requirements:

```
pip install -r requirements.txt
```

- You will need chromedriver, or you can modify the code and use GeckoDriver or any other drivers for Selenium.
- You will need a GUI to execute the code since it interacts with web.whatsapp.com to get statuses
- Replace the name in the file with whichever name you want to track

# How to Run

```
<py or python3> whatsappbeacon.py --username "<username_to_track>" --language "<language_code>"
```

where language_code is either 'en' or 'es' for English and Spanish languages. Future language support will be added.

# Credits

This tool was developed by myself in my spare time. It is a tool that demonstrates the power of Selenium and web scraping. I do not support the use of this tool to harass people or any other fraudulent purpose. If you have suggestions on how to expand or improve the functionality, please send a message to Discord and I will gladly review the changes.

