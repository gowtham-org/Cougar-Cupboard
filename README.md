# Cougar Cupboard Data Dashboard

This project visualizes food pantry usage patterns at the **University of Houston's Cougar Cupboard**, using a fully integrated pipeline from **Google Forms → Google Sheets → Power BI**. The goal is to track resource distribution and identify patterns in student visits to better inform support services.

---

## 🧩 Project Workflow

### 1️⃣ Google Form – Data Collection
- A custom **Google Form** is used by students to log their Cougar Cupboard visits.
- Form Fields:
  - **UH ID**
  - **Date & Time of Visit**
  - **Items Collected** (e.g., Bag of Rice, Bar of Soap)
  - **Quantity**
  - **Visit Type** (Meal or Essential)

### 2️⃣ Google Sheets – Real-Time Data Storage
- The Google Form is connected to a **Google Spreadsheet**, where all submissions are automatically recorded.
- Additional columns in the sheet process:
  - Date formatting
  - Time extraction
  - Day of the week
  - Item categorization (e.g., Meal vs Essential)

### 3️⃣ Power BI Desktop – Data Visualization
- The **Power BI dashboard** (`Cougar_cupboard.pbix`) is connected to the **Google Spreadsheet** as its data source.
- Key Feature: **Auto-refreshable connection**
  - Any new form submissions reflected in Google Sheets will automatically update in Power BI when you **click "Refresh"**.
- Visual Elements Include:
  - Weekly & monthly trends
  - Item frequency charts
  - Category distribution (Meals vs Essentials)
  - Filters for date, time, item type, etc.

---

## 📊 Dashboard Highlights

| Visualization      | Purpose                                      |
|---------------------|----------------------------------------------|
| Bar Chart           | Shows most commonly requested items          |
| Line Chart          | Tracks usage trends over weeks and months    |
| Pie Chart           | Displays share of meals vs essentials        |
| Filters (Slicers)   | Enable dynamic filtering by day, time, etc.  |

---

## 🔄 Live Update Mechanism

✅ **Fully Automated Pipeline**  
→ Student fills Google Form  
→ Data instantly enters Google Sheet  
→ Power BI syncs to the sheet  
→ Click **"Refresh"** in Power BI to view the updated dashboard

This setup ensures real-time analytics with minimal manual effort.

---

## 📁 Project Files

| File                                | Description                         |
|-------------------------------------|-------------------------------------|
| `Cougar_Cupboard_Usage_Sample-1.xlsx` | Sample extracted data from Google Sheet |
| `Cougar_cupboard.pbix`             | Power BI file containing dashboard visuals |

---

## 🎯 Benefits

- Automated and low-maintenance data workflow
- Real-time insights into student needs
- Easy monitoring of pantry stock trends
- Valuable for operational planning and reporting

---

## 🔒 Data Privacy

- No personally identifiable information is shared publicly.
- UH IDs and sensitive details are anonymized for reporting.
