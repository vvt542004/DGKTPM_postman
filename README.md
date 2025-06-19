Tên Dự Án: Test APIs

Ngày Kiểm Thử: 19/05/2025

Người Kiểm Thử: Vũ Viết Tuấn

GIỚI THIỆU

🧩 Postman là gì?
Postman là một công cụ giao diện đồ họa (GUI) phổ biến giúp lập trình viên và tester làm việc với API (Application Programming Interface) một cách dễ dàng. Nó hỗ trợ gửi các yêu cầu HTTP và nhận phản hồi từ server, từ đó giúp bạn kiểm thử API, mô phỏng API, và tự động hóa kiểm thử.

🔧 Postman dùng để làm gì?
Gửi yêu cầu HTTP:
Gửi các loại yêu cầu như:

GET – Lấy dữ liệu

POST – Gửi dữ liệu mới

PUT – Cập nhật dữ liệu

DELETE – Xoá dữ liệu

Xem phản hồi từ server:
Bao gồm:

Mã trạng thái (200, 404, 500…)

Header

Body (dạng JSON, HTML, XML…)

Viết kiểm thử tự động:
Dùng JavaScript để viết test script trong tab Tests, nhằm kiểm tra:

Mã trạng thái

Nội dung JSON

Định dạng, thời gian phản hồi

Tổ chức các yêu cầu thành Collection:
Giúp quản lý các nhóm API của một dự án lớn và chia sẻ với nhóm khác.

Chạy kiểm thử tự động hàng loạt (Collection Runner)
Có thể chạy nhiều API liên tục và báo cáo kết quả test.

Mô phỏng server bằng Mock Server
Mô phỏng phản hồi từ API khi backend chưa sẵn sàng.

Tích hợp CI/CD và xuất báo cáo test
Dùng kết hợp với Newman để chạy Postman script trong pipeline.

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





   




