<img width="2500" height="1250" alt="AdventureWorks_Logo" src="https://github.com/user-attachments/assets/6580e3dd-3fba-42a3-90fe-0cfc160c4d9b" />

<h1 align="center">📊 Adventure Works Sales </h1>
<table>
<tr>
<td>

## Client Background

**Adventure Works** is a global manufacturing company producing cycling equipments and accessories. **Adventure Work's**  book of business is approaching 20,000 customers and possesses over 60,000 transactions, generating sales revenue exceeding $25 million. The available sales data spans various dimensions and metrics, including sales, products, sales by regions, and the company's loyalty program.

Reporting to the Head of Operations, an in-depth analysis was conducted to evaluate Adventure Work’s sales trend over the past several years (2020–2022). This comprehensive review provides valuable insights that internal cross-functional teams will utilize to streamline processes and enhance Adventure Works’s commercial performance. The key insights and recommendations focus on the following areas:
### Northstar Metrics

- **Sales trends - Focusing on key metrics of sales revenue, profit, number of orders placed and the return rates.**
- **Product performance - Analyzing different product lines, market impact and refund rates to inform strategic product decisions**
- **Regional results - Evaluating regional demand and product performance with regions to identify areas for improvement.**

</td>
</tr>
</table>

<h1 align="center">Executive Summary</h1>
<p align="center"> 
  <b>Sales revenue Analysis (2020-2022)</b> 
</p>
<p align="center">
<img width="1284" height="748" alt="image" src="https://github.com/user-attachments/assets/e9acc141-8573-411f-aa97-442ae7f69880" />




</p>
<table>
<tr>
<td width="50%" valign="top">

<b>1. Overall Revenue Trend</b>

- Revenue shows a clear upward long-term trend from 2020 to 2022.
- The trend line indicates that the business has been growing steadily over time, despite short-term fluctuations.

<br>

<b>2. Revenue Growth Acceleration in Late 2021</b>

- Revenue remained relatively stable during most of 2020 and the first half of 2021.
- Beginning around Q3 2021, revenue increased rapidly and maintained a higher level through much of 2022.
- The highest revenue appears in mid-to-late 2022, reaching approximately $0.45M–$0.47M.
- This represents the strongest sales performance during the observed period.

</td>

<td width="50%" valign="top">

<b>3. Key Insights </b>

- Revenue followed a strong upward trend from 2020–2022, indicating continuous business growth.
- Revenue growth accelerated significantly during the second half of 2021, achieving peak monthly sales of $0.45M.
- Revenue volatility increased as the business expanded, resulting in larger month-to-month fluctuations

<br> 

<b>4. Recommendations </b>

- Investigate the causes of the 2021 sales peak (e.g, market expedition, product diversification, customer behaviours.)
- Leverage high-performing periods focusing on top products and markets, refine customer profile to improve marketing and sales strategies.
- Reassess business strategy for 2023, focusing on pricing, promotions, and customer engagement for more stable business income.

</td>
</tr>
</table>
<h1 align="center">Dataset Structure and ERD (Entity relationship diagram)</h1>
The database structure as seen below consists of 8 tables: Sales Data, Customer Lookup, Territory Lookup, Calendar Lookup, Product Lookup, Product Categories Lookup, Product Subcategories Lookup, with a total of 56,086 sales records.
<img width="1046" height="770" alt="image" src="https://github.com/user-attachments/assets/613fee81-ad24-49d3-adf1-7e44a4a9a6ab" />
<h1 align="center">Insight Deep-Dive</h1>
<h2 align="center">Sales Trend</h2>
<img width="924" height="283" alt="image" src="https://github.com/user-attachments/assets/8644d1df-ebc5-4758-ab5f-55dce1f9707b" />
<img width="924" height="283" alt="image" src="https://github.com/user-attachments/assets/6b1d0c9b-7c18-4c09-9f40-a91ef9cc91bd" />
<table>
<tr>
<td>
  <b>Customer Segment Shift:</b>
  
  1. Initial Phrase (Jan 2020 - July 2020):
     The business served a <b>small but exceptionally high-value</b> customer base. While the total number of customers remained low (under 100), Revenue per Customer fluctuated heavily at a very high level, hovering around $3,000.
  2. Turning Point:
     In July 2020, there was a <b> noticeable drop in average order value/revenue per customer </b> down to around $2,000, hinting at an early shift toward a broader, lower-value market.
  3. The big Leap in 2021:
     In July 2021, the charts showed a clear structure change in the company's sales strategy:
     - Total Customers surged immediately from under 100 to roughly 300–400, continuing a steady climb to 400–500.
     - Concurrently, Revenue per Customer dropped sharply to a new stable range of $500 to under $1,000.
  
  <b>Trade-offs:</b>
  - Although Revenue per individual customer fell significantly from over $3000 per customer in 2020 down to around $500 per customer in 2022, the dramatic increase in customer volume successfully compensated for it, ensuring a steadily rising revenue for the company. 
