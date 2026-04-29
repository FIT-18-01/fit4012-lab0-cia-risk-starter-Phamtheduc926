# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** PHẠM THẾ ĐỨC

**MSSV:** 1871020147

**Lớp/Nhóm:** 18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1:Hồ sơ sinh viên 
- Asset 2:Tài khoản người dùng
- Asset 3 (nếu có):Database hệ thống 

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A ->Availability
- Sự cố B ->Integrity
- Sự cố C ->Confidentiality

---

## 3. Phân tích sự cố B
- Threat:  Mối đe dọa từ nội bộ
- Vulnerability:Thiếu phân quyền rõ ràng
-               Không có cơ chế kiểm tra/chấp thuận thay đổi dữ liệu
- Mitigation:Áp dụng role-based access control (RBAC)
-            Ghi log toàn bộ thay đổi
-            Áp dụng xác thực 2 bước khi chỉnh sửa điểm
-            Thiết lập quy trình kiểm duyệt (approval workflow)

---

## 4. Reflection
Nếu là quản trị viên, em sẽ ưu tiên xử lý sự cố B (Integrity) trước.
Dữ liệu điểm bị thay đổi sai là thiệt hại trực tiếp và khó phát hiện nếu không có log,
đồng thời ảnh hưởng nghiêm trọng đến quyền lợi sinh viên và uy tín nhà trường.
Sự cố A (Availability) tuy gây khó chịu nhưng thường tạm thời và dễ khắc phục hơn.
Sự cố C (Confidentiality) cũng nghiêm trọng nhưng dữ liệu đã lộ thì khó thu hồi,
trong khi B có thể ngăn chặn và phục hồi nếu có cơ chế log và backup tốt.
---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

FIT4012{A-A-B-I-C-C}

