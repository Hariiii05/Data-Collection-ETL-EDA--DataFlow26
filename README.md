# Data-Collection-ETL-EDA--DataFlow26
# Xây dựng bộ dữ liệu và EDA

Đây là project **xây dựng bộ dữ liệu và phân tích khám phá dữ liệu (EDA)** phục vụ cho bài toán **phân tích hành vi học tập và kết quả học tập của sinh viên**.

Mục tiêu chính của project là **hiểu dữ liệu**, **phát hiện xu hướng – rủi ro**, và **đưa ra các nhận định định hướng** trước khi bước sang giai đoạn feature engineering hoặc xây dựng mô hình machine learning.

Notebook chính của project: `Xây dựng bộ dữ liệu + EDA.ipynb` và `Dashboard.pbix`

---

## Mục tiêu
- Tổng hợp và chuẩn hóa dữ liệu học tập của sinh viên
- Phân tích thống kê mô tả các biến quan trọng
- Trực quan hóa mối quan hệ giữa các yếu tố học tập
- Đưa ra các nhận xét, giả thuyết ban đầu cho bước modeling

---

## Phạm vi dữ liệu
Dữ liệu sử dụng trong project bao gồm các nhóm thông tin chính:
- Thông tin đầu vào (điểm chuẩn, điểm trúng tuyển, phương thức xét tuyển)
- Thông tin học tập (năm học, học kỳ, số tín chỉ đăng ký)
- Kết quả học tập (số tín chỉ hoàn thành, CPA, trạng thái pass/fail)

---

## Các bước chính trong EDA

### Bước 0: Tổng quan dữ liệu
- Kiểm tra kích thước dataset
- Kiểm tra kiểu dữ liệu các cột
- Xác định các biến số và biến phân loại

---

### Bước 1: Kiểm tra và xử lý dữ liệu thiếu
- Thống kê tỷ lệ missing value theo từng biến
- Phân biệt missing mang tính logic (ví dụ: sinh viên năm 1 chưa có CPA)
- Ghi nhận các biến cần xử lý ở bước preprocessing sau

---

### Bước 2: Phân tích thống kê mô tả
- Giá trị trung bình, trung vị, min, max
- Phân phối số tín chỉ đăng ký và hoàn thành
- Phân phối CPA và tỷ lệ pass

---

### Bước 3: Phân tích mối quan hệ giữa các biến
- Mối quan hệ giữa số tín chỉ đăng ký và tỷ lệ hoàn thành
- Ảnh hưởng của CPA tới kết quả học tập
- So sánh kết quả học tập theo:
  - Năm học
  - Phương thức xét tuyển
  - Độ lệch điểm đầu vào

---

### Bước 4: Trực quan hóa dữ liệu
- Histogram phân phối
- Boxplot phát hiện ngoại lai
- Line chart thể hiện xu hướng theo học kỳ / số tín chỉ

---

### Bước 5: Nhận xét và kết luận EDA
- Xác định các ngưỡng rủi ro học tập
- Nhận diện nhóm sinh viên dễ không hoàn thành tín chỉ
- Đề xuất các feature tiềm năng cho mô hình ML

---

## Công cụ và thư viện sử dụng
Yêu cầu Python >= 3.8 và các thư viện sau:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## Kết quả đạt được
- Hiểu rõ cấu trúc và chất lượng dữ liệu
- Phát hiện các xu hướng quan trọng ảnh hưởng tới kết quả học tập
- Đặt nền tảng vững chắc cho bước **preprocessing & feature engineering**

---

## Ghi chú
- Kết quả EDA mang tính **khám phá**, không phải kết luận nhân quả
- Các nhận định cần được kiểm chứng ở bước modeling

---

Sẵn sàng cho giai đoạn **tiền xử lý dữ liệu và huấn luyện mô hình ML**


