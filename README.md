# Data-Collection-ETL-EDA--DataFlow26
1. Giới thiệu
Dự án này tập trung vào xây dựng bộ dữ liệu, làm sạch, và phân tích khám phá dữ liệu (Exploratory Data Analysis – EDA) nhằm hiểu rõ cấu trúc dữ liệu, phát hiện các xu hướng, mối quan hệ và vấn đề tiềm ẩn trước khi tiến hành các bước phân tích hoặc mô hình hóa tiếp theo.
Notebook chính của dự án: Xây dựng bộ dữ liệu + EDA.ipynb.
2. Mục tiêu
Thu thập và tổng hợp dữ liệu phục vụ nghiên cứu.
Làm sạch dữ liệu: xử lý giá trị thiếu, dữ liệu ngoại lai và sai lệch.
Phân tích thống kê mô tả các biến quan trọng.
Trực quan hóa dữ liệu để nhận diện xu hướng và mối quan hệ.
Đưa ra các nhận xét ban đầu làm cơ sở cho phân tích sâu hơn.
3. Cấu trúc dự án
├── Xây dựng bộ dữ liệu + EDA.ipynb  # Notebook chính
├── data/                            # Thư mục chứa dữ liệu thô 
├── Dashboard.pbi                    # Dashboard báo cáo chính
└── README.md                        # Tài liệu mô tả dự án
4. Công cụ và thư viện sử dụng
Python
Pandas: xử lý và phân tích dữ liệu
NumPy: tính toán số học
Matplotlib / Seaborn: trực quan hóa dữ liệu
Jupyter Notebook: môi trường thực hiện và trình bày phân tích
5. Nội dung chính trong Notebook
5.1. Xây dựng và chuẩn bị dữ liệu
Nạp dữ liệu từ nguồn ban đầu.
Chuẩn hóa tên biến và định dạng dữ liệu.
Kiểm tra và xử lý giá trị thiếu.
5.2. Phân tích khám phá dữ liệu (EDA)
Thống kê mô tả (mean, median, min, max, …).
Phân phối dữ liệu của các biến quan trọng.
Phân tích mối quan hệ giữa các biến bằng biểu đồ.
5.3. Nhận xét ban đầu
Các xu hướng nổi bật trong dữ liệu.
Những vấn đề tiềm ẩn cần lưu ý khi phân tích sâu hơn.
6. Cách sử dụng
Cài đặt các thư viện cần thiết:
pip install pandas numpy matplotlib seaborn jupyter
Mở Jupyter Notebook:
jupyter notebook
Chạy file Xây dựng bộ dữ liệu + EDA.ipynb theo thứ tự các cell.
7. Ghi chú
Kết quả EDA mang tính khám phá và mô tả, chưa phải kết luận cuối cùng.
Các nhận định rút ra từ biểu đồ và thống kê cần được kiểm chứng thêm ở các bước phân tích tiếp theo.
