# 🔍 Trình Quét Mã QR từ Clipboard và File

Ứng dụng web công cụ gọn nhẹ chạy hoàn toàn độc lập, giúp giải mã các mã QR trực tiếp từ ảnh chụp, hình ảnh lưu trữ hoặc dữ liệu sao chép từ bộ nhớ đệm (Clipboard) một cách nhanh chóng và bảo mật.

---

## ✨ Tính Năng Nổi Bật

* **Hoạt động Offline an toàn:** Quá trình phân tích cú pháp dữ liệu hình ảnh và giải mã QR diễn ra hoàn toàn cục bộ trên trình duyệt thông qua thư viện `jsQR`. Ứng dụng tuyệt đối không gửi tập tin hay dữ liệu hình ảnh lên máy chủ, bảo mật thông tin tối đa.

* **Đa phương thức nạp ảnh linh hoạt:**
* Hỗ trợ đọc dữ liệu ảnh trực tiếp từ bộ nhớ tạm bằng phím tắt hệ thống `Ctrl+V` (hoặc `Cmd+V`).

* Hỗ trợ kéo và thả tệp tin ảnh mã QR trực tiếp vào vùng hiển thị (Drop zone).

* Nhấp chọn truyền thống từ máy tính thông qua hộp thoại tải tệp tin.

* **Quét mã thời gian thực chất lượng cao:** Sử dụng HTML5 Canvas để tái tạo hình ảnh theo đúng kích thước gốc nguyên bản, tối ưu hóa độ chính xác và tăng cường tỷ lệ giải mã thành công đối với các mã QR mờ hoặc phức tạp.

* **Trải nghiệm người dùng mượt mà:** Tích hợp sẵn bộ chỉ báo trạng thái chờ (Loading spinner), hiển thị thông báo lỗi chi tiết khi không tìm thấy mã, và nút sao chép nhanh nội dung sau khi quét thành công.

---

## 📐 Định Dạng Dữ Liệu Đầu Vào

Để hệ thống xử lý và phân tách mã vạch chính xác, dữ liệu nạp vào cần đảm bảo:

* **Định dạng tệp hỗ trợ:** Tất cả các loại định dạng tệp tin hình ảnh hợp lệ (MIME type bắt đầu bằng `image/*`).

* **Chuẩn hoá sao chép:** Khi sử dụng tính năng dán tự động qua nút bấm, trình duyệt cần được cấp quyền đọc Clipboard nâng cao (Clipboard API). Nếu bị hạn chế quyền, người dùng có thể sử dụng trực tiếp phím tắt để thay thế.

---

## 🛠️ Hướng Dẫn Sử Dụng

* **Nạp ảnh QR vào hệ thống:**
* **Cách 1:** Sao chép một hình ảnh mã QR, nhấp nút **Dán ảnh QR (Ctrl+V)** hoặc nhấn tổ hợp phím `Ctrl+V` trên bàn phím.

* **Cách 2:** Nhấp nút **Chọn ảnh từ File** để duyệt ảnh từ thiết bị.

* **Cách 3:** Kéo tệp tin hình ảnh mã QR từ máy tính và thả trực tiếp vào khung nét đứt **Ảnh đã tải**.

* **Kiểm tra kết quả giải mã:**
* Sau khi tải ảnh lên, hệ thống tự động xử lý và kết xuất nội dung ra khung **Nội dung mã QR**.

* Nếu mã QR hợp lệ, thông báo **Quét Thành Công!** màu xanh lá sẽ xuất hiện kèm nội dung văn bản chi tiết bên trong.

* **Sao chép dữ liệu:** Nhấp chọn nút **Chép vào Clipboard** để lưu toàn bộ chuỗi ký tự đã giải mã vào bộ nhớ đệm, sẵn sàng sử dụng cho các mục đích khác.

---

## 📝 Thông Tin Phát Triển

* **Tác giả:** Dương Tấn Chánh

* **Công nghệ tích hợp:** HTML5 (Canvas API, Drag and Drop API), CSS3 (Variables & Grid Layout), JavaScript Thuần (Vanilla JS) kết hợp cùng thư viện mã nguồn mở trực tuyến `jsQR.js` hiệu năng cao.
