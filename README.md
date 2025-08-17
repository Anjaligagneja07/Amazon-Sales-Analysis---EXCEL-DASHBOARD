
<h1 align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Amazon_logo.svg" width="90"/> SALES ANALYSIS DASHBOARD </h1>

Welcome to the **Amazon Sales Dashboard**! This project is a comprehensive data visualization and analysis solution built using **Microsoft Excel**. It presents actionable insights from raw sales data collected from Amazon transactions (Walmart source sheet), focusing on **sales trends, profit margins, category performance**, and more.

---

## 🎯 Project Overview
The goal of this project is to:
- Transform raw Amazon (Walmart sheet) sales data into a **comprehensive Excel dashboard**.
- Provide stakeholders with **key performance insights** including:
  - 📊 Sales & Profit trends
  - 🛒 Product Category performance
  - 🌍 Geography-wise breakdown
  - 📦 Quantity analysis
- Enable **decision-making** through a **dynamic, interactive dashboard**.

---

## 📊 Dataset Description
- 📂**Source:** Amazon Raw Sales Data (`Amazon 2_Raw.xlsx`)
- 📄**Sheet Used:** `Walmart`
- 📈**Size:** 10 columns × 3,200 + records  

🧩**Key Columns:**
- `Order ID` → Unique identifier for each order  
- `Order Date` & `Ship Date` → Timeline tracking  
- `EmailID` → Customer identifier  
- `Geography` → Country, City, and State  
- `Category` → Product category (Phones, Labels, Binders, etc.)  
- `Product Name` → Item purchased
- `Sales` → Revenue Generated
- `Quantity` → Units Sold
- `Profit` → Net Profit from the transaction

---

## 🧹 Preprocessing & Data Cleaning Steps
✔️ Removed **duplicates** (repeated order entries).  
✔️ Handled **missing values** in `Profit` and `Sales`.  
✔️ Extracted **Country, State, and City** from `Geography`.  
✔️ Standardized **date formats** for `Order Date` & `Ship Date`.  
✔️ Converted all numerical columns (`Sales`, `Quantity`, `Profit`) to proper numeric formats.

---

## 📊 Key Statistical Analysis Performed
- 📈 **Descriptive Statistics**: Mean, Median, Mode of Sales & Profit  
- 📊 **Category Contribution**: Share of each product category in total revenue  
- 🌍 **Geographical Sales Distribution**: Country, State & city-level contribution  
- ⏱️ **Shipping Time Analysis**: Impact of order-to-ship lead time on sales  
- 🏆 **Top & Bottom Products**: High-revenue vs. loss-making items

---

## 🛠️ Tools & Technologies Used
| Tool / Tech         | Purpose |
|----------------------|---------|
| 📊Microsoft Excel      | Main dashboard & visualization |
| 📑Pivot Tables         | Aggregation & summary metrics |
| 🔄Power Query          | Data cleaning & preprocessing |
| 📈Excel Charts         | Visual storytelling |
| ⏳Slicers & Timelines  | Interactivity |
| 🎨Conditional Formatting | Highlighting KPIs & trends |

---

## 📸 Dashboard Preview
<img width="1295" height="803" alt="Screenshot 2025-08-17 211555" src="https://github.com/user-attachments/assets/f768ef1c-b1ef-426c-bf01-f184118ad995" />

---

## 💡 Insights from the Dashboard
- 🏆 **California** emerged as the top-performing state by sales.  
- 💼 **Binders & Phones** drove the highest revenue.  
- 📉 **Labels** had the lowest profit margins → potential inventory issue.  
- ⏳ Average **shipping time** = 2–5 days.  
- 🔥 Top 10 products contributed **>40% of total sales**. 

---

## ⚙️ How It Works
1. 📥 Load the **raw dataset (`Amazon 2_Raw.xlsx`)** into Excel.  
2. 🧹 Preprocessing and cleaning done using **Power Query**.  
3. 📊 Use **Pivot Tables** and **Charts** to generate insights.  
4. 🎨 Apply **slicers & conditional formatting** for interactivity.  
5. 🖥️ Final Dashboard enables dynamic filtering by:
   - Date  
   - Geography  
   - Product Category

---

## 🎥 Demo Video
Watch the Demo Video here : [Amazon Sales Analysis Demo](https://drive.google.com/file/d/16kgWYh-kpR8h52WYrYUtIfT1X3w_pQXj/view?usp=sharing)

---

## 🛠️ Setup
Clone this repository:

git clone https://github.com/yourusername/Amazon-Sales-Dashboard.git

---

## 🤝 Contribution
We welcome contributions to enhance this dashboard! 🚀

Steps to contribute:

1. Fork the repo

2. Create a feature branch (git checkout -b feature/new-insight)

3. Commit changes (git commit -m "Added new KPI chart")

4. Push to branch (git push origin feature/new-insight)

5. Submit a Pull Request✅

---

## 🪪 License
This project is licensed under the MIT License.

---

## 👩‍💻 About Me
👋 Hi, I'm Anjali Gagneja. Passionate about uncovering insights through data and real world business insights.

🔗 **Let's Connect:**
- GitHub : https://github.com/Anjaligagneja07
- LinkedIN :[Anjali Gagneja](https://www.linkedin.com/in/anjali-gagneja-a35239297/)

---

## 🌟 Show Your Support
If you like this project, don't forget to ⭐ star the repo and share your feedback!
