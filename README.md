# LTKHDL_2024
# Vietnamese Car Price Analysis
# 1. Mục tiêu dự án
Dự án này nhằm phân tích và khám phá dữ liệu về giá xe ô tô tại Việt Nam, giúp hiểu rõ các yếu tố ảnh hưởng đến giá cả của xe và cung cấp các phân tích liên quan đến giá trị, loại xe, thương hiệu, và tình trạng của xe.

Các câu hỏi nghiên cứu chính:
- Những yếu tố nào ảnh hưởng đến giá của xe ô tô tại Việt Nam?
- Thương hiệu nào có giá xe trung bình cao nhất?
- Mối quan hệ giữa tình trạng xe (mới/đã qua sử dụng) và giá xe là gì?
- Có sự phân bố giá xe khác nhau theo các loại xe (SUV, Sedan, Pickup, v.v.) không?
# 2. Tổng quan bộ dữ liệu
- Đây là bộ dữ liệu về mua bán xe cũ ở Việt Nam bắt đầu từ năm 2023. Dữ liệu bao gồm thông tin về giá cả, số kilomet đã chạy, thông tin về người bán bao gồm số điện thoại, tên , website bán (nếu có),...  
    - Dữ liệu được lưu trong file: `car_detail_en.csv`
    - Nguồn dữ liệu: [Vietnamese Car Price](https://www.kaggle.com/datasets/nguynthanhlun/vietnamese-car-price?select=seller_en.csv)
# 3. Các thư viện và công cụ sử dụng
- Pandas: Xử lý và phân tích dữ liệu.
- Matplotlib/Seaborn: Tạo các biểu đồ và trực quan hóa dữ liệu.
- Jupyter Notebook/Google Colab: Dùng để viết mã và chia sẻ báo cáo phân tích.
# 4. Các bước thực hiện
### 1. Thu thập dữ liệu
- Dữ liệu về giá xe ô tô tại Việt Nam được thu thập từ các nguồn website bán xe uy tín.

### 2. Làm sạch dữ liệu
- Xử lý các giá trị thiếu và không hợp lệ trong dữ liệu, bao gồm việc chuyển đổi các đơn vị (ví dụ: "Million" thành số thực).

### 3. Khám phá dữ liệu (EDA)
- Tính toán các chỉ số thống kê cơ bản: trung bình, độ lệch chuẩn, min, max.
- Vẽ biểu đồ phân phối giá của các loại xe.
- Phân tích mối quan hệ giữa các yếu tố như năm sản xuất, số km đã đi với giá xe.
### 4. Trực quan hóa kết quả
- Sử dụng biểu đồ cột, boxplot và scatter plot để trực quan hóa kết quả phân tích.
### 5. Kết luận và Đề xuất
- Dựa trên kết quả phân tích, đưa ra các kết luận về các yếu tố ảnh hưởng đến giá xe ô tô tại Việt Nam.
# Đóng góp
Nếu bạn có bất kỳ câu hỏi hoặc đề xuất nào, đừng ngần ngại đóng góp. 

Mọi đóng góp đều được hoan nghênh!
# Lời kết
Dự án này cung cấp một cái nhìn toàn diện về giá xe ô tô tại Việt Nam và các yếu tố ảnh hưởng đến giá trị của chúng. Thông qua phân tích dữ liệu, bạn sẽ có thể đưa ra các quyết định sáng suốt hơn trong việc mua bán xe hoặc nghiên cứu thị trường xe ô tô.

