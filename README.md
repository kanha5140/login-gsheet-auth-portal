# 🌌 NEO-CYBER LOGIN GATEWAY
> **Status:** SECURITY_LEVEL_CRITICAL // SYSTEM_ACTIVE
> **Engine:** Vanilla JS / CSS3-Grid / GAS-Backend



A high-performance, cyberpunk-themed authentication interface designed for seamless integration with **Google Sheets (Excel)**. This portal uses an asynchronous "handshake" to validate credentials against a remote serverless database.

---

## ⚡ SYSTEM SPECS
* **UI Architecture:** Glassmorphism & CSS-3D Grid Engine.
* **Database:** Remote Spreadsheet (Real-time syncing).
* **Authentication:** Non-SQL, JSON-based POST requests.
* **Animation:** GPU-accelerated keyframes (60fps).

---

## 🛠️ CORE MODULES

### 🖥️ Front-End (Client)
The interface uses a **CSS perspective engine** to simulate a 3D environment. All inputs are sanitized and processed via the `Fetch API` to ensure the UI never freezes during authentication.

### 📡 Back-End (Serverless)
Leverages **Google Apps Script** as a middleware. It treats your Google Sheet like a high-speed database, querying rows for `USER_ID` and `ACCESS_CODE` matches.



---

## 🚀 INITIALIZATION

To deploy your own instance of the terminal:

1.  **DATABASE SETUP**
    * Create a Google Sheet.
    * Column A: `username` | Column B: `password`.
2.  **SCRIPT LINKING**
    * Open `Extensions > Apps Script`.
    * Deploy the `code.gs` (provided in `/backend`) as a Web App.
    * Set permissions to **"Anyone"**.
3.  **SYNC TERMINAL**
    * Copy your Web App URL.
    * Update `const SCRIPT_URL` in `index.html`.

---
---

## 🛠️ CUSTOMIZATION & SUPPORT
Need this system adapted for your specific project? I am available for custom modifications, including:
* **UI/UX Re-branding:** Custom color schemes and logos.
* **Feature Expansion:** Adding multi-page dashboards or data visualization.
* **Database Migration:** Moving from Google Sheets to Firebase or SQL.

📩 **[CONTACT ME FOR MODIFICATIONS](mailto:kanha5140q@gmail.com)**

## 📂 DIRECTORY STRUCTURE
```text
├── index.html           # Main Terminal Interface
├── dashboard.html       # Authorized Access Zone
├── backend/
│   └── Google sheet          # Server-side Logic
└── assets/              # Interface Metadata
