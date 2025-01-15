# 📊 Power BI Dashboard: Dynamic Market Analysis for Computer Hardware Sales Across India

## Challenge 🚀
The company specializes in selling computer hardware products throughout India and is experiencing dynamic market growth. However, the Sales Director is concerned about gaining a clear and objective understanding of the business landscape. There is a pressing need for a detailed overview of key aspects, including **products**, **customers**, and regional **markets** (North, South, Central). This Power BI dashboard aims to address these concerns by providing actionable insights and facilitating data-driven decision-making.

## Project Steps 🔍

1. **Data Preparation 📊**
   - Imported raw data from Excel into SQL, organizing it into key tables: **Customers**, **Products**, **Markets**, and **Transactions**.
   - Preprocessed the data to ensure quality and consistency, including:
     - Date filtering for relevant time frames 📅.
     - Establishing relationships between tables for comprehensive analysis 🔗.
     - Handling missing values ❌ and conducting feature engineering to enhance the dataset.

2. **Data Implementation in Power BI 💻**
   - Implemented the preprocessed data into Power BI.
   - Defined essential metrics, particularly within the **Transactions** table, calculating key performance indicators such as **Revenue** 💰 and **Profit** 📈.
   - Created a **Date Table** 📅 to support time-based analysis.
   - Established a **Star Schema** ⭐ model, with **Transactions** at the center for optimized querying.

3. **Dashboard Creation 🎨**
   - **Sales Overview Page**:
     - Developed visualizations for profit distribution by market 🌍.
     - Created a timeline with a drill-down feature from years to months using a hierarchical structure 📊.
     - Implemented bookmarks for quick access to insights on the best and worst products and customers regarding profit 📑.
     - Added slicers for filtering by product types 🔍.
       
![Sales Overview](https://github.com/user-attachments/assets/e0733b70-7f99-41c8-8ac0-ce7474f6e47d)
   - **Customer Details Page**:
     - Designed as a drill-through page accessible from any customer in the Sales Overview 🔄.
     - Included various slicers and complex visualizations focusing on **Profit Margin** 💵 and **Total Revenue** 📈.
     - Highlighted the most profitable and popular products for each customer 🌟.
       
![Customer Details](https://github.com/user-attachments/assets/e71f2ff8-7ee7-45b4-9ad3-bdf4789348f5)
   - **Product Details Page**:
     - Created a dedicated page for detailed insights into individual products 🛍️.
     - Enabled drill-through capabilities to view metrics such as **Unit Price** 💲, **Units Sold** over time 📅, **Total Profit** 💰, and **Number of Transactions** 🔢.
       
![Product Details](https://github.com/user-attachments/assets/48e4e7fa-be55-4f24-bb3c-ff0d775782d2)

4. **Final Touches and Insights 🔍**
   - Conducted thorough testing of all visualizations and interactions ✅.
   - Ensured a user-friendly experience by optimizing layout and navigation throughout the dashboard 🧭.

## Conclusion 🎉
This Power BI dashboard provides a comprehensive analysis of the company’s sales data, empowering the Sales Director with actionable insights to make informed decisions. By leveraging data visualizations and interactivity, the dashboard facilitates a deeper understanding of market dynamics, product performance, and customer behavior. Future enhancements could include predictive analytics and advanced customer segmentation to further refine marketing strategies and optimize inventory management.

#### 📫 Contact 
<div style="text-align: center;">
  <a href="mailto:lauren.gallegoropero@gmail.com" style="display: inline-block; margin-right: 30px;">
    <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse2.mm.bing.net%2Fth%3Fid%3DOIP.GPb0ZcxnKxbRAXHa3xNw3QHaHa%26pid%3DApi&f=1&ipt=4371e1e26750a70ea8a1e846e34d3c3685b4199092807f925c8fd83820b0224c&ipo=images" alt="Email" width="30">
  </a>
  <a href="https://www.linkedin.com/in/lauren-gallego-ropero/" target="_blank" style="display: inline-block;">
    <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ffreelogopng.com%2Fimages%2Fall_img%2F1656996524linkedin-app-icon.png&f=1&nofb=1&ipt=7c10c25f586f2064f67e02e144040429a2b1c65c2aae6c39e1fa8076f98060fc&ipo=images" width="30" alt="LinkedIn Profile">
  </a>
</div>
