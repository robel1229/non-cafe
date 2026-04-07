# 🍲 Non-Cafe System (Ethiopian University Edition)

[![Status](https://img.shields.io/badge/Status-Live-success.svg)](#)
[![Version](https://img.shields.io/badge/Version-2.0.0--stable-blue.svg)](#)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-orange.svg)](#)

A high-performance, mobile-first web application engineered specifically for Ethiopian university students. This system simplifies the complexity of "Non-Cafe" (off-campus) living by managing shared meal expenses, group finances, and local calendar tracking.

[**Launch Web App**](https://robel1229.github.io/non-cafe/)

---

## 🚀 Core Features

### 📅 Cultural Integration
* **Ethiopian Calendar (E.C.):** Native support for the local calendar system. All entries are automatically timestamped with the correct Ethiopian date.
* **Smart Meal Context:** Detects the time of day to automatically suggest Breakfast, Lunch, or Dinner categories.

### 💰 Financial Management
* **Smart Split Engine:** Automatically calculates individual shares down to the cent using a custom rounding-up algorithm.
* **Dynamic Group Logic:** Add or remove members on the fly; the system recalculates debts instantly for every meal.
* **Monthly Summary Dashboard:** A dedicated section showing individual grand totals and a breakdown of spending by location (e.g., Central, Amazon, Wude).

### 🔒 Privacy & Security
* **Private Group Locking:** Create private group IDs with password protection powered by Firebase.
* **Admin Controls:** Sensitive actions like deleting records or clearing history are protected by group-specific credentials.

### 📊 Data Portability
* **Excel Export (.xlsx):** Generate professional spreadsheets for offline record-keeping.
* **PDF Reports:** Download formatted summary reports for easy sharing via Telegram or WhatsApp.
* **Offline Persistence:** Uses `LocalStorage` alongside Firebase to ensure data remains accessible even with spotty campus Wi-Fi.

---

## 🛠️ Technical Stack

* **Frontend:** HTML5, CSS3 (Modern Flexbox/Grid), JavaScript (ES6+)
* **Backend:** Firebase Realtime Database
* **Libraries:** * `SheetJS (XLSX)`: Complex spreadsheet generation.
    * `jsPDF & AutoTable`: PDF report engine.
    * `QRCode.js`: Instant group sharing logic.
* **UI/UX:** Custom modern design with a mobile-first responsive layout.

---

## 📖 How to Use

1. **Join/Create a Group:** Enter a unique Group ID. If it's a new group, set a password.
2. **Setup Members:** Add your roommates or friends to the member list.
3. **Log a Meal:** * Enter the location (e.g., "Wude").
    * Input the total price.
    * Tick the names of those who shared the meal.
4. **Save:** Click "Save Daily Record" to sync with the cloud.
5. **Settle Up:** At the end of the month, use the "Individual Totals" section to see who owes what.

---

## 👨‍💻 Author

**Aman** *Electrical and Computer Engineering Student @ DTU*

Developed with ❤️ for the Ethiopian Student Community. © 2026

---

## 📄 License
This project is open-source. Feel free to fork and improve.
