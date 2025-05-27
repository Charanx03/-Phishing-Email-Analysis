# 📧 Task 2: Phishing Email Analysis

## ✅ Email Sample Overview

- **From:** support@peypal.com  
- **To:** user@gmail.com  
- **Subject:** Urgent Action Required – Account Access Limited  
- **Body Summary:** Claims unusual login activity and urges recipient to click a link to "verify identity" or risk account suspension.

---

## 🔍 Phishing Indicators Identified

| 🔐 Indicator | 📝 Details |
|-------------|-----------|
| **🧑‍💻 Spoofed sender address** | `support@peypal.com` mimics `@paypal.com`, replacing "a" with "e" |
| **🌐 Fake website link** | URL: `http://peypal-security-check.com/login` is not an official PayPal domain |
| **⚠️Urgent language** | Threatens account suspension if no action is taken within 24 hours |
| **✍️ Spelling/Grammar flaws** | “Valued PeyPal Customer” is generic, and sentence flow feels slightly off |
| **🕵️‍♂️ Impersonation of brand** | Poses as PayPal with fake support email and formatting to appear legitimate |

---

## 🧠 Header (if available)

*Note: This sample does not include full email headers. If available, headers can be analyzed using [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx).*

---

## 🚫 Link Analysis

- **Text shown:** "Click the link below to verify your account"
- **Actual link:** `http://peypal-security-check.com/login`  
- ✅ Checked on [VirusTotal](https://www.virustotal.com/) (in real-world usage – don’t click).
- ❌ Domain is not related to PayPal, making it a phishing trap.

---

## 📌 Summary & Conclusion

This email exhibits **multiple phishing indicators**:
- Fake sender domain
- Dangerous URL
- Urgency
- Brand impersonation

A recipient clicking the link risks losing login credentials or installing malware.

---

## ✅ Recommendation

Never click links in suspicious emails. Always verify:
- Sender domain
- Link destination
- Official branding and language

Use tools like VirusTotal and header analyzers to confirm legitimacy.
