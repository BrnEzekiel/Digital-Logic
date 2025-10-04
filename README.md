# 🔢 Number System Converter (PWA)

A Progressive Web App (PWA) that allows you to **convert numbers between Binary, Octal, Decimal, and Hexadecimal systems**.  

This tool supports both **integer and fractional numbers** (e.g., `59.7737`), and it shows **step-by-step explanations** of how the conversion is done — perfect for **students, teachers, and developers** who want to *understand* the process, not just see the result.  

You can install it on your **Android or iOS device** like a native app, directly from the browser.

---

## ✨ Features

- ✅ Convert between **Binary (2), Octal (8), Decimal (10), and Hexadecimal (16)**.  
- ✅ Supports **fractional numbers** (e.g., `101.11₂`, `59.7737₁₀`, `1A.F₁₆`).  
- ✅ Provides **detailed step-by-step conversion breakdowns**.  
- ✅ Simple, clean, mobile-friendly interface.  
- ✅ Works **offline** (thanks to PWA + Service Worker).  
- ✅ Can be **installed** on Android/iOS/Desktop as a standalone app.  

---

## 📱 Installation Guide (Android & iOS)

The Number System Converter is a **PWA**, which means you don’t need to download it from the Play Store or App Store.  
Instead, you install it directly from your browser.  

### ▶️ On **Android**
1. Open the app’s GitHub Pages link in **Google Chrome** (or any Chromium browser).  
   Example:  
   ```
   https://brnezekiel.github.io/Digital-Logic/
   ```
2. Once loaded, you’ll see a popup at the bottom:  Alternatively,  tap the 3 dots on the top right, scroll down and you will find
   **“Install App”** or **“Add to Home Screen”**.  
3. Tap **Install**.  
4. The app will appear on your **home screen** like a normal app.  
5. You can now launch it offline, anytime.  

---

### 🍏 On **iOS (iPhone/iPad)**
1. Open the app’s link in **Safari**.  
2. Tap the **Share button** (the square with an arrow at the bottom).  
3. Scroll down and select **“Add to Home Screen”**.  
4. Give the app a name (e.g., *Converter*).  
5. Tap **Add**.  
6. The app icon will appear on your **home screen**.  

Now you can open and use it like a normal iOS app.  

---

### 💻 On Desktop (Windows/Mac/Linux)
1. Open the link in **Google Chrome** or **Edge**.  
2. Click the **Install App** icon in the address bar (a little “+” inside a monitor).  
3. The app will install and run in its own window, like a native desktop app.  

---

## 🛠 How to Use the Tool

1. **Enter a number** in the input box.  
   - Examples:  
     - `1011` (binary)  
     - `59.7737` (decimal)  
     - `1A.F` (hexadecimal)  

2. **Select the base to convert from** (Binary, Octal, Decimal, Hex).  

3. **Select the base to convert to** (Binary, Octal, Decimal, Hex).  

4. **Click Convert** → The app will:  
   - Show the **final result**.  
   - Display the **step-by-step process** of conversion.  

---

## 📖 Example Conversion

**Input:**  
```
59.7737 (Decimal) → Binary
```

**Output:**  
```
Result: 111011.11000100110011₂
```

**Steps:**  
```
Step 1: Convert integer part (59) → binary:
59 ÷ 2 = 29 remainder 1
29 ÷ 2 = 14 remainder 1
14 ÷ 2 = 7 remainder 0
7 ÷ 2 = 3 remainder 1
3 ÷ 2 = 1 remainder 1
1 ÷ 2 = 0 remainder 1
Integer result = 111011

Step 2: Convert fractional part (0.7737) → binary (approx):
0.7737 × 2 = 1.5474 → 1
0.5474 × 2 = 1.0948 → 1
0.0948 × 2 = 0.1896 → 0
0.1896 × 2 = 0.3792 → 0
0.3792 × 2 = 0.7584 → 1
0.7584 × 2 = 1.5168 → 1
Fractional result ≈ .110001

Final Answer = 111011.110001₂
```

---

## 📦 Tech Stack

- **HTML5 / CSS3 / JavaScript**  
- **Progressive Web App (PWA)** with `manifest.json` + `service-worker.js`  
- **Hosted on GitHub Pages**  

---

## 🚀 Deployment

If you want to deploy your own version:  

1. Fork or clone this repo.  
2. Push the files to a **GitHub Pages** branch (`main` or `gh-pages`).  
3. Go to Repo Settings → Pages → Enable GitHub Pages.  
4. Your app will be live at:  
   ```
   https://brnezekiel.github.io/Digital-Logic/
   ```

---

## 🙌 Credits

Built with ❤️ to help students and developers learn **number system conversions** in a fun and interactive way.

---

## 👥 Collaborators

| Name | Registration Number | Email |
|------|---------------------|--------|
| **Chris Munene Murithi** | CT101/G/21909/24 | murithi.21909@students.kyu.ac.ke |
| **Otieno Samwel Amos** | CT101/G/21435/24 | otieno.21435@students.kyu.ac.ke |
| **Erick Minyara Onyango** | CT101/G/22794/24 | onyango.22794@students.kyu.ac.ke |
| **Murithi Owen Muthomi** | CT101/G/23216/24 | murithi.23216@students.kyu.ac.ke |
| **Ezekiel Brian Onyango** | CT101/G/16066/22 | ezekiel.16066@students.kyu.ac.ke |
