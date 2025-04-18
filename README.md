# Project Background
FreshMart, a U.S.-based retail and e-commerce company founded in 2012, specialises in consumer goods like wines, meats, fruits, snacks and premium products. FreshMart operates through physical stores and an online platform. With rising competition and marketing costs, the company initiated a data-driven project to identify high-value customer segments and top product categories driving revenue. 

Insights and recommendations are provided on the following key areas:

- **Category 1:** Customer Segmentation
- **Category 2:** Product Category Performance
- **Category 3:** Spending Patterns by Demographics

# Executive Summary

### Overview Of Findings
Using demographic and product purchasing behaviour data, I identified key customer segments, product category performance and revenue drivers. My key findings include:
- Married customers aged 35-54 with graduate-level education generate the highest revenue, contributing approximately $129,000 in revenue.
- Wines are the highest performing product category, generating $680,000, which accounts for about 50% of total revenue.
- Meat products follow, contributing $373,000, which is about 28% of total revenue.
- Customers **under 35** exhibit more diversified spending across all product categories, while **55+** tend to concentrate on a few key categories.



   # Insights Deep Dive
  ### Category 1: Customer Segmentation
- Married customers aged 35-54 with graduate-level education are the highest-spending customer segment, contributing approximately **$129,000** in revenue. This segment has the highest lifetime value and demonstrates brand loyalty. Their high spending likely reflects financial stability and family household needs.
- Married customers aged 55+ with graduate-level education follow very closely behind with **$125,000** in revenue. This segment is retired or possibly approaching retirement and spends steadily, possibly out of habit and trust.
- Customers aged 55+ with graduate-level education who are together(possibly cohabiting) are our third top spenders with **$100,000** in revenue. This segment resembles married households with shared expenses and financial security, which means high purchasing power.
- Our top key spenders are all customers with graduate-level education. Education level seems to correlate with spending power
 
    ![Dashboard 1](https://github.com/user-attachments/assets/e8a91182-6b69-4ec8-ad19-c16fb966ca4b)

    ### Category 2: Product Category Performance
- The top-performing product category is Wines at **$680,000** in revenue, making up **50%** of total revenue. Wines dominate customer spending, indicating strong product loyalty and customer preference.
- Meat is the second highest revenue driver at **$373,000** in revenue, making up **28%** of total revenue, indicating consistent demand and essential and regular purchases.
- Gold is the third highest revenue driver at **$98,000** despite being a non-essential product. This suggests an overlooked and lucrative product with high potential.
  

  ![Sheet 1 product category and revenue](https://github.com/user-attachments/assets/cd386d49-c445-447e-a5a9-ee3c37f6d115)

### Category 3: Spending Patterns by Demographics
- **Age Group:** Customers aged **55+** are the highest spenders across all product categories, with a total spend of **$727,000** contributing more significantly than other age groups. This group consists of retirees or people approaching retirement, and this suggests a mature and financially secure customer base likely driven by consistent and familiar buying habits and a higher purchasing power.
- **Education:** Graduate-level customers are the top spenders in this category at **$698,000**. This category has a significantly higher average spend than other education levels.
- **Marital Status:** Married customers are the top spenders in this category at **$510,000** likely due to more disposable income and buying for larger households.

  ![Dashboard 1 spending patterns](https://github.com/user-attachments/assets/6070c423-497e-410b-a99d-3c8a8b64cabf)

  # Recommendations:
  
  Based on the insights and findings above, I would recommend that the marketing team consider the following:
  
 - Target high-value segments like married customers aged **35-54, 55+ with graduate education** by developing personalised campaigns and possibly loyalty programs tailored according to their preferences.
 - Maximise revenue from the top performing product categories by allocating more marketing spend to promote **Wines and Meat**, which make up **50% and 28%** of total revenue, respectively. We can also leverage bundle deals and cross-selling in these categories.
 - Position **Gold** products more noticeably in advertising as they rank third in product performance, and so there is potential for it to drive more sales. We can emphasise quality and exclusivity to appeal to our high-spending demographics.
 - Capitalise on Age and Marital status-based spending patterns by focusing on married customers and 55+ customers by using messaging that aligns with their needs and lifestyle, perhaps emphasising premium, family-centric, health-conscious products.

   # Assumptions and Caveats
   Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are listed below:
 - In the education column, the value "2n cycle" was assumed to be equivalent to "Masters" and was replaced to maintain uniformity.
 - In the marital status column, non-standard entries such as "Alone", "YOLO" and "Absurd" were interpreted as being indicative of a single status and recrded as "Single".
 - In the income column, missing values were imputed using the mean income, and this may have reduced the accuracy of income-based segmentation, which is why it was excluded from core demographic analysis.
 - Three rows in the age column contained irregular age entries, and this was replaced with the average age to prevent distortion in age-based analysis. 





