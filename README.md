# Hoat dong 2
## Yêu cầu
Chép trong đề

## Dữ liệu sử dụng
Bộ dữ liệu về covid data thu thập từ tất cả các nước.

Tập dữ liệu gồm có 67 thuộc tính: **(Có thể xoá trước vài thuộc tính, chừa lại tầm 10 thuộc tính thôi)**
1. iso_code
2. continent
3. location
4. date
5. total_cases
6. new_cases
7. new_cases_smoothed
8. total_deaths
9. new_deaths
10. new_deaths_smoothed
11. total_cases_per_million
12. new_cases_per_million
13. new_cases_smoothed_per_million
14. total_deaths_per_million
15. new_deaths_per_million
16. new_deaths_smoothed_per_million
17. reproduction_rate
18. icu_patients
19. icu_patients_per_million
20. hosp_patients
21. hosp_patients_per_million
22. weekly_icu_admissions
23. weekly_icu_admissions_per_million
24. weekly_hosp_admissions
25. weekly_hosp_admissions_per_million
26. total_tests
27. new_tests
28. total_tests_per_thousand
29. new_tests_per_thousand
30. new_tests_smoothed
31. new_tests_smoothed_per_thousand
32. positive_rate
33. tests_per_case
34. tests_units
35. total_vaccinations
36. people_vaccinated
37. people_fully_vaccinated
38. total_boosters
39. new_vaccinations
40. new_vaccinations_smoothed
41. total_vaccinations_per_hundred
42. people_vaccinated_per_hundred
43. people_fully_vaccinated_per_hundred
44. total_boosters_per_hundred
45. new_vaccinations_smoothed_per_million
46. new_people_vaccinated_smoothed
47. new_people_vaccinated_smoothed_per_hundred
48. stringency_index
49. population_density
50. median_age
51. aged_65_older
52. aged_70_older
53. gdp_per_capita
54. extreme_poverty
55. cardiovasc_death_rate
56. diabetes_prevalence
57. female_smokers
58. male_smokers
59. handwashing_facilities
60. hospital_beds_per_thousand
61. life_expectancy
62. human_development_index
63. population
64. excess_mortality_cumulative_absolute
65. excess_mortality_cumulative
66. excess_mortality
67. excess_mortality_cumulative_per_million

## Mục tiêu 
Xây dựng một mô hình hồi quy tuyến tính bội có thể ước lượng được số ca tử vong mới dựa trên các thông số khác.

Cụ thể, các biến dự đoán là: **(Cần chọn ra 6 biến hợp lý nhất)**
1. 
2. 
3. 
4. 
5. 
6. 

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

## Thống kê đa biến
Tính ma trận hiệp phương sai (matrix 7x7)

Dựng đồ thị mô tả sự tương quan giữa các biến

# Xây dựng mô hình hồi quy bội
## Định nghĩa và ký hiệu cho mô hình

## Ước lượng tham số
Tính ra các hệ số của mô hình

## Ước lượng độ lệch chuẩn của sai số

## Xác định hệ số R^2 hiệu chỉnh

## Xác định khoảng tin cậy của các hệ số hồi quy

## Kiểm định đường hồi quy và các hệ số hồi quy

## Xác định khoảng tin cậy của giá trị trung bình của Y khi x=x_0

## Xác định khoảng tin cậy của các giá trị dự đoán

## Kiểm định sự phù hợp của mô hình hồi quy tuyến tính