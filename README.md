# 🚀 Fabric End-to-End Project Automation

![Project Architecture](./architecture_baraa.png)

This repo holds resource for automating the entire process of replicating [Data with Baraa’s](https://www.youtube.com/@DataWithBaraa) end-to-end data engineering project in **Microsoft Fabric** — from raw data ingestion all the way to report creation — in under **5 minutes**.

---

## ⚙️ What It Does

When you run the [automation notebook](./Automation_Notebook.ipynb), it automatically:

- Creates a **Lakehouse**  
- Downloads and loads the **raw dataset**  
- Transforms data and saves it as **silver layer tables**  
- Creates a **Warehouse**  
- Builds a **star schema model** using T-SQL  
- Creates a **Direct Lake semantic model**  
- And generates a **report** connected to that model  

All without manual setup.

---

## 🧭 How to Use

1. Get a [Microsoft Fabric free trial](https://www.microsoft.com/en-us/microsoft-fabric/getting-started).   
2. Create a new workspace in your Fabric environment.  
3. Import this notebook into the workspace.  
4. Run all cells — the automation will handle the rest.

In a few minutes, you’ll have:
- A **Lakehouse** with raw datasets  
- A **Python notebook** that transforms the data into silver tables  
- A **Warehouse** and **star schema**  
- A **Direct Lake model** and ready-to-use **report**

---

## 💡 Inspiration

This automation was inspired by:

- [Greg Beaumont](https://www.linkedin.com/in/gregbeaumont/) and [Inderjit Rana](https://www.linkedin.com/in/singhinderjit/)’s [Healthcare Fabric Automation](https://github.com/isinghrana/fabric-samples-healthcare/tree/main/analytics-bi-directlake-starschema) project  
- Data with Baraa’s original [end-to-end Data warehouse project](https://www.youtube.com/watch?v=9GVqKuTVANE&t=13229s)
- To follow along on how i built it on fabric, read this [blog post](https://www.linkedin.com/pulse/eating-data-breakfast-designing-building-warehouse-abdulmaleek--jjn0f/?trackingId=fIvDAq2jTz%2B%2BHYvcu%2BZ5ww%3D%3D)

---

## 🧱 Next Steps

Future versions of this notebook will extend the automation to include more Fabric capabilities  

---

### 🙌 Acknowledgements

Special thanks to [Will Needham](https://www.linkedin.com/in/willneedham/)'s **Fabric Dojo** community for helping me learn more about Fabric automation.

---
