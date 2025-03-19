
![Image](https://github.com/user-attachments/assets/b9710db4-28ad-49eb-a6db-7c9c40f7d5e3)
## **Project Overview**
As a passionate football fan and someone who absolutely loves the sport, I wanted to create a project that merges my love for football with my skills in data engineering and analytics. This project aims to build an **ETL (Extract, Transform, Load)** data pipeline that automates the process of collecting data from a **RESTful API**, processing it with **Python**, storing it in **Microsoft SQL Server**, and visualizing insights using **Power BI**. The goal is to efficiently manage data extraction, transformation, and visualization for decision-making.

## **Project Workflow**

### **1. Extract:**

- Connect to a RESTful API to retrieve **JSON** formatted data.
- Handle API authentication, pagination, and rate limits if applicable.
  
  **API source**: [API-Football](https://www.api-football.com/)

### **2. Transform:**

- Process raw JSON data using **Python** (`pandas`, `json`, `numpy`).
- Clean and normalize the data, handle missing values, and apply necessary transformations.

### **3. Load:**

- Store transformed data in a **Microsoft SQL Server** database.
- Use Python’s **pyodbc** for database connection and data insertion.

### **4. Visualize:**

- Connect **Power BI** to SQL Server.
- Create interactive dashboards and reports to extract meaningful insights.

## **La Liga Top 20 Players Dashboard**

- [View the La Liga Top 20 Players Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNGQwYzRlM2QtMzZmOC00MGYzLWI0NzAtZmMyZDY0NTE3MTE5IiwidCI6ImNiNDg0NDZlLTkwZTYtNGJmMS04MjViLTQwZTQ4ZmNjOWZmNiJ9)
