# 🔍 OWASP ZAP Vulnerability Scan – Juice Shop

This project demonstrates how to use **OWASP ZAP** to perform an automated vulnerability scan on a purposely vulnerable web application: [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/).

---

## 📦 Project Structure

vuln-scan-zap/
├── zap-juice-shop-report.html  # Full scan report
├── README.md                   # Project overview

---

## 🛠 Tools Used

- **OWASP Juice Shop**: A vulnerable Node.js web app for training
- **OWASP ZAP**: Open-source penetration testing tool

---

## 🧪 Scan Setup

- Target URL: `http://localhost:3000`
- Spider: Traditional spider (AJAX disabled)
- Mode: Automated scan using ZAP's Quick Start

---

## ✅ Steps Taken

1. Installed and launched Juice Shop locally
2. Opened OWASP ZAP
3. Ran an automated scan on `http://localhost:3000`
4. Exported results to HTML

---

## 📊 Vulnerability Findings

- 6+ alerts including:
  - Information Disclosure
  - Missing Security Headers
  - Cookie Without Secure Flag

> 📄 Full details are available in [`zap-juice-shop-report.html`](./zap-juice-shop-report.html)

---

## 💡 Lessons Learned

- How ZAP spiders and tests web apps
- Importance of security headers
- Basics of identifying OWASP Top 10 issues

---

## 🔗 Useful Links

- [ZAP Website](https://www.zaproxy.org/)
- [Juice Shop GitHub](https://github.com/juice-shop/juice-shop)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
