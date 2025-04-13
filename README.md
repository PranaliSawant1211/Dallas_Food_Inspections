# Dallas Food Inspections - Data Profiling & Modeling Project

## 📊 Project Overview

This repository showcases a complete data engineering workflow focused on Dallas city food inspection records. Using **Alteryx**, I performed advanced data profiling and transformation on over **80,000 records** of food establishment inspections. The project further includes **physical and dimensional data modeling** to support scalable reporting and business intelligence use cases.

The initiative is designed to uncover critical hygiene trends, enable risk-based inspections, and lay the groundwork for future predictive analytics in the public health domain.

---

## 🗂️ About the Dataset

- **Source**: [City of Dallas Open Data Portal - Food Inspection Scores](https://www.dallasopendata.com/)
- **Dataset Name**: *Food Establishment Inspection Scores*
- **Size**: ~100K+ inspection records
- **Time Span**: Covers multiple years of food inspection activity across restaurants, schools, retail food outlets, and public kitchens.
- **Fields Included**:
  - Establishment Name
  - Address, ZIP Code, Council District
  - Inspection Date, Inspection Type (Routine, Follow-up)
  - Inspection Score
  - Violation Details
  - Inspector Notes and Comments

The dataset includes a rich mix of structured and semi-structured fields, enabling deep exploratory analysis and reporting.

---

## 🎯 Objectives

- Conduct in-depth **data profiling** to evaluate data health and usability.
- Build a reproducible **data preparation pipeline** using Alteryx Designer.
- Design **normalized (physical)** and **star schema (dimensional)** data models for reporting efficiency.
- Provide a reliable data foundation for downstream BI dashboards and advanced analytics.

---

## 🛠️ Tools & Technologies

- **Alteryx Designer** – Used for profiling, data cleansing, transformation, and workflow creation.
- **ER/Studio / DM1 Files** – Data modeling (ER diagrams, schema documentation).
- **GitHub** – Code and workflow version control.

---

## 📁 Repository Structure

| File Name                        | Description |
|----------------------------------|-------------|
| `DallasDataPrep.yxmd`           | Main Alteryx workflow that cleans, deduplicates, and transforms the inspection dataset. |
| `DallasDataProfiling.yxmd`      | Workflow performing data profiling to check nulls, types, frequencies, and anomalies. |
| `DallasDataProfiling.bak`       | Backup of the profiling workflow. |
| `DallasDimensionalModel.DM1`    | Dimensional star schema with fact and dimension tables for BI tools. |
| `DallasPhysicalModel.DM1`       | Normalized relational model showing table relationships, keys, and constraints. |
| `DataPrep.yxmd`                 | Additional prep workflow focusing on sub-processes and enhancements. |
| `DataPrep.bak`                  | Backup of the data preparation workflow. |
| `.gitattributes`                | Git version control file. |

---

## 🔍 Key Features

- **Data Profiling**:
  - Summary statistics, field data types, min/max values
  - Frequency distribution of categorical variables
  - Missing value analysis and duplicate detection

- **Data Preparation**:
  - Standardized field formats (dates, text)
  - Created derived columns like inspection month/year and violation counts
  - Removed incomplete and corrupted records

- **Data Modeling**:
  - **Physical Model**: Relational structure optimized for OLTP
  - **Dimensional Model**: Star schema with `FactInspection` and dimension tables such as `DimEstablishment`, `DimDate`, `DimViolation`, etc.
  - Enables slice-and-dice operations and trend analysis in BI tools

---

## 📈 Business Use Cases

- Monitor establishments with frequent violations to prioritize re-inspections.
- Identify inspection score trends over time and by geographic region.
- Enable public dashboards for transparency and awareness.
- Support predictive analytics for early detection of health risk zones.

---

## 💡 Skills Demonstrated

- Data Engineering and preparation using **Alteryx workflows**
- Data Quality and exploratory analysis via **profiling techniques**
- Data Architecture and schema design using **ER modeling**
- Documentation and reproducibility using **Git and GitHub**

---

## 🙋‍♀️ Author

**Pranali Sawant**  
📫 [LinkedIn](https://www.linkedin.com/in/pranalisawantt12/) | 📧 pranalisawantt12@gmail.com  
🔬 Data analyst passionate about public health data, process automation, and transforming raw datasets into actionable insights.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

⭐ If you found this project useful or insightful, feel free to give it a ⭐ on GitHub or connect with me on LinkedIn!
