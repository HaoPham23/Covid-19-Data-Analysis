# HOẠT ĐỘNG 2
## Yêu cầu
Chép trong đề

## Dữ liệu sử dụng [Hào, XONG]
Bộ dữ liệu về Covid-19 thu thập ở USA.

Tập dữ liệu gồm có 14 thuộc tính:
1. **location**: Tên đất nước (USA)
2. **date**: Ngày thu thập dữ liệu
3. **new_deaths**: số ca tử vong mới trong ngày
4. **total_deaths**: tổng số ca tử vong
5. **new_cases**: số ca mắc mới trong ngày
6. **total_cases**: tổng số ca mắc
7. **new_tests**: số ca xét nghiệm mới trong ngày
8. **total_tests**: tổng số ca xét nghiệm
9. **positive_rate**: tỉ lệ dương tính
10. **people_fully_vaccinated**: tổng số người đã tiêm vaccine đầy đủ (2 mũi trở lên)
11. **icu_patients**: số lượng bệnh nhân đang trong giai đoạn hồi sức tích cực trong ngày
12. **hosp_patients**: số lượng bệnh nhân đang nhập viện trong ngày
13. **reproduction_rate**: tỉ lệ lây nhiễm 
14. **population**: dân số

## Mục tiêu [Hào, XONG]
Xây dựng một mô hình hồi quy tuyến tính bội có thể ước lượng được số ca tử vong mới dựa trên các thông số khác.

Cụ thể, các biến dự đoán là: **(Cần chọn ra 6 biến hợp lý nhất)**

1. **new_cases**
2. **new_tests**
3. **icu_patients**
4. **hosp_patients**
5. **people_fully_vaccinated**
6. **positive_rate**

Biến được ước lượng: **new_deaths**
## Đọc dữ liệu
(Hiển thị bảng dữ liệu gốc)

## Làm sạch dữ liệu (Data cleaning)
### Trích xuất các dữ liệu chính
(Chỉ giữ lại các cột cần thiết, bao gồm 6 cột của biến dự đoán và cột biến ước lượng)
### Xử lý dữ liệu khuyết (NA)
(Kiểm tra các dữ liệu NA, thay bằng 0 hoặc giá trị khác)

## Làm rõ dữ liệu 
## Chuyển đổi biến (Data transformation)
Chuyển qua logarithm hoặc các dạng khác nếu cần.
## Thống kê mô tả
### Thống kê đơn biến
Thực hiện các phương pháp thống kê đơn biến lên từng biến dự đoán, 1 vài phương pháp: Summary Statistics, Frequency Distribution Table, Bar chart, Histogram... 

### Thống kê đa biến
Tính ma trận hiệp phương sai (matrix 7x7)

Dựng đồ thị mô tả sự tương quan giữa các biến

# Xây dựng mô hình hồi quy bội
## Định nghĩa và ký hiệu cho mô hình

## Ước lượng tham số
Tính ra các hệ số của mô hình

## Ước lượng độ lệch chuẩn của sai số

## Xác định hệ số $R^2$ hiệu chỉnh

## Xác định khoảng tin cậy của các hệ số hồi quy

## Kiểm định đường hồi quy và các hệ số hồi quy

## Xác định khoảng tin cậy của giá trị trung bình của $Y$ khi $x=x_0$

## Xác định khoảng tin cậy của các giá trị dự đoán

## Kiểm định sự phù hợp của mô hình hồi quy tuyến tính