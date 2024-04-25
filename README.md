# Case-Study

**Phase 1:**

Hello Good Friend, Hope you are doing fine.
Please read the below situation and come up with cost efficient and suitable solution.

1.An Amazon seller enterprise operates in various countries, including those in the EU and
North America. Initially, operations ran smoothly until the manager realized the time-consuming nature of managing numerous sections within Amazon Seller Central. The Data usually involves the product, sales numbers, orders and inventory details.The platform's limitations in data extraction hindered efficient analysis. Consequently, the manager proposed relocating this data to an external storage for future analysis and batch analysis as well. 

In addition to analysis, the manager extracts numerous files from seperate sources and combine the for analysis on a weekly and monthly basis. To prepare the files and to streamline this process, automation is required, along with the separate storage of all data. What existing tools could facilitate these tasks? How will you automate the above process, kindly attach the justification for the selection of this tool. 

2.Propose a Database Design :  


**Order Table**
| Field Name             | Description              |
|------------------------|--------------------------|
| order_id               | ID of the order          |
| marketplace_id         | ID of the marketplace    |
| order_status           | Status of the order      |
| purchase_order_number  | Purchase order number    |
| purchase_date          | Date of purchase         |
| is_business_order      | Indicates business order |



**Payment Table**
| Field Name       | Description          |
|------------------|----------------------|
| payment_id       | Payment ID           |
| order_id         | ID of the order      |
| payment_method   | Method of payment    |
| payment_amount   | Amount of payment    |
| payment_currency | Currency code        |


**Fulfillment_Order Table**    
| Field Name             | Description                |
|------------------------|----------------------------|
| seller_fulfillment_id  | Seller fulfillment ID      |
| shipping_charge_value  | Shipping charge value      |
| order_id               | ID of the order            |
| marketplace_id         | ID of the marketplace      |
| currency_code          | Currency code              |
| received_date          | Date order was received    |


**Finance_Order Table**
| Field Name         | Description                  |
|--------------------|------------------------------|
| finance_order_id   | Finance order ID             |
| seller_sku         | Seller SKU                   |
| posted_date        | Date order was posted        |
| marketplace_id     | ID of the marketplace        |
| profit_per_product | Profit per product           |
| quantity           | Quantity ordered             |
| received_date      | Date order was received      |



What would be the logical schema you would design from the above tables. You can use any  convenient tool to design the schema, please provide the link or attach the image for easy viewing. 
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


**Data Analysis Extravaganza: A Worldwide Sales and Orders Odyssey**

**Mission Briefing:**
Prepare yourself for an exhilarating dive into the ocean of data as we embark on a grand adventure to analyze sales and orders data from nooks and crannies around the globe. Your tools? API calls sharper than a double-edged sword and Excel files thicker than a mystery novel!

**Quests to Conquer:**

**Phase 2:**
API Shenanigans:

Your Targets:

Orders API: Master the ancient scrolls of the [Orders API v0 Reference](https://developer-docs.amazon.com/sp-api/docs/orders-api-v0-reference) to summon order details from the digital ether.

Sales API: Channel the arcane powers of the [Sales API v1 Reference](https://developer-docs.amazon.com/sp-api/docs/sales-api-v1-reference) to reveal the mysteries of sales data.

**Stealth Mode:** Engage in covert operations to make API calls. Remember, the keys to the kingdom (API keys, that is) must remain unseen by prying eyes across different realms (regions).

Though you only have to come up the code for authenticating and calling an API!

**Phase 3:**

Treasure Hunt (Data Retrieval and Setup):
**Maps** - [Google Drive Maps Folder](https://drive.google.com/drive/folders/1X9nCy4mvgAXjzvpqCzQw28S5FQS7IEuO?usp=sharing)

Download treasure maps (XLS files) leading to the rich lands of Germany, Spain, France, the United Kingdom, and the United States.
Each map is filled with cryptic symbols and numbers representing sales lore (columns like Date/Time, Order ID, SKU, and more).

Data Alchemy (Cleaning and Preprocessing):
Transmute chaotic date formats into a single, golden standard.
Banish the dark spirits of null values and duplicate entries with your powerful data-cleansing spells.

Epic Saga of Analysis (Data Analysis and Reporting):
Combine all treasure maps into one legendary artifact (a single comprehensive file).
Determine which kingdom (country) hoards the most gold (sales) and identify the mightiest region within that kingdom.
Travel through time with comparisons of months and years to uncover patterns of wealth and woe.
Investigate the curious case of disappearing gold (refunds). Are some treasures cursed (higher refunds for certain products)?


Expected Bounty:

A treasure chest (consolidated dataset) brimming with polished data jewels ready for analysis.
A scroll (report) detailing your heroic deeds with charts as colorful as a bard's tales, comparing the riches across different lands and eras.
Wise insights into the enigmatic patterns of refunds, complete with sage advice on enhancing the market's offerings and customer joy.
Dive into this quest with the vigor of a knight, the precision of an archer, and the wisdom of a wizard. May your data points always be accurate, and your graphs never be pie-lies!
