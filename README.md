# 💩 Daily Habit and Bowel Movement Tracker

A lightweight, fully private, client-side health and habit dashboard designed to help you track daily lifestyle habits alongside gastrointestinal symptoms and bowel movements. 

Built as a single, self-contained file using **HTML**, **Tailwind CSS**, and **Chart.js**, with zero backend or external servers required—all records stay entirely secure and private in your browser's `localStorage`.

---

## 🌟 Features

* **🚶‍♂️ Daily Habits Tracking:** Log daily step counts and water/fluid intake (using a convenient bottle size multiplier or exact mL entries) alongside daily personal notes.
* **💩 Bowel Movement Logging:** Log multiple bowel movement events per day with timestamps, Bristol Stool Scale types (1–7), pain scale ratings (0–5), and bleeding severity indicators.
* **📊 Visual Trend Analysis:** Interactive dual-axis charts powered by Chart.js displaying trends over 7 days, 14 days, 30 days, or all time, complete with target reference lines.
* **📂 Data Management:** Easily export your complete database to a JSON backup file or restore/import records via drag-and-drop.
* **🌙 Dark Mode Support:** Seamlessly toggle between light and dark themes with persistent state storage.
* **📱 Fully Responsive:** Optimized mobile-first view that scales up smoothly into a multi-column dashboard grid on large desktop screens.

---

## 🚀 Getting Started / Installation

Since this project is contained within a single `index.html` file, running or hosting it is effortless:

1. Download or clone this repository.
2. Double-click the `index.html` file to open and run it instantly in any modern web browser.
3. *(Optional)* Host it for free on **GitHub Pages** to access and update your health logs securely from your phone or any other device.

---

## 📋 Update Log & Changelog

### **Build 1.0b2_20261118 (Latest)**
* Added full-width responsive large-screen support (`max-w-full` layout).
* Reorganized dashboard into a clean multi-column grid on desktop views and placed trend charts side-by-side.
* Updated chart rendering logic to ensure cleared/deleted dates do not plot lingering zero-value data points.
* Moved the build badge to a discrete bottom-right footer label.

### **Build 1.0b1_20261118 (Initial Release)**
* Initial release of the single-file habit and bowel movement tracker.
* Implemented daily habit logging (steps, fluid intake calculator, daily remarks).
* Implemented multi-entry bowel movement logging (Bristol hardness scale, pain scale, bleeding severity).
* Added Chart.js visual analytics with customizable date range filters (7 days, 14 days, 30 days, all time).
* Added Dark Mode support with state persistence.
* Added JSON backup export and drag-and-drop import data management.

---

## 🔒 Privacy Notice

Your data privacy is 100% protected. **Daily Habit and Bowel Movement Tracker** does not use cookies, analytics, or third-party databases. All logs are stored strictly inside your browser's local storage environment (`localStorage`), meaning your health data never leaves your device unless you manually export a JSON backup.

---

## 📄 License

This project is open-source and available for personal health tracking use.
