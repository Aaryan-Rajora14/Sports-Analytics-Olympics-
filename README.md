# 🏅 Olympics Sports Analysis Dashboard in Power BI

<img width="734" height="651" alt="Image 1" src="https://github.com/user-attachments/assets/f547c6c4-c8e5-4e68-a77f-07577fd05229" />

## Welcome, Students! 👋

Hello aspiring data analysts and BI developers! This repository contains my **Olympics Sports Analysis Dashboard** built in **Power BI**. 

I created this project to demonstrate real-world dashboard development using historical Summer Olympics data (medals, athletes, sports, countries, etc.). 

Whether you're a beginner learning Power BI or an intermediate student looking to build polished, interactive reports, this README will guide you step-by-step — just like I'm teaching a class!

---

## 🎯 Project Objective

The goal is to turn raw Olympics data into **actionable insights**:
- Which countries dominate specific sports?
- Medal trends over the years by gender and event.
- Top performers, athlete participation, and more.

Users can filter by **Year**, **Country**, **Sport**, **Medal Type**, and more using slicers and interactive visuals.

---

## 🛠️ Tech Stack & Features

- **Power BI Desktop** (with DAX for measures and calculated columns)
- **Custom Visuals**: Chiclet Slicer, Image Carousel (for logos/medals)
- **Key Visuals**:
  - KPI cards (Total Medals, Gold/Silver/Bronze)
  - Bar/Column charts for country & sport rankings
  - Line charts for trends over time
  - Donut/Pie for gender or medal distribution
  - Maps (if geospatial data included)
  - Medal icons and Olympic branding visuals
- **Theme**: Olympic-inspired colors (gold, silver, bronze accents)
- **Interactivity**: Cross-filtering, drill-through, bookmarks

---

## 📊 Dataset

- Historical Summer Olympics data (athletes, events, medals, nations)
- Sources typically include Kaggle or public Olympics datasets
- Columns: Year, City, Sport, Discipline, Athlete, Country, Medal (Gold/Silver/Bronze), Gender, etc.

---

## 📘 Step-by-Step Dashboard Creation Guide (For Students)

### Phase 1: Planning & Data Understanding
1. Define business questions (e.g., "Top 10 countries by gold medals?")
2. Explore the raw dataset in Excel/Power Query.

### Phase 2: Data Preparation (Power Query)
1. **Get Data** → Load CSV/Excel files.
2. Clean data:
   - Remove duplicates
   - Handle missing values
   - Standardize medal names and country codes
   - Create calculated columns (e.g., Medal Count = 1 if medal exists)
3. Transform: Unpivot if needed, merge tables.

### Phase 3: Data Modeling
1. Create relationships between tables (e.g., Athlete → Events → Medals).
2. Build **DAX Measures**:
   ```dax
   Total Medals = COUNTROWS(Medals)
   Gold Medals = CALCULATE([Total Medals], Medals[Medal] = "Gold")


Happy Learning 

Building skills is the only thing where you never regret your choices.
