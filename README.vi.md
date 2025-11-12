# MacOS New File

**[English](./README.md) | [Tiếng Việt](#)**

Repository này chứa một workflow macOS cho phép thêm hành động "Create New File" vào menu chuột phải trong Finder. Đây là một tính năng hữu ích cho những người dùng thấy Finder của macOS thiếu chức năng thiết yếu này.

![demo.gif](./demo.gif)

## Tính năng

- Thêm hành động "Tạo tệp mới" vào menu chuột phải trong Finder
- Tên tệp sẽ tự động tăng số để tránh xung đột với tệp mới đã tồn tại
- **Chức năng tự động đổi tên**: Tự động vào chế độ đổi tên sau khi tạo tệp
- Tên Quick Action có thể tùy chỉnh (hỗ trợ tiếng Anh/tiếng Việt)

## Cài đặt

1. Clone repo này
2. Double-click vào package "Tạo tệp mới.workflow" để cài đặt workflow.
3. Làm theo hướng dẫn trên màn hình để thêm workflow vào hệ thống của bạn.

Sau khi cài đặt, bạn sẽ thấy hành động "Create New File" trong menu chuột phải khi bạn **click vào thư mục** hoặc **vào tab Finder**.

## Sử dụng

1. Chuột phải vào một thư mục hoặc vào tab Finder.
2. Từ menu ngữ cảnh, trong phần "Quick Actions", chọn hành động "Tạo tệp mới".
3. Một tệp mới sẽ được tạo trong thư mục với tên "untitled.txt". Sau đó bạn có thể đổi tên tệp và sửa phần mở rộng nếu cần.

## Tùy chỉnh

Để thay đổi tên tệp mặc định cho các tệp mới được tạo, làm theo các bước sau:

1. Mở ứng dụng `Automator` trên Mac của bạn.
2. Trong Automator, chọn "Open" từ menu File, và điều hướng đến workflow đã cài đặt (`~/Library/Services/MacOS_New_File.workflow`).
3. Tìm action script `bash` trong workflow.
4. Chỉnh sửa script `bash` để thay thế tên tệp mặc định bằng tên tệp bạn muốn.
5. Lưu thay đổi và đóng ứng dụng Automator.

## Đóng góp

Nếu bạn có bất kỳ đề xuất, báo cáo lỗi hoặc cải tiến nào, hãy thoải mái gửi pull request hoặc tạo issue. Chúng tôi đánh giá cao mọi đóng góp và phản hồi của bạn!

## Credits

Dự án này là phiên bản sửa đổi dựa trên [macos-new-file](https://github.com/dohsimpson/macos-new-file) của Doh.

**Cải tiến bởi Finix:**
- ✨ Chức năng tự động đổi tên: Tệp tự động vào chế độ đổi tên sau khi tạo
- 🌏 Hỗ trợ đa ngôn ngữ: Tên Quick Action có thể tùy chỉnh (tiếng Anh/tiếng Việt)
- 🔧 Cải thiện trải nghiệm người dùng với quy trình tạo tệp liền mạch
- 📖 Tài liệu tiếng Việt (README.vi.md)

Đặc biệt cảm ơn [Doh](https://github.com/dohsimpson) cho phiên bản gốc!

## Giấy phép

Dự án này được phát hành theo [Giấy phép MIT](LICENSE).
