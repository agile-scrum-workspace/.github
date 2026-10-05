# 🔄 Agile Scrum Workspace

Chào mừng bạn đến với **Agile Scrum Workspace** — Không gian làm việc, quản trị mã nguồn và thực hành quy trình phát triển phần mềm theo khung làm việc **Agile/Scrum**.

---

## 🎯 Mục tiêu hoạt động

Workspace được thiết lập nhằm:
- 📌 Chuẩn hóa quy trình phát triển phần mềm theo tiêu chuẩn Scrum Guide.
- 🚀 Quản lý source code, tài liệu và tiến độ các dự án phần mềm theo từng Sprint.
- 🤝 Rèn luyện kỹ năng làm việc nhóm, thực hành Git flow, Code Review và chuẩn bàn giao sản phẩm (*Definition of Done*).

---

## 🏛️️ 3 Trụ cột vận hành

1. **Minh bạch (Transparency):** Mọi công việc, trạng thái task và tiêu chí nghiệm thu đều được hiển thị rõ ràng trên Sprint Board.
2. **Thanh tra (Inspection):** Rà soát tiến độ và chất lượng qua các sự kiện Daily Scrum, Sprint Review và Pull Request.
3. **Thích nghi (Adaptation):** Điều chỉnh Product Backlog và cải tiến quy trình làm việc ngay sau buổi Sprint Retrospective.

---

## ⚙️ Quy chuẩn nhịp Sprint (Cadence)

- **Độ dài Sprint cố định:** 2 tuần/Sprint (Timeboxed).
- **Tiêu chuẩn hoàn thành (DoD):** Tính năng chỉ được coi là hoàn tất khi đã qua kiểm thử, chạy ổn định và đạt tiêu chuẩn chất lượng đã thống nhất.
- **Cải tiến liên tục:** Sprint Retrospective là sự kiện bắt buộc cuối mỗi Sprint nhằm chọn ra ít nhất một điểm cần cải tiến cho Sprint kế tiếp.

---

## 🚀 Kế hoạch khởi tạo (Workspace Setup)

- [ ] Hoàn thiện hồ sơ và phân quyền thành viên trong Organization
- [ ] Thiết lập Project Board (Product Backlog / Sprint Backlog)
- [ ] Khởi tạo Repository chứa tài liệu quy trình và User Stories
- [ ] Khởi tạo các Repository mã nguồn cho dự án (Frontend / Backend)
- [x] Thống nhất quy chuẩn Branching, Commit Message và PR Description

---

## 🛠️ Quy chuẩn Git & Mô tả khi Push / Tạo PR

Mọi thành viên tuân thủ các quy tắc sau để giữ lịch sử code minh bạch, dễ theo dõi:

### 1. Quy tắc đặt tên nhánh (Branch)
- `feature/<tên-tính-năng>`: Thêm tính năng mới (ví dụ: `feature/login-screen`).
- `bugfix/<tên-lỗi>`: Sửa lỗi phát sinh (ví dụ: `bugfix/fix-token-expiration`).
- `docs/<nội-dung>`: Cập nhật tài liệu, README.

### 2. Quy chuẩn Commit Message (Conventional Commits)
Cú pháp: `<loại>: <mô tả ngắn gọn>`
- `feat:` Thêm tính năng mới (ví dụ: `feat: tích hợp api đăng nhập google`)
- `fix:` Sửa bug (ví dụ: `fix: sửa lỗi crash khi chưa cấp quyền vị trí`)
- `docs:` Viết tài liệu (ví dụ: `docs: bổ sung hướng dẫn chạy sprint`)
- `refactor:` Tối ưu code nhưng không đổi logic chạy
- `test:` Bổ sung hoặc sửa unit test

---

## 👤 Thông tin Tác giả

* **Email liên hệ:** ankhangbc.2021@gmail.com