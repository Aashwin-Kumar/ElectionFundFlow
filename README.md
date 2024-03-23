**Description:**
This dataset presents detailed information on electoral bond transactions facilitated by the State Bank of India (SBI). Electoral bonds are financial instruments that allow individuals and organizations to make anonymous donations to political parties in India. The dataset contains essential details such as the purchaser's name, the type of donor (business, individual, or trust), and other relevant information.

Additionally, exploratory data analysis (EDA) has been performed on this dataset using Jupyter Notebook. Insights and patterns regarding electoral funding dynamics, donor characteristics, and transparency measures have been extracted to enhance the understanding of political financing in India.

**Columns:**
1. **Purchaser Name:** Name of the entity purchasing the electoral bonds.
2. **Denomination:** Name of the individual or organization making the donation.
3. **Type:** A new column added to segregate donors into two categories: "Individual" and "Firm" (representing businesses, companies, trusts, etc.).
4. **Date of Encashment:** The date when the electoral bonds were encashed.
5. **Name of the Political Party:** The political party receiving the donation.
6. **Denomination:** The face value or denomination of the electoral bonds.

**Conclusion:**

1. **Bond Buyer Analysis:**
   - The dataset comprises transactions from 1314 unique bond buyers.
   - Buyers are categorized into six types, with the majority being firms (938), followed by individuals (365).
   - The most common amount of bonds purchased varies across buyer types, with firms leading with an average purchase of ₹123,321,425.
   - Notably, FUTURE GAMING AND HOTEL SERVICES PRIVATE LIMITED stands out with a substantial purchase of ₹13,680,000,000.
   - LAKSHMI NIWAS MITTAL emerges as the top individual buyer, with a purchase of ₹350,000,000.
   - Electoral bonds purchased by individuals or entities containing 'AGARWAL' in their name total ₹179,082,000.

2. **Encashment Data Analysis:**
   - A total of 27 unique political parties are listed in the dataset.
   - BHARTIYA JANTA PARTY received the highest total donations, amounting to a staggering ₹60,605,110,000.
   - May 10, 2019, witnessed the most encashments, totaling ₹4,116,500,000.
   - On this date, BHARTIYA JANTA PARTY recorded the highest encashments, amounting to ₹3,961,500,000.

These findings underscore the significant financial transactions facilitated by electoral bonds, emphasizing the role of both buyers and political parties in the electoral funding landscape.

**Note:** The dataset has been enhanced by adding a new column "Type" to facilitate easier analysis and segmentation of donors into individual and firm categories.
---
Feel free to adjust or expand upon this description based on your specific dataset and objectives!
