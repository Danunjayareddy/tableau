# Task 1: Connect Data Sources to Tableau

## i) Supported Data Sources  
| Source Type      | Examples                        |  
|------------------|--------------------------------|  
| Text Files       | .CSV, .TXT                     |  
| Excel Files      | .XLS, .XLSX                    |  
| Access Database  | .MDB, .ACCDB                   |  
| SQL Server       | Microsoft SQL Server (live/extract) |  

---

## ii) Steps to Connect  
1. Open Tableau Desktop  
2. From the **Connect Pane**:  
   - Select **Excel** → Import Excel workbooks  
   - Select **Text File** → Import `.csv` or `.txt`  
   - Select **Access** → Connect `.mdb` or `.accdb`  
   - Select **Microsoft SQL Server** → Provide server name, credentials, database  
3. Tableau loads data into **Data Source Tab** for preview.  

---

## iii) Dimensions & Measures  
- **Dimensions** → Categorical fields (e.g., Region, Date, Category)  
- **Measures** → Numerical fields (e.g., Sales, Profit)  
- Tableau:  
  - Blue = Dimensions (Discrete)  
  - Green = Measures (Continuous)  

---

## iv) Changing Data Types  
1. Go to **Data Pane**  
2. Right-click a field → **Change Data Type**  
3. Options: String, Number, Date, Boolean  

---

## v) Applying Filters  
- **From Data Pane**: Drag fields to **Filters Shelf**  
- **From Worksheet**: Right-click → Filter  
- Add filter controls in dashboards for interactivity.  

---

## vi) Merging Multiple Data Sources  
- **Join (within one source)** → Drag tables & define join key (Inner/Left/Right/Full).  
- **Data Blending (across sources)** → Link fields from two sources (primary & secondary).  
