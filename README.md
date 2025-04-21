# 📊 Commercial Data Analysis Solution

## 📅 Overview  
This project presents a dynamic Power BI solution designed to simplify and automate the tracking of invoices and project commercial data in the construction domain. It provides a clear, interactive view of financial metrics across different invoice types, streamlining manual efforts and ensuring live visibility for better decision-making.

The solution contains two key report pages:  
- **Summary**  
- **Invoices Analysis**

---

## 🛠️ Tools Used  
- Power BI  
- Power Automate  
- SharePoint  
- DAX  
- Power Query  

---

## 🌐 Data Source  
The data is sourced from files uploaded to a SharePoint folder. These uploads are connected to the dashboard through a flow that updates the data model, allowing for near real-time updates.

---

## 🔗 Data Modeling  
- **Dimensions**:  
  - Date  
  - Invoice Number  
  - Project Name  

- **Facts**:  
  - Target Invoices  
  - Submitted Invoices  
  - Approved Invoices  
  - Project Details  

Inactive relationships are used between fact tables to allow for dynamic filtering and accurate calculations across views.

---

## 🔍 Analysis Process  

### 📄 First Page: Summary  
- **Filter Pane**:  
  - Dropdown filters: Project, Area, TOC Status, Invoice Number  
  - Date slicer (sliding bar)  
  - Icon to clear filters  
  - “i” icon displays a table of uploaded project details  

- **Summary Section**:  
  - Project contract type and value  
  - Estimated revenue, work volume, net due, collections  
  - Breakdown of remaining dues and invoice collections  

- **EAC Breakdown**:  
  - Pie chart of EAC components  

- **Invoice Breakdown (Target / Submitted / Approved)**:  
  - Latest number, date, and project name (based on filters or latest available)  
  - Current and cumulative values  
  - Percentage comparisons VS EAC and other types  
  - Tooltip: Gauge chart showing contributing factors for percentages  

- **Trend Line**:  
  - Work Volume VS Net Due  
  - Interactive and filter-controlled  

---

### 📄 Second Page: Invoices Analysis  
- **Filter Pane**: Same as summary  

- **Invoice Payments Details**:  
  - Each of the 3 invoice types visualized separately  

- **Approved Deductions**:  
  - Total value and pie chart breakdown  
  - Main categories: Retention, AD Payment, Social Insurance  
  - “Other Deductions” has tooltip with detailed breakdown  

- **Comparison Chart**:  
  - Submitted VS Approved per time period  

- **Variance Analysis**:  
  - Target VS Approved  
  - Target VS Submitted  
  - Submitted VS Target  
  - Percentages for each  

- **Trend Variance Over Time**:  
  - Dynamic line chart using field parameters  
  - Switches between 3 variance measures  
  - Zero-line reference with color indicators  

---

## 📌 Key Findings  
This solution is designed to provide **structure and visibility**, rather than produce specific findings. It can work with any invoice dataset and adapt according to predefined metrics and visual designs. The purpose is to streamline how commercial data is tracked and presented — turning static records into a live analytical experience.

---

## 💡 Conclusion  
The dashboard acts as a powerful reporting assistant for project commercial tracking. With dynamic filtering, automated flows, and layered visuals, it ensures accurate tracking across various invoice types and approval stages — empowering teams to focus on actions, not calculations.

---

## 🖼️ Dashboard Image  
![Alt text](https://github.com/Ahmed-Kazlak/Commercial-Data-Analysis-Solution/blob/main/1.png)

![Alt text](https://github.com/Ahmed-Kazlak/Commercial-Data-Analysis-Solution/blob/main/2.png)

