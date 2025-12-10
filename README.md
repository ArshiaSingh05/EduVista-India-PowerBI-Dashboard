# 🎓 EduVista – Indian Education Insights Dashboard  
*An interactive Power BI dashboard visualizing student enrollment & teacher distribution across India.*

---

## 📌 Project Overview  
EduVista is an interactive data visualization project that explores India’s education system through  
state-wise insights on **students, schools, and teachers**.  
This dashboard helps users understand:

- Gross Enrollment Ratio (GER) trends  
- Distribution of school types (Co-ed, Girls, Boys)  
- Rural vs Urban school availability  
- Regular vs Contract-based teacher workforce  
- Gender distribution of teachers  
- State-to-state educational disparity through a custom India map

---

## 🛠️ Tool Stack  
- **Power BI** – Data modelling & dashboard development  
- **Power Query** – Data cleaning & transformation  
- **DAX (Data Analysis Expressions)** – Calculated measures & slicers  
- **TopoJSON** – Custom Indian map integration  
- **Microsoft Excel** – Dataset storage & preprocessing  

---

## 📂 Project Structure  
│── Datasets/
│── ImagesUsed/
│── arshia_project.pbix # Final Power BI dashboard
│── Arshia_report.doc # Project report
└── india.json # Custom India TopoJSON map  


---

## 📊 Key Features  

### 🔹 1. Student & School Insights  
- Gross Enrollment Ratio (Middle, Secondary, Higher Secondary)  
- School distribution by type (Co-ed / Girls / Boys)  
- Rural vs Urban school comparison  
- Dynamic slicers for **management type**, **levels**, and **categories**

### 🔹 2. Teacher Insights  
- Regular vs Contract teacher distribution  
- Gender-wise segmentation (Male/Female)  
- Comparison across school categories (PS, UPS, SS, HSS)  
- Dedicated interactive Teacher dashboard page  

### 🔹 3. Visual Design  
- Soft educational theme  
- Transparent background illustrations  
- Rounded visual containers  
- Hyperlinked navigation buttons  
- Clean layout optimized for storytelling  

---

## 🛠️ Data Processing Workflow  

### **Step 1 – Data Import**  
Imported multiple government datasets covering schools & teachers across states of India.

### **Step 2 – Data Cleaning**  
- Standardized state names  
- Cleaned inconsistent categories  
- Handled missing/blank entries  
- Separated regular/contract teacher data  
- Added structured feature columns  

### **Step 3 – Data Modelling**  
Built relationship model using:  
- `Dim_States`  
- `Dim_Level`  
- `Dim_Category`  
Mapped to fact tables for student, school & teacher datasets.

### **Step 4 – DAX Measures**  
Created metrics for:  
- GER levels  
- Student totals by management type  
- Teacher gender/contract categories  
- Dynamic pie chart values  
- Regular vs Contract totals  

### **Step 5 – Dashboard Pages**  
- **Page 1:** Students & Schools  
- **Page 2:** Teachers  
- Custom navigation buttons  

---

## 📸 Dashboard Preview  
*(Add screenshots here later)*  

---

## 🚀 Future Enhancements  
- Add real-time API-driven data  
- Allow district-level drill-down  
- Add ML-driven insights (dropout prediction)  
- Add theme switcher & multilingual labels  

---

## 👩‍💻 Author  
**Arshia Singh**  
- 🌐 *LinkedIn:* https://www.linkedin.com/in/YOUR-LINK  
- 💻 *GitHub:* https://github.com/YOUR-USERNAME  

---

## 📜 License  
This project is open-source under the **MIT License**.