- Following mid-2021 onward, both metrics (number of customers/revenue per customer) has achieved stability. This indicates that the new business model successfully found product-market fit and operated steadily through 2021 and 2022. Hence, explained the significant rise in revenue in 2021
</td>
</tr>
</table>
<h1 align="center">Product Performance</h1>
<p align='center'>
  <b>The line chart below shows the weekly revenue of each category during the observed period</b>
  
</p>
<img width="2500" height="1250" alt="image" src="https://github.com/user-attachments/assets/d6b783dd-1fc1-4d1a-ab38-cb33aad22d84" />
<table>
<tr>
<td>
  
  - Throughout the shown period from 2020 to 2022, Bikes has always been single-handedly drives the vast majority of the company's revenue, scaling aggressively from around $0.1M up to over $0.4M per week by 2022.

  - By July 2021, the company started gaining revenue from selling accessories and clothing. At the same time, the revenue from Bikes dramatically increased, this spike suggests a successful cross-selling or product portfolio expansion strategy launched around July 2021 to complement the core bike business.
</td>
</tr>
</table>

<h1 align="center">Market Segment</h1>
<img width="1386" height="729" alt="image" src="https://github.com/user-attachments/assets/dc8a97e1-23aa-4b2c-ad28-623eeb92feb1" />

<img width="1244" height="717" alt="image" src="https://github.com/user-attachments/assets/6ce51bef-01eb-4bed-95f0-f5fe0acc8e3f" />
<table>
<tr>
<td>
  
  - The United States and Australia regions contributes the most to sales revenue of AdventureWorks throughout 2020 to 2022, especially after the July 2021 product expedition.
- In 2022, the United States and Australia combines generated over $15M in revenue, about 60% of the total revenue of the company.
- In contrast, there have not been a significant revenue improvement in other regions, especially in Europe countries.
    
</td>
</tr>
</table>
<h2 align="center">Regional Customer Income Levels</h2>

<table align='center'>
  <tr>
    <td align="center" width="33%">
      <img alt="image" src="https://github.com/user-attachments/assets/910517ba-09a6-451e-93bb-eecfc29ea1d4" />
<br/>
      <sub><b>The United States</b></sub>
    </td>
    <td align="center" width="33%">
      <img width="282" height="312" alt="image" src="https://github.com/user-attachments/assets/43fd986b-3531-49a9-8642-2e27ad9e43a0" />
<br/>
      <sub><b>Australia</b></sub>
    </td>
    <td align="center" width="33%">
      <img width="282" height="312" alt="image" src="https://github.com/user-attachments/assets/198af991-e239-4584-a26b-5c1697bd771f" />
<br/>
      <sub><b>Canada</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img width="282" height="312" alt="image" src="https://github.com/user-attachments/assets/4fdcde01-3f9d-4c28-a754-c0340f7e0c4f" />
<br/>
      <sub><b>France</b></sub>
    </td>
    <td align="center">
      <img width="282" height="312" alt="image" src="https://github.com/user-attachments/assets/d97e37b9-a6ba-47b2-b69d-d5925f511797" />
<br/>
      <sub><b>Germany</b></sub>
    </td>
    <td align="center">
      <img width="282" height="312" alt="image" src="https://github.com/user-attachments/assets/66daba9a-2926-4ef6-af29-e906ee2ade34" />
<br/>
      <sub><b>United Kingdom</b></sub>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td>

- Customers in the United States, Canada and Australia have over 60% qualified as High-Income customers. Meanwhile, the majority of customers in Europe countries stays in the Low-Income level.
- The number of customer is also considerably lower in Europe countries compare to the United States, Australia or Canada.
- These evidences indicates that while the product expedition program has achieved successes in North America and Australia, these strategies does not appear to be effective in the Europe market.
    </td>
  </tr>
</table>
</table>
<h1 align='center'>
  Recommendations
</h1>
<h4>
  Based on the insights reviewed above, here are some recommendations that AdventureWorks can take away from our analysis.
  
</h4>
<h3>
  <b>Sales:</b>
</h3>
