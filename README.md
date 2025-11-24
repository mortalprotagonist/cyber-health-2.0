# ⭐ Phishing Awareness Demo – Cyber Health 2.0

A fully functional phishing-simulation demo created to educate users on how phishing attacks work.  
This project demonstrates how easily stolen credentials can be collected through a fake login page and visualized using a real-time analytics dashboard.

> ⚠️ **Important:**  
> This project is for **educational and awareness purposes only**.  
> It must **not** be used for malicious activities.

---

## 📌 Project Overview

This project simulates a phishing attack workflow:

1. A user enters credentials on a fake login page.
2. The data is sent to a Google Apps Script backend.
3. Credentials are stored in a Google Sheet.
4. The user is redirected to an awareness page explaining the attack.
5. A dashboard visualizes all submitted data with charts and tables.

This demonstrates:
- How phishing pages trick users  
- Why URL verification is important  
- How attackers harvest data  
- How stolen data can be analyzed  

---

## 🚀 Features

### 🔐 Fake Login Page
- Mimics a real login form  
- Sends data to Apps Script backend  

### ⚡ Google Apps Script Backend
- Handles POST submissions  
- Stores username/password in Google Sheets  
- Returns JSON through GET for the dashboard  

### 📊 Analytics Dashboard (Chart.js)
- Username frequency chart  
- Password frequency pie chart  
- Total submissions counter  
- Raw submissions table  
- Auto-update from Google Sheets  

### 🎭 Awareness Page
Shows a "Gotcha!" message explaining:
- What phishing is  
- How you were tricked  
- Safety tips  

---

## 🛠 Tech Stack

| Component | Technology |
|----------|------------|
| Frontend | HTML, CSS, JavaScript |
| Backend | Google Apps Script |
| Database | Google Sheets |
| Hosting | GitHub Pages |
| Charts | Chart.js |

---

## 📁 Project Structure

```
Cyber-Health-2.0/
│── index.html            # Fake login page
│── success.html          # Awareness page
│── dashboard.html        # Dashboard UI
│── README.md             # Documentation
│── /assets               # (Optional) images, styles, scripts
```

---

## 🚀 Deployment Steps

### 1️⃣ Deploy Apps Script
- Go to **Deploy → New Deployment → Web App**
- Execute as: **Me**
- Access: **Anyone**
- Copy the `/exec` URL

### 2️⃣ Update Dashboard Fetch URL
Replace with your script URL:
```js
fetch("YOUR_SCRIPT_URL/exec?action=getData")
```

### 3️⃣ Host on GitHub Pages
- Go to **Settings → Pages**
- Source: `main` → root (`/`)
- Site becomes live at:  
  `https://your-username.github.io/your-repo-name/`

---

## 📸 Screenshots (Add Later)
```
Add images of:
- Login page
- Awareness page
- Dashboard charts
- Google Sheet data
```

---

## ⚠️ Disclaimer

This project is strictly for **education and cybersecurity awareness**.  
Never use this for real credential harvesting or malicious intent.  
Always follow ethical guidelines and privacy laws.

---

## 💬 Need Help?

Want to add:
- More charts?  
- Cleaner UI?  
- Admin login?  
- Themes?  
- Professional styling?

Just ask — happy to help! 🚀
