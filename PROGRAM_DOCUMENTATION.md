# 💻 PROGRAM DOCUMENTATION
## Project: Digital Logic — Number System Converter (PWA)

### 📄 Version: 1.0
**Maintainer:** Ezekiel Brian Onyango  
**Repository:** [github.com/BrnEzekiel/Digital-Logic](https://github.com/BrnEzekiel/Digital-Logic)  
**Date Updated:** October 2025  
**App link** [Converter](https://brnezekiel.github.io/Digital-Logic/)
---

## 1. 🎯 Purpose of the Program

The **Digital Logic Number System Converter** is a **Progressive Web App (PWA)** that allows users to **convert numbers between Binary, Octal, Decimal, and Hexadecimal systems**. It’s an educational tool designed for students, developers, and educators learning about digital logic and base systems.

**Objectives:**
- Enable fast, accurate number system conversions.
- Provide **step-by-step explanations** for learning.
- Work **offline** via PWA technology.
- Be **installable** on Android, iOS, and desktops.

---

## 2. 🧩 Functional Overview

### ✳️ Core Features
- Convert numbers across bases (2, 8, 10, 16)
- Handle **fractional values**
- Show **step-by-step** breakdown
- **Offline & installable** (PWA)
- Responsive across all screen sizes

### 🧠 Conversion Matrix
| From | To |
|------|----|
| Binary | Octal, Decimal, Hexadecimal |
| Octal | Binary, Decimal, Hexadecimal |
| Decimal | Binary, Octal, Hexadecimal |
| Hexadecimal | Binary, Octal, Decimal |

---

## 3. ⚙️ System Requirements

| Requirement | Minimum | Recommended |
|--------------|----------|--------------|
| Browser | Chrome 90+, Edge 90+, Safari 14+ | Latest Chrome |
| Internet | Optional | Required for updates only |
| Device | Android/iOS/PC | Any PWA-capable device |
| Node/Python | For local server | Latest version |

---

## 4. 🧱 System Components

| File | Description |
|------|-------------|
| **index.html** | Main interface and UI layout. |
| **manifest.json** | Defines PWA properties (icons, display, name). |
| **service-worker.js** | Enables offline functionality through caching. |
| **assets/** | Holds Screenshots. |
| **README.md** | Project summary and setup instructions. |
| **PROCESS_DOCUMENTATION.md** | Workflow and process documentation. |

---

## 5. 🧮 Program Logic

### 5.1 Conversion Algorithm
```javascript
function convertNumber(inputValue, fromBase, toBase) {
    let decimalValue = parseInt(inputValue, fromBase); // Convert to decimal
    let result = decimalValue.toString(toBase).toUpperCase(); // Convert to target base
    return result;
}
```

**Logic Flow:**
1. User provides input number and selects source & target base.
2. Program converts input to **decimal**.
3. Decimal is converted to the **target base**.
4. Output is formatted and displayed with **explanation steps**.

### 5.2 Fractional Handling
- Integer and fractional parts handled separately.
- Fraction converted by **repeated multiplication/division**.
- Results rounded to ensure precision and readability.

---

## 6. 🧭 User Interface Description

| Section | Description |
|----------|-------------|
| Input | Field to enter number and choose input base. |
| Output | Displays converted value. |
| Explanation | Shows the step-by-step conversion process. |
| Buttons | Convert, Clear, and Reset controls. |
| Install Prompt | Option to install the app (PWA feature). |

**Example Flow:**
- Input: `1011.01`  
- From Base: `Binary`  
- To Base: `Decimal`  
- Output: `11.25`  
- Steps:  
  `(1×2³) + (0×2²) + (1×2¹) + (1×2⁰) + (0×2⁻¹) + (1×2⁻²)`

---

## 7. 🧠 Data Flow Diagram

```
User Input
   ↓
Input Validator
   ↓
Conversion Logic (to Decimal → to Target Base)
   ↓
Result Formatter
   ↓
Output Display (HTML DOM)
   ↓
Service Worker Cache (for offline use)
```

---

## 8. 🧰 Error Handling

| Error | Cause | Resolution |
|--------|--------|-------------|
| Invalid Input | Wrong digit for base | Display error message |
| Empty Field | No input provided | Prompt user for input |
| Unsupported Base | Base outside supported range | Disable option |
| Overflow | Fraction too long | Round result automatically |

---

## 9. 📱 PWA Features

| Feature | Description |
|----------|-------------|
| **Offline Access** | App works fully offline after first load. |
| **Add to Home Screen** | Installable like a native app. |
| **Cache Management** | Uses service worker for caching HTML, JS, and assets. |
| **Auto Updates** | Updates cached files automatically when new version detected. |

Example from `service-worker.js`:
```javascript
self.addEventListener('install', event => {
  event.waitUntil(
    caches.open('v1').then(cache => {
      return cache.addAll(['/', '/index.html', '/manifest.json', '/script.js', '/assets/style.css']);
    })
  );
});
```

---

## 10. 👥 Program Roles and Contacts



| Role | Responsibilities | contacts
|------|------------------|------------|
| Maintainer | Manage releases and merges. |  ezekiel.16066@students.kyu.ac.ke
| Developer | Write and test code. |murithi.21909@students.kyu.ac.ke & ezekiel.16066@students.kyu.ac.ke  
| Tester | Validate conversions. | onyango.22794@students.kyu.ac.ke
| Doc Lead | Maintain documentation. |  murithi.23216@students.kyu.ac.ke & otieno.21435@students.kyu.ac.ke

---

## 11. 🧾 Version History

| Version | Date | Description |
|----------|------|-------------|
| 1.0 | Oct 2025 | Initial stable release with full conversion logic and PWA features. |

---

## 12. 🚀 Future Enhancements

- Add Base 32 / Base 64 support.
- Enable Dark/Light Mode.
- Implement conversion history (IndexedDB).
- Add voice input for accessibility.
- Introduce AI-driven learning tips.

---

## 13. 🧭 Summary

The **Digital Logic Number Converter PWA** combines functionality, simplicity, and modern web technology to teach and perform number conversions.  
Its maintainable codebase, PWA capabilities, and educational value make it a standout digital logic tool for students and developers alike.
