# 🧩 Process Documentation
## Project: Digital Logic — Number System Converter (PWA)

### 🔖 Version: 1.0  
**Maintainer:** [BrnEzekiel](https://github.com/BrnEzekiel)  
**Date Updated:** October 2025  
👥 Roles and Responsibilities

| Role | Responsibilities | contacts
|------|------------------|------------|
| Maintainer | Manage releases and merges. |  ezekiel.16066@students.kyu.ac.ke
| Developer | Write and test code. |murithi.21909@students.kyu.ac.ke & ezekiel.16066@students.kyu.ac.ke  
| Tester | Validate conversions. | onyango.22794@students.kyu.ac.ke
| Doc Lead | Maintain documentation. |  murithi.23216@students.kyu.ac.ke & otieno.21435@students.kyu.ac.ke

---

## 1. 🎯 Overview and Objective

**Digital Logic** is a **Progressive Web App (PWA)** designed to **convert numbers across multiple bases** — Binary, Octal, Decimal, and Hexadecimal — including **fractional values**.  
It serves as a **learning and utility tool** for students, educators, and programmers exploring **digital logic and number systems**.  

**Key Goals:**
- Simplify number system conversions through a clean, interactive interface.  
- Show **step-by-step explanations** to enhance understanding.  
- Provide **offline capability** via PWA integration.  
- Offer **cross-platform compatibility** (web, Android, iOS installable PWA).  

---

## 2. 🏗️ System Architecture and Components

### 🧩 Technology Stack
| Component | Technology |
|------------|-------------|
| Frontend | HTML5, CSS3, JavaScript (Vanilla) |
| PWA Support | Service Worker + Manifest.json |
| Hosting | GitHub Pages |
| Version Control | Git / GitHub |
| Development Tools | VS Code, Chrome DevTools |

### 🔍 Core Functional Components
| Module | Description |
|---------|-------------|
| `index.html` | The main entry point for the web app’s UI. Hosts the conversion interface. |
| `manifest.json` | Defines app metadata, icons, and display behavior for PWA installation. |
| `service-worker.js` | Handles caching and offline access. Enables “Install App” functionality. |
| `/assets/` | Stores images, screeshots of the PWA
| `README.md` | Outlines basic project description, setup, and usage instructions. |

---

## 3. ⚙️ Development Setup Process

### 3.1 Clone the Repository
```bash
git clone https://github.com/BrnEzekiel/Digital-Logic.git
cd Digital-Logic
```

### 3.2 Run a Local Development Server
Option 1 – Using Python:
```bash
python3 -m http.server
```
Open in browser: http://localhost:8000

Option 2 – Using Node.js:
```bash
npx http-server
```

### 3.3 Folder Structure
```
Digital-Logic/
│
├── assets/                # images, 
├── index.html             # main web interface
├── manifest.json          # PWA configuration
├── service-worker.js      # offline caching logic
├── README.md              # quick project info
└── LICENSE                # project license (MIT)
```

---

## 4. 🧠 Process Workflow (End-to-End)

### 4.1 Planning & Design Phase


### 4.2 Implementation Phase


### 4.3 Testing Phase


### 4.4 Review & Merge

### 4.5 Deployment Phase


## 5. 🔁 Maintenance and Update Routine



## 6. 🧰 Best Practices

### USAGE 
- Use to convert any base to your desired base, hasle free.

## 7. 👥 Roles and Responsibilities

| Role | Responsibilities | contacts
|------|------------------|------------|
| Maintainer | Manage releases and merges. |  ezekiel.16066@students.kyu.ac.ke
| Developer | Write and test code. |murithi.21909@students.kyu.ac.ke & ezekiel.16066@students.kyu.ac.ke  
| Tester | Validate conversions. | onyango.22794@students.kyu.ac.ke
| Doc Lead | Maintain documentation. |  murithi.23216@students.kyu.ac.ke & otieno.21435@students.kyu.ac.ke

---

## 8. 🚀 Deployment Checklist

✅ Test conversions  
✅ Validate PWA and offline mode   



---

## 9. 📦 Future Improvements

| Feature | Description |
|----------|-------------|
| Dark Mode | Add toggle for better visibility. |
| Step Animation | Animate conversion explanation. |
| History | Store previous conversions. |
| Multi-language | Add Swahili, French, etc. |
| Shareable Links | Allow sharing results. |

---

## 10. 🧾 References
- [MDN: Service Workers](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)  
- [Google PWAs](https://developers.google.com/web/progressive-web-apps)  
- [GitHub Pages Guide](https://pages.github.com/)  
- [Number System Conversion](https://www.geeksforgeeks.org/number-system-conversion/)  

---

## 11. 🧭 Summary

This documentation defines the **entire operational process** for the *Digital Logic* PWA — from planning, coding, testing, and deployment to maintenance and continuous improvement.  
It ensures every update is done with structure, transparency, and precision.
