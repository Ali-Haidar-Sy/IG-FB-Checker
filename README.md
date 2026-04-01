# 🔍 Educational Tool – Instagram & Facebook Email Checker
<p> FOLLOW ME IN INSTAGRAM : @_ungn </p>
<p> sub my ch in telegram : @p33_9 </p>
<hr>
⚠️ IMPORTANT DISCLAIMER 
This tool is created exclusively for educational and research purposes.  
It is designed to help understand how social media APIs work and how to use Python for automated testing.  
(Do not use it to violate the privacy of others or to gather data without explicit consent.)  
The author is not responsible for any misuse of this code.

---

## 📖 Description

This script performs the following tasks:

- Randomly collects Instagram usernames (using public endpoints).
- Checks whether the associated Gmail address (username@gmail.com) is registered on **Instagram** and **Facebook**.
- Uses multiple endpoints and fallback methods to verify account existence.
- Sends valid results to a **Telegram bot** (if configured) and saves them locally.
- Uses multithreading for faster processing.

It is intended to demonstrate:
- Working with REST APIs (Instagram, Facebook Graph API).
- Handling JSON data and HTTP headers.
- Using Python libraries: `requests`, `threading`, `faker`, `uuid`, etc.
- Building a simple Telegram bot integration.

---

## ⚙️ Requirements

- Python 3.7 or higher
- Required packages (see `requirements.txt`)

Install dependencies with:

```bash
pip install -r requirements.txt
