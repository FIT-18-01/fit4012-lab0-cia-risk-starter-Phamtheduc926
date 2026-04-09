# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính

**Assets:**
- Dữ liệu điểm số của sinh viên (điểm quá trình, điểm thi, điểm tổng kết).
- Tài khoản người dùng (sinh viên, giảng viên), bao gồm thông tin đăng nhập và quyền truy cập.

**CIA mapping:**
- Sự cố A → Confidentiality  
  Ví dụ: sinh viên có thể xem điểm của người khác khi chưa được cho phép.

- Sự cố B → Integrity  
  Ví dụ: điểm số bị thay đổi sai do lỗi hệ thống hoặc truy cập trái phép.

- Sự cố C → Availability  
  Ví dụ: hệ thống lưu điểm bị gián đoạn khi sinh viên cần truy cập để xem kết quả.

**Phân tích sự cố B:**
- **Threat:** Insider hoặc người không có quyền truy cập cố ý hoặc vô tình làm thay đổi dữ liệu điểm.
- **Vulnerability:** Phân quyền truy cập chưa chặt chẽ, thiếu cơ chế kiểm tra và ghi log khi chỉnh sửa dữ liệu.
- **Mitigation:** Áp dụng phân quyền theo vai trò (RBAC), sử dụng xác thực mạnh (2FA), và ghi log toàn bộ thay đổi để phát hiện và khôi phục khi cần.

### 4. Kết luận ngắn
Qua bài lab này, em hiểu rõ hơn về mô hình CIA và cách áp dụng vào một hệ thống thực tế như hệ thống lưu điểm. Em nhận ra rằng mỗi thành phần trong hệ thống, từ dữ liệu đến người dùng, đều có thể trở thành điểm yếu nếu không được bảo vệ phù hợp. Phần khó nhất là phân biệt giữa threat và vulnerability vì hai khái niệm này khá dễ nhầm lẫn. Bài lab cũng giúp em hiểu tầm quan trọng của việc phân quyền và kiểm soát truy cập trong việc đảm bảo tính toàn vẹn của dữ liệu.

- Reviewed final submission before pushing