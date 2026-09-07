# 🛡️ Getting Started with Burp Suite

> *Intercept, analyze, exploit, and conquer web apps.*

A straightforward guide to setting up and navigating **Burp Suite**—the ultimate weapon for web penetration testers and bug hunters.

---

## ⚡ Quick Setup

1. **Fire up Burp Suite** (Community or Pro).
2. **Configure the Proxy**: Route your browser traffic through `127.0.0.1:8080` (Pro-tip: Use *FoxyProxy* or Burp's built-in browser).
3. **Trust the CA Certificate**: Navigate to `http://burpsuite` in your configured browser to download and install the certificate to inspect HTTPS traffic smoothly.

---

## 🧰 Core Arsenal

* **Proxy (`Ctrl + Shift + M`)**: Intercept and manipulate live HTTP/S requests/responses on the fly.
* **Repeater (`Ctrl + R`)**: Tweak and resend individual requests to test server logic and hunt bugs manually.
* **Intruder (`Ctrl + I`)**: Automate brute-force attacks, fuzz parameters, and bypass inputs.
* **Target / Site Map**: Map out the application's attack surface and directory structure.

---

> *“To understand the web, you must become the middleman.”* 💀
