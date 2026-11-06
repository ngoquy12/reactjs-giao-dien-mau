# Giao diện mẫu cho bài tập ReactJS (HTML + Bootstrap)

Mỗi thư mục là giao diện mẫu của một bài tập: HTML thuần kết hợp Bootstrap 5.3.3, không có mã React. Bạn chuyển HTML sang JSX bằng công cụ https://transform.tools/html-to-jsx, tách thành component rồi nối dữ liệu và hành vi theo đề bài.

## Cách dùng

```bash
git clone https://github.com/ngoquy12/reactjs-giao-dien-mau.git
```

Mở tệp `index.html` của bài bằng trình duyệt (bấm đúp tệp, không cần máy chủ). Cần có mạng để tải Bootstrap từ CDN.

## Danh sách bài

| Bài | Thư mục |
| :-- | :-- |
| Session 01, Bài 1: Danh bạ nhân viên | `session-01/bai-1-danh-ba-nhan-vien` |
| Session 01, Bài 2: Todo list | `session-01/bai-2-todo-list` |
| Session 01, Bài 3: Todo lưu trong trình duyệt và hẹn giờ | `session-01/bai-3-todo-luu-trinh-duyet-va-hen-gio` |
| Session 01, Bài 4: Quản lý nhân viên với reducer và context | `session-01/bai-4-quan-ly-nhan-vien-reducer-context` |
| Session 01, Bài 5: Quản lý nhân viên nhiều trang | `session-01/bai-5-quan-ly-nhan-vien-nhieu-trang` |
| Session 01, Bài 6: Quản lý nhân viên với API | `session-01/bai-6-quan-ly-nhan-vien-voi-api` |
| Session 02, Bài 1: Bảng công việc | `session-02/bai-1-bang-cong-viec-giao-dien` |
| Session 02, Bài 2: Thêm và lọc công việc | `session-02/bai-2-them-va-loc-cong-viec` |
| Session 02, Bài 3: Widget thời tiết | `session-02/bai-3-widget-thoi-tiet-open-meteo` |
| Session 02, Bài 4: Công việc với API crudcrud | `session-02/bai-4-cong-viec-voi-api-crudcrud` |
| Session 02, Bài 5: Task Hub nhiều trang và đăng nhập | `session-02/bai-5-task-hub-nhieu-trang-va-dang-nhap` |
| Session 02, Bài 6: Bảng điều khiển Task Hub | `session-02/bai-6-bang-dieu-khien-task-hub` |

Bài nhiều màn hình (Session 01 Bài 5 và Bài 6, Session 02 Bài 5) có nhiều trang HTML; `index.html` là trang mục lục liên kết tới các trang còn lại.
