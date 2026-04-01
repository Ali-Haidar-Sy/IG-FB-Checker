<!-- Badges section -->
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.7%2B-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg" />
  <img src="https://img.shields.io/badge/Status-Educational-orange" />
  <img src="https://img.shields.io/badge/Instagram-API-critical?logo=instagram" />
  <img src="https://img.shields.io/badge/Facebook-API-1877F2?logo=facebook" />
</p>

<h1 align="center">🔍 Instagram & Facebook Email Checker</h1>
<p align="center">
  <b>Educational tool – Learn how social media APIs work with Python</b><br>
  <i>⚠️ For ethical and educational use only. Do not misuse.</i>
</p>

<p align="center">
  <a href="https://t.me/P33_9">📱 Telegram Channel</a> •
  <a href="https://www.instagram.com/_ungn">📸 Instagram Profile</a>
</p>

---

## ⚠️ IMPORTANT DISCLAIMER

**This tool is created exclusively for educational and research purposes.**  
It is designed to help understand how social media APIs work and how to use Python for automated testing.  
**Do not use it to violate the privacy of others or to gather data without explicit consent.**  
The author is not responsible for any misuse of this code.

---

## 📖 Description

This script performs the following tasks:

- Randomly collects Instagram usernames (using public endpoints).  
- Checks whether the associated Gmail address (`username@gmail.com`) is registered on **Instagram** and **Facebook**.  
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
