# IE207.Q11.CNVN
Dự án "Xây dựng Website bán vé xem phim" - một hệ thống thương mại điện tử B2C tập trung giải quyết bài toán số hóa quy trình đặt vé, chọn ghế trực quan và quản lý rạp chiếu phim.
-------------

## 1. Danh sách nhóm

| STT | MSSV     |             Họ và tên             | Vai trò              |
|-----|----------|:-------------------------------:|----------------------|
| 1   | 22521488 | Lê Đức Khánh Toàn               | Backend & Database   |
| 2   | 22521562 | Ngụy Công Vũ Trung              | Frontend & UI/UX     |

## 2. Tài nguyên

- **Công cụ quản lý & Triển khai:** Github, Jira.
- **Backend:** NestJS (Node.js), MongoDB.
- **Frontend:** NextJS (React), Tailwind CSS.

## 3. Tính năng nổi bật

### Phân hệ Khách hàng:
- **Đặt vé thời gian thực:** Chọn ghế trực quan với trạng thái ghế (Đang chọn, Đã đặt) được cập nhật realtime.
- **Xử lý đồng thời (Concurrency):** Hệ thống tự động khóa ghế tạm thời để ngăn chặn việc trùng vé khi nhiều người cùng chọn.
- **Tìm kiếm thông minh:** Hỗ trợ tìm kiếm phim tiếng Việt có dấu/không dấu (Full-text search).

### Phân hệ Quản trị:
- **Quản lý rạp & Suất chiếu:** Giao diện thêm/xóa/sửa phim, phòng chiếu và xếp lịch chiếu linh hoạt.
- **Thống kê báo cáo:** Biểu đồ doanh thu và tỉ lệ lấp đầy rạp.
