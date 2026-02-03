# Data-Collection-ETL-EDA--DataFlow26
Đây là project **xây dựng bộ dữ liệu và phân tích khám phá dữ liệu (EDA)** phục vụ cho bài toán **phân tích hành vi học tập và kết quả học tập của sinh viên**.

Mục tiêu chính của project là **hiểu dữ liệu**, **phát hiện xu hướng – rủi ro**, và **đưa ra các nhận định định hướng** trước khi bước sang giai đoạn feature engineering hoặc xây dựng mô hình machine learning.

Notebook chính của project: `Xây dựng bộ dữ liệu + EDA.ipynb` và `Dashboard.pbix`

## Mục tiêu
- Tổng hợp và chuẩn hóa dữ liệu học tập của sinh viên
- Phân tích thống kê mô tả các biến quan trọng
- Trực quan hóa mối quan hệ giữa các yếu tố học tập
- Đưa ra các nhận xét, giả thuyết ban đầu cho bước modeling

## Phạm vi dữ liệu
Dữ liệu sử dụng trong project bao gồm các nhóm thông tin chính:
- Thông tin đầu vào (điểm chuẩn, điểm trúng tuyển, phương thức xét tuyển)
- Thông tin học tập (năm học, học kỳ, số tín chỉ đăng ký)
- Kết quả học tập (số tín chỉ hoàn thành, CPA, trạng thái pass/fail)

## Các bước chính trong xây dựng bộ dữ liệu

### Bước 0: Tổng quan dữ liệu
- Kiểm tra kích thước dataset
- Kiểm tra kiểu dữ liệu các cột
- Xác định các biến số và biến phân loại

## Bước 1: Chuẩn hóa học kỳ để sắp xếp thời gian
## Bước 2: Gộp data để tính lịch sử + xây dựng đặc trưng cho bộ dữ liệu
## Bước 3: Ghép thông tin tuyển sinh
## Bước 4: Chia tập dữ liệu
## Bước 5: Lựa chọn đặc trưng đưa vào mô hình và lưu kết quả


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


