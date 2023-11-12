#  adventure work
## Model structure
The model has seven tables:
|Table|Description|
|-----|-------|
|**Customer**|Describes customers and their geographic location. Customers purchase products online (Internet sales).|
|**Date**|There are three relationships between the **Date** and **Sales** tables, for order date, ship date, and due date. The order date relationship is active. The company's reports sales using a fiscal year that commences on July 1 of each year. The table is marked as a date table using the **Date** column.|
|**Product**|Stores finished products only.|
|**Reseller**|Describes resellers and their geographic location. Reseller on sell products to their customers.|
|**Sales**|Stores rows at sales order line grain. All financial values are in US dollars (USD). The earliest order date is July 1, 2017, and the latest order date is June 15, 2020.|
|**Sales Order**|Describes sales order and order line numbers, and also the sales channel, which is either **Reseller** or **Internet**. This table has a one-to-one relationship with the **Sales** table.|
|**Sales Territory**|Sales territories are organized into groups (North America, Europe, and Pacific), countries, and regions. Only the United States sells products at the region level.|

The model doesn't contain any DAX calculations.
## INSIGHT
<img src="C:\Users\Admin\Documents\GitHub\ADVENTURE WORKS.pdf">

									
									
									
									
									
									
