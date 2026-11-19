# Daily Habit and Bowel Movement Tracker

A single-file web dashboard for logging daily habits (steps, water/fluid intake, and notes) alongside bowel movements (Bristol stool scale, pain level, bleeding severity, time, and remarks), complete with trend charts, multi-criteria filtering, dark mode, and local JSON backup/restore.

**Live Demo:** [https://mytf49.github.io/Daily-Habit-and-Bowel-Movement-Tracker/](https://mytf49.github.io/Daily-Habit-and-Bowel-Movement-Tracker/)

**Current Build:** `1.0b3_20261119`

---

## Features

- **Summary Strip:** At-a-glance cards showing fluid intake vs. a `2,000 mL` daily target, total steps vs. a `10,000` daily step target, and a rolling 7-day average Bristol stool type.
- **📊 Trend Analysis Charts:**
  - **Steps vs. Water Intake (mL):** Dual-axis line chart with dashed target reference lines (`2,000 mL` water and `10,000` steps) and date range selector (`Last 7 Days`, `Last 14 Days`, `Last 30 Days`, `All Time`).
  - **Bristol Hardness & Pain:** Dual-axis line chart tracking average Bristol type (`1–7`) with a `Type 4` reference line and average pain (`0–5`), highlighting dates with bleeding in red on the x-axis and providing log count + bleeding status in tooltips.
- **🌿 Daily Habits Logging:**
  - Date selector with a quick **Today** jump button.
  - Step counter and a unified fluid intake box supporting bottle size × bottle count (`±0.5` step buttons) or exact total fluid in `mL` with two-way syncing.
  - Daily remarks/notes, **Save Habits**, and **Clear Habits**.
- **💩 Bowel Movement Logging:**
  - Supports multiple entries per day with customizable date and time.
  - Bristol stool scale (`Type 1` to `Type 7`), `0–5` pain scale slider, bleeding level (`0–3`), optional remarks, plus **Edit** and **Delete** support for existing entries.
- **🕒 History & Data Filtering:**
  - Collapsible daily log cards with date selection and search/filtering by keyword, specific date, stool type (`1–7`), minimum pain level (`1+` to `5`), bleeding presence, fluid range (`Min–Max mL`), and steps range (`Min–Max`).
- **📂 Data Management (JSON Import & Export):**
  - Export all records to a timestamped `.json` backup file or import a `.json` backup via drag-and-drop or file picker.
- **Dark Mode & Local Storage:**
  - Persistent light/dark theme toggle and automatic browser `localStorage` persistence.

---

## Usage

1. Open [https://mytf49.github.io/Daily-Habit-and-Bowel-Movement-Tracker/](https://mytf49.github.io/Daily-Habit-and-Bowel-Movement-Tracker/) (or open `index.html` locally in any modern browser).
2. Use **🌿 Daily Habits** to record daily steps, fluid intake, and notes for the selected date.
3. Use **💩 Bowel Movement** to log one or more entries for a date and time.
4. Review trends in **📊 Trend Analysis**, search or filter past entries in **🕒 History & Data**, and periodically export a **JSON** backup via **📂 Data Management**.

---

## Data & Privacy

All tracking data is stored locally in your browser's `localStorage` under the key `health_tracker_db` (with theme preference under `dark_mode`). Nothing is sent to an external server by the app itself, so exporting JSON backups is recommended if you switch browsers or clear site data.
