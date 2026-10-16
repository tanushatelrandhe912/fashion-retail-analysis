Fashion Trends Analysis
Fashion Trends Analysis is a data analysis project focused on understanding fashion product trends, pricing, discounts, brands, categories, product types, and gender-based preferences. The project uses a fashion retail dataset to identify patterns that can help understand customer preferences and support better pricing and discount strategies .The analysis considers factors such as Original Price, Discount Price, Discount Percentage, Brand, Category, Gender, Product Type, Price Segment, and Discount Tier.
Objectives
The main objectives of this project are:
•	Identify the product categories and brands with the highest representation.
•	Analyze the effect of discounts on products and customer buying patterns.
•	Understand gender-wise and category-wise product preferences.
•	Analyze products across Budget, Mid, Premium, and Luxury price segments.
•	Evaluate pricing and discount strategies using data-driven analysis.
Dataset
The dataset contains information about fashion products. Important fields include:
•	Brand – Product brand
•	Product_ID – Unique product identifier
•	Product_Name / ProductName – Product name/type
•	Original_Price – Price before discount
•	Discount_Price – Price after discount
•	Discount_Percentage – Percentage discount offered
•	Discounted_amount – Amount reduced from the original price
•	Gender – Men, Women, Kids, or Unisex
•	Category – Product category
•	Price_Segment – Budget, Mid, Premium, or Luxury
•	Discount_Tier – No Discount, Light, Moderate, or Heavy
 Analysis Performed
1. Data Preparation
•	Checked for missing values using isnull().sum().
•	Renamed columns where required for consistency.
•	Converted price and discount-related columns into appropriate numeric formats.
2. Exploratory Data Analysis (EDA)
•	Studied the distribution of numerical variables.
•	Examined frequency distributions of categorical variables such as Product Category, Product Type, and Brand.
•	Identified potential outliers in price and discount values.
3. Brand & Category Analysis
•	Identified brands having the largest number of products.
•	Analyzed dominant product categories.
•	Compared categories across different price segments.
4. Product Type & Gender Analysis
•	Studied common product types such as T-shirts, Jeans, Sarees, and Shoes.
•	Compared product types across genders.
•	Identified popular product types within different categories.
5. Discount & Price Analysis
•	Compared products across different discount tiers.
•	Calculated average discount percentages by product type.
•	Analyzed discounts across categories.
•	Studied the relationship between product price and discount using visual analysis.
 Visualization Techniques
The project uses different visualization techniques to understand the dataset effectively:
•	Histograms – Numerical distributions
•	Bar Charts – Brand, category, and gender comparisons
•	Boxplots – Outlier detection
•	Scatter Plot – Price vs. discount relationship
•	Stacked Bar Charts – Discount distribution across categories
•	Heatmaps – Brand and price-segment comparison
Tools & Techniques
Python | Jupyter Notebook | Pandas | Matplotlib | Seaborn | Exploratory Data Analysis | Data Cleaning | Data Wrangling | Data Visualization
Key Learning Outcomes
Through this project, I gained practical experience in data cleaning, data preparation, exploratory data analysis, categorical and numerical analysis, grouping and aggregation, outlier identification, and data visualization. I also learned how to analyze fashion retail data from multiple perspectives, including brand, category, gender, discount, product type, and price segment.
Conclusion
The Fashion Trends Analysis project demonstrates how data analysis can be used to understand product trends, pricing patterns, discount strategies, and customer-oriented preferences in the fashion retail domain. The analysis provides a structured approach for extracting meaningful insights from raw fashion product data and supporting data-driven business decisions.
