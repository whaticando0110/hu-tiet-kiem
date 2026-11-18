# Hũ tiết kiệm thông minh

Đồ án lập trình mobile về quản lý mục tiêu tiết kiệm. Người dùng phân bổ tiền từ ví mô phỏng vào từng hũ, theo dõi tiến độ và xem cách điều chỉnh kế hoạch khi có nguy cơ thiếu tiền vào ngày hạn.

## Kịch bản hũ Laptop

Hũ có **4.000.000 đ** trên mục tiêu **6.000.000 đ**. Ban đầu còn bốn kỳ góp thứ Hai, mỗi kỳ **500.000 đ**. Sau khi bỏ lỡ một kỳ, nếu giữ kế hoạch cũ thì đến hạn sẽ thiếu **500.000 đ**.

| Phương án | Mức góp | Ngày hạn |
| --- | --- | --- |
| A. Giữ ngày hạn | 666.667 đ/kỳ, kỳ cuối góp vừa đủ | 07/12/2026 |
| B. Giữ mức góp | 500.000 đ/kỳ, thêm một kỳ góp | 14/12/2026 |

Theo thiết kế, bộ tính trên thiết bị đếm các ngày góp còn lại và tạo phương án. Chatbot AI giải thích phương án theo ưu tiên người dùng. Khi người dùng xác nhận, ứng dụng chỉ lưu kế hoạch và giữ nguyên số dư.

## Tiến độ

Đã có báo cáo phân tích nghiệp vụ, ERD cho ví, hũ, giao dịch, kế hoạch và nhắc góp, cùng prototype Figma nối từ cảnh báo thiếu hụt đến so sánh, chatbot và xem trước thay đổi. Chatbot trong prototype dùng hội thoại mẫu.

Repo hiện giới thiệu đồ án. Flutter/Dart, SQLite và chatbot kết nối dịch vụ AI là phần triển khai dự kiến.
