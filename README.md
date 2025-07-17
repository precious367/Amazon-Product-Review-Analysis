## DSA Capstone Project
### Topic: Amazon Product Review Analysis

This project explores an Amazon product review dataset to uncover key insights on pricing, discount strategies, customer ratings, and product performance across categories by analysing product and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement.

### Company Overview
RetailTech Insights is a company that provides
e-commerce analytics solutions to sellers on platforms like Amazon.

### Dataset Description:
- Product details: name, category, price, discount, and ratings
- Customer engagement: user reviews, titles, and content
- Each row represents a unique product, with aggregated reviewer data
  stored as comma-separated values
- Total Records: 1,465 rows 
- TotalFields: 16 columns

 ### Tools Used
 - Ms Excel (for Data Analysis cleaning)
 - For data collection
 - For data cleaning
 - Pivot Table and chart (for analysis and Dashboard Visualization)

### Data cleaning and preparation
- Data Loading and inspection
- Handling missing variable
- Data cleaning and formating
- Data filtering
- Removing duplicates values

### Data Manipulation 
The Category column was split using a delimiter to enhance clarity and support more granular analysis.

### New Calculated Columns Created
1. Average Discount Percentage = (Actual Price - Discounted Price) / Actual Price * 100
2. Potential Revenue = Actual Price * Rating Count
3. Discount range bucket (≥50%) = IF(Discount % >= 50, "Yes", "No")
4. Price Range Bucket = IF(Discounted Price <= 500, "₹200–₹500", ">₹500")
5. Discount Range Percentage
= IF([@Discount%]<=10, "0–10%", 
  IF([@Discount%]<=20, "11–20%", 
  IF([@Discount%]<=30, "21–30%", ...)))
5. Product Review  = IF(Rating Count < 1000, "Fewer than 1000", "Greater than")
- These calculated columns played a vital role in deriving actionable insights

  ### Conclusion on Retail Tech Product Review Insight
  The dashboard gives a clear overview of how pricing, discounts, customer reviews, and product performance vary across categories.

   ### My Key Insights:
- Electronics, Home & Kitchen, and Computers & Accessories lead in terms of product availability, pricing range, and customer engagement.
- There’s a noticeable positive link between discounts and sales, showing that discounting is an effective way to drive purchases.
- Most customer ratings are favorable, averaging between 3.8 and 4.5, and the top-rated categories also tend to have better overall performance.
- Interestingly, even with high discounts, some product categories still retain high average prices, which speaks to the value perception and brand strength of those products.

  ### My Recommendations:
1. Apply Bigger Discounts on Low-Performing Products, Use more aggressive discounting (50% and above) for products that aren't doing well, to boost interest and sales.
2.  Use Moderate Discounts for Best-Sellers or high-performing categories, maintain discounts in the 20–40% range to keep the perceived value strong while still driving sales.
3. Focus More on High-Rated Categories, allocate more resources and promotions to categories with high ratings and lots of reviews—especially Electronics and Computers & Accessories—since these already show strong customer satisfaction.
4. Improve Low-Rated Product Areas and Take a closer look at categories like Health & Personal Care and Car Accessories, where ratings or engagement are low. This could mean there's room to improve product quality or customer experience.
5. Boost Customer Review Efforts, Actively encourage more customer reviews, especially in categories that are underrepresented.
This could be through simple follow-up emails or small incentives, which would help collect more data and support better business decisions.

### Data Analysis ( Files Included)
  - view project here [Excel workbook]

 
 ### Author
PRECIOUS OJUGBELI

Feel free to explore, suggest improvements, or fork this project!

