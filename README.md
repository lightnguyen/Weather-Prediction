# Đồ án Machine Learning: Dự báo thời tiết

Đây là đồ án cuối kỳ cho môn học Máy học, tập trung vào việc ứng dụng các thuật toán phân loại để giải quyết bài toán dự báo thời tiết dựa trên các dữ liệu lịch sử.

## 📝 Tổng quan

Dự án này thực hiện một quy trình hoàn chỉnh của một bài toán khoa học dữ liệu, bao gồm các bước:
* Phân tích và trực quan hóa dữ liệu để tìm ra các đặc điểm nổi bật.
* Tiền xử lý dữ liệu để chuẩn bị cho việc huấn luyện mô hình.
* Xây dựng và huấn luyện ba mô hình Machine Learning khác nhau.
* Đánh giá và so sánh hiệu suất của các mô hình.

Điểm đặc biệt của dự án là các thuật toán cốt lõi được lập trình thủ công để thể hiện sự am hiểu sâu sắc về cơ sở toán học, thay vì chỉ sử dụng các hàm cấp cao có sẵn.

## 📊 Dữ liệu

Dự án sử dụng tập dữ liệu **Seattle Weather** (`seattle-weather.csv`), chứa thông tin thời tiết hàng ngày tại Seattle.
* **Các đặc trưng (Features):** `precipitation`, `temp_max`, `temp_min`, `wind`.
* **Biến mục tiêu (Target):** `weather` (bao gồm 5 lớp: `sun`, `rain`, `drizzle`, `snow`, `fog`).

## 🤖 Các mô hình được triển khai

Ba mô hình phân loại đã được xây dựng và huấn luyện:
1.  **Hồi quy Softmax (Softmax Regression)**
2.  **K-Nearest Neighbors - (KNN)**
3.  **Cây quyết định (Decision Tree)**


Cảm ơn bạn đã ghé thăm repository này!
