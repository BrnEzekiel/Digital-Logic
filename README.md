# 🔢 Number System Converter (C++)

A **C++ console application** that converts numbers between different number systems:  
✨ **Decimal ↔ Binary ↔ Octal ↔ Hexadecimal**

---

## 🚀 Features
- 🔄 Decimal → Binary / Octal / Hexadecimal  
- 🔄 Binary / Octal / Hexadecimal → Decimal  
- 🔄 Binary ↔ Octal / Hexadecimal  
- 🔄 Octal ↔ Binary / Hexadecimal  
- 🔄 Hexadecimal ↔ Binary / Octal  
- ❌ Handles invalid digits gracefully (e.g., `9` in octal input)  
- 👨‍💻 Interactive **menu-based interface**

---

## 📋 Menu Options  

| Option | Conversion |
|--------|-------------|
| 1️⃣ | Decimal → Binary |
| 2️⃣ | Decimal → Octal |
| 3️⃣ | Decimal → Hexadecimal |
| 4️⃣ | Binary → Decimal |
| 5️⃣ | Octal → Decimal |
| 6️⃣ | Hexadecimal → Decimal |
| 7️⃣ | Binary → Octal |
| 8️⃣ | Binary → Hexadecimal |
| 9️⃣ | Octal → Binary |
| 🔟 | Octal → Hexadecimal |
| 1️⃣1️⃣ | Hexadecimal → Binary |
| 1️⃣2️⃣ | Hexadecimal → Octal |
| 0️⃣ | Exit |

---

## 🛠️ How to Compile & Run  

### Linux / macOS  
```bash
g++ converter.cpp -o converter
./converter
```

### Windows (MinGW)  
```bash
g++ converter.cpp -o converter.exe
converter.exe
```

---

## 💡 Example Usage  

```
=== Number System Converter ===
1. Decimal -> Binary
2. Decimal -> Octal
3. Decimal -> Hexadecimal
...
Choose an option: 1
Enter the number: 25
Binary: 11001
```

---

## 📚 Code Highlights  

- **`toDecimal(string num, int base)`** → Converts any base to decimal  
- **`fromDecimal(int decimal, int base)`** → Converts decimal to any base  
- **`main()`** → Runs the menu loop and manages user input/output  

---

## ✅ Requirements  
- 🖥️ C++ Compiler (GCC, Clang, MSVC, MinGW, etc.)  
- Works on **Linux**, **macOS**, and **Windows**

---

## 🌟 Future Improvements  
- ➕ Support for fractional numbers (`10.5 → binary`)  
- 🎨 GUI version (Qt / Flutter)  
- 📱 Mobile app integration  

---

🔥 Ready to convert like a pro? Clone, compile, and run today!
