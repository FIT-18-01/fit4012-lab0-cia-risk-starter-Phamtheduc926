# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** PHẠM THẾ ĐỨC

**MSSV:** 1871020147

**Lớp/Nhóm:** 18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1:tài khoản khách hàng 
- Asset 2:Học bạn và điểm số
- Asset 3 (nếu có):tài khoản ngân hàng 

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A ->A
- Sự cố B ->I
- Sự cố C ->C

---

## 3. Phân tích sự cố B
- Threat:  Nhân viên quản trị
- Vulnerability:Không có cơ chế kiểm tra dữ liệu đầu vào
		        Thiếu phân quyền hoặc quy trình kiểm duyệt
- Mitigation:Detective Control
		     Log toàn bộ lịch sử chỉnh sửa
		     Cho phép kiểm tra và phát hiện thay đổi bất thường
		     Áp dụng xác nhận 2 bước khi chỉnh sửa điểm số

---

## 4. Reflection
Viết 5-7 dòng.
Qua bài lab, em hiểu rõ hơn về mô hình bảo mật CIA gồm Confidentiality, 
Integrity và Availability trong hệ thống thông tin. Với hệ thống lưu điểm sinh viên, 
tính bảo mật giúp tránh lộ thông tin cá nhân và điểm số; 
tính toàn vẹn đảm bảo dữ liệu không bị sai lệch do lỗi hoặc tấn công; 
còn tính sẵn sàng giúp hệ thống hoạt động ổn định để sinh viên truy cập khi cần. 
Việc phân tích threat, vulnerability và mitigation cũng giúp nhận diện rủi ro và đề xuất biện pháp bảo vệ phù hợp.
---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em:FIT4012{A-A-B-I-C-C}

