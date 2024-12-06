# Dự Đoán Nguy Cơ Mắc Bệnh Tiểu Đường Sử Dụng Học Máy

## 1. Mục Tiêu  
Mục tiêu của đề tài là khai thác dữ liệu để dự đoán nguy cơ mắc bệnh tiểu đường ở người, cụ thể:  
- Đánh giá các mô hình dự đoán để xác định các yếu tố quan trọng ảnh hưởng đến nguy cơ mắc bệnh.  
- Thu thập, làm sạch và chuẩn hóa dữ liệu nhằm đảm bảo tính chính xác và phù hợp cho phân tích.  
- Áp dụng các thuật toán khai phá dữ liệu và học máy để phát hiện xu hướng và mối liên hệ, đặc biệt với các yếu tố như: tuổi, huyết áp, tiền sử bệnh, lượng mỡ trong máu.  

### Kết quả mong đợi  
- Dự đoán chính xác khả năng mắc bệnh tiểu đường, góp phần phát hiện sớm.  
- Hỗ trợ nâng cao hiệu quả phòng ngừa, quản lý bệnh và cải thiện sức khỏe cộng đồng.  

---

## 2. Quy Trình Ứng Dụng Học Máy  

### 2.1 Chọn Tập Dữ Liệu  
Lựa chọn tập dữ liệu phù hợp, đáng tin cậy cho bài toán dự đoán.  

### 2.2 Tải Dữ Liệu  
Tải dữ liệu từ nguồn đã chọn vào hệ thống để xử lý.  

### 2.3 Tiền Xử Lý Dữ Liệu  
Các bước xử lý dữ liệu thô:  
- **Kiểm tra giá trị khuyết (Null Values):** Loại bỏ hoặc xử lý dữ liệu thiếu.  
- **Phát hiện và xử lý ngoại lệ (Outliers):** Loại bỏ giá trị bất thường.  
- **Chuẩn hóa dữ liệu (Standardization):** Đưa dữ liệu về dạng tiêu chuẩn.  
- **Xóa bản sao (Remove Duplicates):** Loại bỏ các mục trùng lặp.  

### 2.4 Lựa Chọn Mô Hình  
Tiến hành thử nghiệm các mô hình học máy, bao gồm:  
- Logistic Regression  
- Decision Tree  
- Random Forest  

### 2.5 Chia Dữ Liệu  
Tách dữ liệu thành hai tập:  
- **Tập huấn luyện (Training Set):** Dùng để huấn luyện mô hình.  
- **Tập kiểm tra (Test Set):** Dùng để đánh giá mô hình.  

### 2.6 Xây Dựng Mô Hình  
Huấn luyện mô hình với tập huấn luyện và điều chỉnh để đạt hiệu suất tốt nhất.  

### 2.7 Đánh Giá Mô Hình  
Đo lường hiệu quả mô hình qua các chỉ số:  
- **Confusion Matrix:** Ma trận lỗi.  
- **Accuracy:** Độ chính xác tổng thể.  
- **Precision:** Độ chính xác khi dự đoán đúng.  
- **Recall:** Khả năng phát hiện đúng các trường hợp thực tế.  
- **ROC/AUC:** Hiệu suất tổng quát của mô hình.  

### 2.8 Kết Luận  
Dựa trên kết quả đánh giá, rút ra kết luận:  
- Tính khả thi của mô hình trong thực tế.  
- Đề xuất cải tiến hoặc áp dụng các biện pháp phòng ngừa, hỗ trợ quản lý bệnh.  
