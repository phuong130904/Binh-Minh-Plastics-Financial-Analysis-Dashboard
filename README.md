# Dashboard Phân Tích Tài Chính Công Ty Cổ Phần Nhựa Bình Minh

## Tổng quan dự án

Dự án xây dựng hệ thống Dashboard hỗ trợ phân tích báo cáo tài chính cho Công ty Cổ phần Nhựa Bình Minh (BMP) bằng Microsoft Power BI.

Thay vì trình bày dữ liệu tài chính dưới dạng các báo cáo tĩnh, Dashboard được thiết kế theo hướng Business Intelligence và Data Storytelling, giúp người dùng theo dõi sức khỏe tài chính doanh nghiệp, đánh giá chất lượng tăng trưởng và hỗ trợ ra quyết định dựa trên dữ liệu.

Dự án sử dụng dữ liệu báo cáo tài chính theo quý của BMP trong giai đoạn 2021–2025.

## Bài toán kinh doanh

Một doanh nghiệp có thể tăng trưởng doanh thu nhưng chưa chắc tăng trưởng đó bền vững.

Dự án được xây dựng nhằm trả lời câu hỏi:

**"Nhựa Bình Minh có đang duy trì tăng trưởng bền vững và sở hữu nền tảng tài chính lành mạnh hay không?"**

Để trả lời câu hỏi này, Dashboard được triển khai theo 5 góc nhìn tài chính khác nhau:

1. Tăng trưởng và hiệu quả tài chính
2. Hiệu quả vận hành và sinh lời
3. An toàn tài chính và thanh khoản
4. Dòng tiền và khả năng tạo tiền
5. Giá trị cổ đông và định giá

## Nguồn dữ liệu

* Báo cáo kết quả kinh doanh
* Bảng cân đối kế toán
* Báo cáo lưu chuyển tiền tệ

Dữ liệu được thu thập từ nền tảng CafeF.

Quy mô dữ liệu:

* 20 quý
* Giai đoạn 2021–2025
* Hơn 50 chỉ tiêu tài chính

## Quy trình thực hiện

### 1. Thu thập dữ liệu

* Thu thập dữ liệu báo cáo tài chính theo quý
* Chuẩn hóa cấu trúc dữ liệu
* Tổng hợp dữ liệu từ nhiều báo cáo tài chính

### 2. Xử lý dữ liệu

Sử dụng Power Query để:

* Làm sạch dữ liệu
* Chuẩn hóa định dạng
* Xử lý giá trị thiếu
* Chuyển đổi dữ liệu phục vụ phân tích

### 3. Mô hình dữ liệu

Thiết kế mô hình dữ liệu theo kiến trúc Galaxy Schema nhằm tối ưu hiệu năng truy vấn và khả năng mở rộng Dashboard.

### 4. Xây dựng KPI

Phát triển hơn 50 DAX Measures phục vụ các nhóm KPI:

* Tăng trưởng doanh thu
* Tăng trưởng lợi nhuận
* Biên lợi nhuận
* ROA
* ROE
* Thanh khoản
* Đòn bẩy tài chính
* Dòng tiền
* EPS
* BVPS
* P/E

### 5. Trực quan hóa dữ liệu

Triển khai Dashboard tương tác với:

* Navigation Menu
* Dynamic Filters
* Drill-down Analysis
* KPI Indicators
* Data Storytelling

## Cấu trúc Dashboard

### Trang 1. Tăng trưởng và Hiệu quả tài chính

**Câu hỏi:**
Doanh nghiệp có thực sự tăng trưởng và tăng trưởng đó có bền vững hay không?

**Insight chính:**
Lợi nhuận tăng nhanh hơn doanh thu nhờ cải thiện hiệu quả hoạt động và kiểm soát chi phí.

### Trang 2. Hiệu quả vận hành và Sinh lời

**Câu hỏi:**
Tăng trưởng đến từ mở rộng doanh thu hay nâng cao hiệu quả vận hành?

**Insight chính:**
Khả năng sinh lời và hiệu quả sử dụng tài sản được cải thiện rõ rệt qua các năm.

### Trang 3. An toàn tài chính và Thanh khoản

**Câu hỏi:**
Doanh nghiệp có duy trì nền tảng tài chính an toàn hay không?

**Insight chính:**
Tỷ lệ nợ thấp, thanh khoản cao và mức độ phụ thuộc vốn vay thấp.

### Trang 4. Dòng tiền và Khả năng tạo tiền

**Câu hỏi:**
Lợi nhuận có được hỗ trợ bởi dòng tiền thực tế hay không?

**Insight chính:**
Khả năng chuyển đổi lợi nhuận thành dòng tiền được cải thiện theo thời gian.

### Trang 5. Giá trị cổ đông và Định giá

**Câu hỏi:**
Doanh nghiệp đã tạo ra giá trị gì cho cổ đông?

**Insight chính:**
EPS, BVPS và cổ tức tăng trưởng tích cực, phản ánh giá trị cổ đông được cải thiện.

## Kết quả nổi bật

* Lợi nhuận sau thuế tăng mạnh trong giai đoạn 2021–2025.
* Biên lợi nhuận gộp và biên lợi nhuận ròng được cải thiện.
* ROA và ROE duy trì ở mức cao.
* Tỷ lệ nợ thấp và thanh khoản ổn định.
* Dòng tiền kinh doanh tăng trưởng tích cực.
* Giá trị cổ đông gia tăng thông qua EPS, BVPS và cổ tức.

## Công nghệ sử dụng

* Microsoft Power BI
* Power Query
* DAX
* Data Modeling
* Business Intelligence
* Financial Analysis

## Kỹ năng thể hiện trong dự án

* Data Cleaning
* Data Modeling
* DAX Development
* Financial Analysis
* KPI Design
* Dashboard Design
* Data Visualization
* Business Storytelling
* Business Intelligence
