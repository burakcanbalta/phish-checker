# Phish Checker 🔎

**Phish Checker** is a lightweight, browser-based tool to help identify suspicious URLs.  
It performs basic checks to detect phishing attempts based on known techniques used in malicious links.

---

## 🔍 What is this for?

Phishing attacks often trick users by disguising harmful URLs to look like legitimate ones.  
**Phish Checker** analyzes a URL and highlights signs that may indicate it is unsafe, such as:

- Use of raw IP addresses instead of domain names
- Inclusion of an "@" symbol to mislead users about the actual destination
- Excessive use of subdomains to obscure the true host

This tool is designed for:

- Cybersecurity learners and educators
- CTF (Capture The Flag) challenges
- Phishing awareness and training programs
- Developers who want to integrate basic phishing checks into small-scale tools

It works entirely in the browser — **no internet connection required**, and **no data is sent anywhere**.

---

## ⚙️ How to Use

1. **Download the project files** and locate `index.html`.
2. **Open `index.html`** in any modern browser (Chrome, Firefox, Edge, etc.).
3. **Enter a URL** you want to analyze into the input field (e.g., `http://192.168.0.1` or `http://login.google.com@phishy.site`).
4. **Click "Check"**, and the system will immediately evaluate the URL.
5. **View the results**:
   - Green indicates the link appears safe.
   - Red indicates possible signs of phishing.

You’ll receive a detailed explanation of what might be suspicious in the link.

---

## 📄 License

This project is licensed under the MIT License.  
Feel free to modify, use, or integrate it in other tools — see the [LICENSE](./LICENSE) file for full details.

---

## ⚠️ Disclaimer

This tool is meant for **educational and ethical use only**.  
It is not a full-proof phishing detection system and should not replace professional security tools.
