Tên Dự Án: Test APIs

Ngày Kiểm Thử: 19/05/2025

Người Kiểm Thử: Vũ Viết Tuấn

GIỚI THIỆU

Postman là một ứng dụng mã nguồn mở giúp phát triển và kiểm thử API, cho phép người dùng tạo, chia sẻ và quản lý các yêu cầu API một cách dễ dàng. Nó hỗ trợ nhiều phương thức HTTP và cung cấp các công cụ hữu ích cho lập trình viên trong quá trình phát triển phần mềm.

Tổng Quan Về Postman

Khái Niệm: Postman là một công cụ được phát triển bởi Postdot Technologies, bắt đầu từ năm 2012, nhằm hỗ trợ việc kiểm thử API.

Phiên Bản: Hiện tại, Postman có ba phiên bản chính:

Postman (phiên bản miễn phí)
Postman Pro (ra mắt năm 2016)
Postman Enterprise (ra mắt năm 2017)
Ưu Điểm Của Postman

Dễ sử dụng với giao diện thân thiện.
Hỗ trợ cả chạy bằng giao diện người dùng (UI) và không có giao diện (non-UI).
Cho phép viết mã tự động hóa kiểm tra bằng JavaScript.
Hỗ trợ cả dịch vụ RESTful và SOAP.
Có chức năng tạo tài liệu API.
Nhược Điểm Của Postman

Các tính năng nâng cao chỉ có sẵn trong các phiên bản trả phí, như làm việc theo nhóm và hỗ trợ trực tiếp.
Cài Đặt Postman

Người dùng có thể tải Postman từ trang web chính thức: Postman Download.
Các Thành Phần Chính Của Postman

Settings:

Chứa thông tin cài đặt chung, bao gồm thông tin tài khoản và tùy chỉnh giao diện.
Cho phép nhập dữ liệu từ bên ngoài.
Collections:

Lưu trữ thông tin của các API theo thư mục hoặc theo thời gian.
API Content:

Hiển thị nội dung chi tiết của API và các phần hỗ trợ để thực hiện kiểm thử.
Các Thành Phần Chính Trong Kiểm Thử API

Environments: Chứa thông tin về các môi trường khác nhau như dev, staging và production, giúp dễ dàng chuyển đổi giữa các môi trường mà không cần thay đổi URL từng yêu cầu.

Request: Phần chứa thông tin chính của API, cho phép người dùng gửi yêu cầu đến server.

Response: Chứa thông tin trả về từ server sau khi gửi yêu cầu, giúp người dùng kiểm tra kết quả.

Postman là một công cụ mạnh mẽ cho việc phát triển và kiểm thử API, giúp tiết kiệm thời gian và nâng cao hiệu quả làm việc của lập trình viên.

1. Mục Tiêu Kiểm Thử: Sử dụng Postman để kiểm thử một API thực tế

2. Môi Trường Kiểm Thử: Postman.

3. Phương Pháp Kiểm Thử: Kiểm thử tự động và thủ công trên phần mềm Postman.

4. Kịch Bản Kiểm Thử:
   
Phương Thức HTTP (GET/POST/PUT/DELETE): GET

URL: https://jsonplaceholder.typicode.com/posts

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
![image](https://github.com/user-attachments/assets/9104d6b6-6f94-44e4-b146-d7c8bb22a4ad)


5. Kịch Bản Kiểm Thử:
   
Phương Thức HTTP (GET/POST/PUT/DELETE): POST

URL: https://jsonplaceholder.typicode.com/posts

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
![image](https://github.com/user-attachments/assets/9fb8c494-4b01-4e54-bd20-1f07faab3f65)



6. Kịch Bản Kiểm Thử:
   
Phương Thức HTTP (GET/POST/PUT/DELETE): PUT

URL: https://jsonplaceholder.typicode.com/posts/1

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
![image](https://github.com/user-attachments/assets/6cdabf6d-0e39-4be5-9a30-dd6654367e72)

7. Kịch Bản Kiểm Thử:
   
Phương Thức HTTP (GET/POST/PUT/DELETE): DELETE

URL: https://jsonplaceholder.typicode.com/posts/1

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
![image](https://github.com/user-attachments/assets/345b3063-578e-46a0-9b07-54c3bc153f8c)

8. Test
![image](https://github.com/user-attachments/assets/1271bdfa-3a73-437d-873b-77fa90dacfd5)
![image](https://github.com/user-attachments/assets/b7a48bbe-fd2d-4658-be0f-52db0e10323b)
![image](https://github.com/user-attachments/assets/412e2a67-1865-4675-8c01-3496217e50de)
![image](https://github.com/user-attachments/assets/b3675215-c4d0-48b3-b2f8-8053adf4cdf7)





   




