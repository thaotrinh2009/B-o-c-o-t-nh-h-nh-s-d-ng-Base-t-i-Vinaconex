# Tình hình sử dụng Base tại Vinaconex

Báo cáo tình hình sử dụng 5 app **Task, BPM, E-office, Booking, Project** theo người dùng và theo Ban/đơn vị tại Vinaconex.

- Trang báo cáo: `index.html` (GitHub Pages)
- Kỳ hiện tại: **01/11/2026**, so sánh với kỳ 23/10/2026. Trạng thái đăng nhập cập nhật ngày 02/11/2026.
- Dữ liệu chi tiết từng bản ghi nằm trong Google Sheet đi kèm (không đưa lên repo vì có thông tin cá nhân).

## Số liệu chính kỳ 01/11/2026

| Chỉ số | 23/10 | 01/11 |
|---|---|---|
| Nhân sự có tài khoản (đã loại tài khoản test) | 244 | 253 |
| Đã dùng Base (gồm chỉ đăng nhập/xem) | 208 (85,2%) | **230 (90,9%)** |
| – trong đó có tác nghiệp ≥1 app | 138 (56,6%) | **185 (73,1%)** |
| – chỉ đăng nhập/xem, chưa tác nghiệp | 70 | 45 |
| Chưa đăng nhập lần nào | 36 | 22 (+1 tài khoản trùng) |

Theo app (người có tác nghiệp, kỳ 01/11): Task 159 · BPM 63 · Booking 56 · E-office 23 · Project 15.
Bản ghi thật trong tháng 10: Task 1.182 việc · BPM 114 phiếu · Booking 154 lượt · E-office 54 văn bản · Project 74 việc.

## Các mục trên báo cáo

1. **Mức độ sử dụng:** chưa đăng nhập / chỉ đăng nhập-xem / tác nghiệp 1, 2, 3+ app.
2. **Theo Ban:** độ phủ, tỷ lệ dùng từng app, số người chưa đăng nhập, khối lượng tác nghiệp.
3. **Theo ứng dụng:** trạng thái công việc, phiếu, văn bản, lượt đặt, dự án.
4. **15 người dùng tích cực nhất.**
5. **Chi tiết nhân sự theo Ban:** trạng thái từng người, lọc theo Ban/trạng thái, tải CSV.
6. **Đã đăng nhập nhưng chưa có thao tác nghiệp vụ,** theo Ban: số lần đăng nhập, lần gần nhất, số công việc đã xem (in, tải CSV).
7. **Chưa đăng nhập Base,** theo Ban (in, tải CSV).

## Cách tính

- **Đã dùng Base:** có đăng nhập Base (web hoặc app điện thoại, theo nhật ký đăng nhập hệ thống từ 22/09/2026) hoặc đã mở xem/thao tác trên ít nhất một app.
- **Tác nghiệp:** Task – tạo, hoàn thành hoặc bình luận ≥1 việc; BPM – tạo phiếu hoặc xử lý/duyệt ≥1 bước; E-office – tạo văn bản hoặc có ≥1 thao tác; Booking – đặt ≥1 lượt; Project – tạo ≥1 công việc hoặc có ≥1 thao tác trong dự án.
- **Chỉ đăng nhập/xem:** có vào hệ thống nhưng chưa tạo hay xử lý bản ghi nào. Đây là cách dùng phù hợp với vai trò của lãnh đạo.
- **Loại khỏi số liệu:**
  - Tài khoản test/Base: Quản trị hệ thống, quanly, Kiem Thu.
  - Bản ghi có tiêu đề test/demo hoặc tiêu đề rác.
  - Dữ liệu thực hành trong các buổi đào tạo: BPM 08–09/10, Booking 09/10, E-office 20/10.
  - Các bản ghi bị loại vẫn giữ trong Google Sheet, đánh dấu "Test" ở cột "Dữ liệu test".
- **Gán Ban:** theo nhóm người dùng trên Base. Chỉ huy trưởng/BĐH công trường chưa thuộc nhóm nào được gom vào "BCH/BĐH công trường (chưa gán Ban)".

## Lịch sử cập nhật

- **02/11/2026:**
  - Sửa định nghĩa "đã dùng": tính cả người đăng nhập để xem, theo dõi. Bản trước ghi nhầm một số lãnh đạo là "chưa dùng".
  - Tách riêng danh sách đã đăng nhập nhưng chưa tác nghiệp (mục 6) và danh sách chưa đăng nhập (mục 7).
  - Tính bình luận trên Task là tác nghiệp.
- **01/11/2026:** quét kỳ mới; thêm app Project; loại thêm dữ liệu thực hành đào tạo; so sánh với kỳ 23/10.
- **23/10/2026:** quét kỳ 2; thêm chi tiết nhân sự theo Ban và danh sách chưa dùng.
- **16/10/2026:** kỳ quét đầu tiên (Task, BPM, E-office, Booking).

## Cần khách hàng xác nhận

- **Tài khoản trùng:** Ngọ Văn Thành có 2 tài khoản; một tài khoản đã dùng, một chưa đăng nhập.
- **Trùng tên khác Ban:** Vũ Anh Tuấn (Ban Xây dựng / Ban Đầu tư) và Nguyễn Minh Thắng (Ban Đầu tư / Văn phòng TCT).
- **Tài khoản có thể tạo nhầm:** "Bùi Hoàng Bảo Bảo" và "Trần Tuấn Nghĩa Nghĩa".
- **Chưa thuộc Ban nào:** 21 tài khoản mới (chủ yếu chỉ huy trưởng/BĐH công trường) cần gán vào nhóm người dùng.
