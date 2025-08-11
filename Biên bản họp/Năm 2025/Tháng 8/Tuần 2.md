# Biên bản họp giao ban - Công ty FoxAI
**Tuần ... - Tuần 2 tháng 8 - Từ ngày 11/08**

<img src="https://fox.ai.vn/wp-content/uploads/2024/07/Logo_Original-1.png" alt="Hình ảnh" width="30%" />

## 1. Thời gian
Thời gian định kỳ: 9h sáng hàng tuần

## 2. Tiến độ dự án triển khai
Kết quả:
- Tổng hợp kết quả từ bộ phận quản lý để báo cáo tiến độ dự án
- Những vướng mắc, khó khăn cần công ty hỗ trợ
- Với những dự án mà kinh doanh chuyển về, bộ phận nào sẽ tiếp quản tiếp, bố trí nhân sự làm gì để triển khai được tiếp theo.

## 3. Tiến độ R&D và kinh doanh AI
- Với những dự án mà kinh doanh chuyển về, bộ phận nào sẽ tiếp quản tiếp, bố trí nhân sự làm gì để triển khai được tiếp theo: Dự án đào tạo chính quyền xã thông minh (đang xây dựng tài liệu đào tạo), dự án ABS (đang làm lại bản demo), dự án Huetronics (đang chờ ký hợp đồng), dự án Parcific Airline (đã gửi email kế hoạch khảo sát)...
- Tiến độ làm POC: nhân sự hiện tại, ai đang làm gì. Dự án SHB (đã xây dựng POC và gửi cho KH), Vietinbank Lào (đã xong giao diện web, OCR, đang thi công tính năng chụp ảnh-chân dung, tuần này sẽ demo), TLTL (đã xây dựng tờ trình, tuần này sẽ làm demo).
- Kế hoạch triển khai dự án tiếp theo: Ví dụ LaoVietBank cần bao nhiêu người online, offline để thực hiện
- **Chú ý:** Phân biệt giữa quản lý (thống kê, hậu kiểm) và vận hành (có quy trình theo dõi & kết nối hàng ngày) 

## 4. Tình hình tài chính của từng trung tâm
- Doanh thu, chi phí theo từng dự án.

## 5. Quy trình phát triển sản phẩm
- Sau khi Dev hoàn thiện lập trình, bộ phận BA tạo ra các Testcase gửi cho QA test trên `môi trường Dev`.
- QA test xong thì chuyển giao cho team triển khai test các testcase đó trên `môi trường UAT` để tránh lỗi thiếu thư viện. Đồng thời triển khai học luôn phần mềm để có kiến thức để triển khai.
- Xong rồi thì mới chuyển sang cho khách hàng sử dụng trên `môi trường Production`.


**Lưu ý:** Testcase cần xây theo khung từng service trong microservice: IAM service, Config service, ...



