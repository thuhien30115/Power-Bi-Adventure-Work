#  adventure work

![alt](https://drive.google.com/file/d/1Qv75SIPtxQRtSCBTtNcfcjo9-Exp_mXM/view?usp=drive_link)

 ## Dashboard
 < img src="https://drive.google.com/file/d/1Qv75SIPtxQRtSCBTtNcfcjo9-Exp_mXM/view?usp=drive_link">
 ## Insight
**INSIGHT AND RECOMENDATION**
TRANG 1: OVERVIEW SALES DASHBOARD

- Lợi nhuận và số lượng sản phẩm bán ra tăng đều qua các năm ( 2011 - 2014). Nhưng doanh thu năm tháng 6/ 2014 đang có dấu hiệu giảm sâu
- Dễ nhận thấy **catergory bike** là những sản phẩm chiến lược chủ đạo, **doanh thu 95 triệu đô chiếm 86% toàn bộ doanh thu của công ty.  Đặc biệt là các dòng Mountain Bikes  và road bikes doanh thu chiếm đến 73% toàn doanh thu của công ty**. >> Có thể dùng 2 dòng sp trên làm sản phẩm chiến lược, mở rộng và phát triển thị trường. 
- Doanh thu đến chủ yếu từ các cửa hàng ở khu vực Bắc Mỹ và Châu âu
- Filter mốc thời gian các năm, nhận thấy năm **2012 mức lợi nhuận/doanh thu chỉ 3% nhưng tăng dần lên 8% ( năm 2013) và 17% năm 2014**. 
> Chúng ta có thể học được gì từ bài học này, có thể áp dụng gì vào thực tế không?
- Có những **điểm bất thường về dữ liệu trong tháng 6 năm 2014** ( **Doanh thu, số lượng, lợi nhuận giảm 1 cách đột ngột** ( mặc dù dữ liệu được ghi chép đến ngày 27/06/2014? . **Đặc biệt không có 1 chiếc xe đạp nào được bán ra**.  > nguyên nhân? cách khắc phục
- **TRANG 2**: dễ dàng nhận thấy đại đa số các đơn hàng đều được mua online. hình thức mua online mang lại doanh thu và lợi nhuận cao hơn ( xem hình 2)
- Riêng đối với **category bike mua ofline doanh thu đem về 66tr đô nhưng bị lỗ 3tr đô** - Ngược lại  **mua online** tuy chỉ có mức **doanh thu là 22tr đô nhưng lợi nhuận lại được 11tr đô ( chiếm > 50% lọi nhuận/doanh thu)** > triển khai các chương trình quảng cáo, khuyến mãi >> khiến các khách hàng mua online đối với dòng sản phẩm này ( filter category: bike để xem kết quả) 


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










									
									
									
									
									
									
