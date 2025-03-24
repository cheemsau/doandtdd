

# ChatApp - Java Chat Application

![Java](https://img.shields.io/badge/Java-20-orange) ![License](https://img.shields.io/badge/License-MIT-blue)

**ChatApp** là ứng dụng chat thời gian thực viết bằng Java, sử dụng Swing cho giao diện và socket cho giao tiếp client-server. Hỗ trợ trò chuyện văn bản, gửi tệp, thay đổi avatar và mật khẩu.

---

## Tính năng

- Đăng nhập/Đăng ký tài khoản.
- Chat văn bản thời gian thực.
- Gửi và nhận tệp.
- Cập nhật avatar và mật khẩu.
- Xem danh sách người dùng trực tuyến.

---

## Cấu trúc dự án

- **`com.chatapp.view`**:
  - `LoginFrm`: Đăng nhập/đăng ký.
  - `ChatFrm`: Giao diện chat chính.
  - `ChangeAvatarFrm`: Thay đổi avatar.
  - `ChangePasswordFrm`: Thay đổi mật khẩu.
  - `ServerFrm`: Điều khiển server.
- **`com.chatapp.model`**:
  - `Account`, `TextMessage`, `FileMessage`: Mô hình dữ liệu.
- **`com.chatapp.controller`**:
  - `Server`: Logic server.

---

## Yêu cầu

- **Java**: 20+
- **IDE**: NetBeans (khuyến nghị)
- **Cổng**: 9999 (mặc định)

---

## Hướng dẫn cài đặt

### 1. Clone dự án
```bash
git clone https://github.com/cheemsau/doandtdd.git

```

### 2. Mở trong IDE
- Import dự án vào NetBeans hoặc IDE khác.
- Đảm bảo cấu hình Java Swing và socket.

### 3. Chạy Server
- Mở `ServerFrm.java` → Nhấn "Run" → Nhấn nút "RUN" trong giao diện.

### 4. Chạy Client
- Mở `LoginFrm.java` → Nhấn "Run" → Đăng nhập hoặc đăng ký.

---

## Sử dụng

1. Khởi động server trước.
2. Đăng nhập trên client.
3. Chọn người dùng từ danh sách để chat hoặc gửi tệp.
