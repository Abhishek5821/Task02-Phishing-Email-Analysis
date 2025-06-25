# 🛡️ Phishing Email Analysis Report

**Internship Task 2: Cybersecurity**

This repository contains an analysis of a phishing email example from Hook Security.  
🔗 Example Source: [Google Phishing Example](https://www.hooksecurity.co/phishing-examples/google-phishing-example)

---

## 📩 Sample Email Text:

> “We noticed suspicious activity in your Google account. Please login immediately to verify your identity.  
> If you don’t, your account will be deactivated.  
> [Click here to secure your account]”

---

## 🚩 Phishing Indicators Identified:

1. **Suspicious Sender Address**  
   - The original email is likely from a fake Google-like domain (e.g., `security@googl3.com`), not `@google.com`.

2. **Deceptive Link**  
   - Link text is "Click here", but the real URL leads to a fake login page.  
   - Hiding the URL is a red flag.

3. **Scare Tactics**  
   - Language like "suspicious activity", "verify your identity", and "your account will be deactivated" is designed to create panic.

4. **Generic Message**  
   - No personal greeting or account details, which legitimate services usually include.

5. **Grammar Warning**  
   - Slightly off: “Please login” should be “log in”.  
   - Big companies have professional communication.

6. **Missing Branding**  
   - No Google logo, footer, or other visual authenticity cues.

---

## ✅ Final Conclusion:

This is a **phishing email**. The attacker is attempting to steal login credentials by imitating a security alert from Google.

---

## 📁 Files Included:

- `README.md` – This file (full report)
- `fake_email_example.txt` – The raw sample text from the phishing email
-  `screenshot.png` – Visual of the sample email 

---

> ⚠️ For awareness only. Never click suspicious links or provide personal data in emails that feel off.

