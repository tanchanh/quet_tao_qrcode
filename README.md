# 📱 Quét Và Tạo Mã QR - D.T.Chánh

Ứng dụng web Single-page gọn nhẹ, hiện đại và bảo mật, chạy trực tiếp trên trình duyệt mà không cần cài đặt. Tích hợp trọn bộ 2 chức năng chính: **Quét & Giải mã QR từ hình ảnh/Clipboard** và **Tạo mã QR tùy chỉnh chất lượng cao (SVG/PNG)**.

---

## ✨ Tính Năng Nổi Bật

### 1. 🔍 Quét & Giải Mã QR
* **Hoạt động Offline an toàn:** Quá trình phân tích hình ảnh và giải mã QR diễn ra hoàn toàn cục bộ trên thiết bị của bạn. Không gửi ảnh hay dữ liệu cá nhân lên máy chủ.
* **Nạp ảnh đa phương thức:**
  * **Dán nhanh từ Clipboard:** Nhấn phím tắt `Ctrl+V` (hoặc `Cmd+V`) hoặc bấm nút **Dán ảnh QR**.
  * **Chọn tệp tin:** Tải ảnh từ thư viện thiết bị.
  * **Kéo & Thả (Drag & Drop):** Thả tệp ảnh QR trực tiếp vào khu vực nhận diện.
* **Trích xuất thông tin tức thì:** Tự động nhận diện và hiển thị chuỗi văn bản/đường dẫn, kèm nút **Sao chép nội dung** tiện lợi.

---

### 2. 🎨 Tạo Mã QR Tùy Chỉnh
* **Tự động tạo mã tức thì (Real-time):** Mã QR tự động sinh trực tiếp ngay khi nhập, dán văn bản hoặc thay đổi bất kỳ tùy chọn cấu hình nào mà không cần bấm nút.
* **Sinh ma trận chuẩn xác 100%:** Sử dụng thuật toán ma trận chuyên dụng tạo mã QR đúng tiêu chuẩn ISO/IEC 18004.
* **Hiển thị thông tin mã QR ngắn gọn:** Tự động thống kê Mức sửa lỗi và Kích thước ma trận (ví dụ: 25×25 ô).
* **Tùy chỉnh Mức Sửa Lỗi (Error Correction Level):**
  * **L - Thấp (~7%):** Tối ưu mật độ ô, thích hợp cho dữ liệu dài.
  * **M - Trung bình (~15%):** Mặc định chuẩn cân bằng.
  * **Q - Cao (~25%):** Khôi phục tốt khi mã bị che khuyết một phần.
  * **H - Rất cao (~30%):** Mức bảo vệ tối đa, phù hợp in ấn hoặc chèn logo.
* **Tùy chỉnh Lề Khoảng Trắng (Margin / Quiet Zone):**
  * Hỗ trợ cài đặt lề từ **0 cell** (bỏ hoàn toàn viền trắng ngoài) đến **5 cell**.
* **Kiểu dáng ô (Style) sáng tạo:**
  * **Ô vuông chuẩn (Square):** Truyền thống, sắc nét.
  * **Ô bo góc (Rounded):** Mềm mại, hiện đại.
  * **Chấm tròn (Dots):** Tinh tế, thẩm mỹ cao.
* **Kích thước hiển thị linh hoạt:** Thay đổi kích thước từ 250px đến 500px.
* **Xuất bản & Lưu trữ:**
  * **Tải về file SVG:** Định dạng Vector không bao giờ vỡ nét khi phóng to hay in ấn.
  * **Tải về file PNG:** Ảnh bitmap sắc nét chuẩn kích thước lựa chọn.
  * **Sao chép ảnh QR:** Chép trực tiếp hình ảnh QR vào Clipboard để dán vào Word, Zalo, Messenger, Photoshop,...

---

## 🛠️ Hướng Dẫn Sử Dụng

### 1. Cách Quét Mã QR
1. Chuyển sang thẻ **Quét**.
2. Sao chép ảnh QR rồi nhấn `Ctrl+V` (hoặc nút **Dán ảnh QR**), chọn file ảnh từ máy hoặc kéo thả ảnh vào khung.
3. Kết quả giải mã sẽ hiển thị ngay bên dưới. Nhấn nút **Sao chép nội dung** để lưu thông tin.

### 2. Cách Tạo Mã QR
1. Chuyển sang thẻ **Tạo**.
2. Nhập hoặc dán văn bản, số điện thoại hay đường dẫn (URL) vào ô nhập liệu. Mã QR sẽ được tự động tạo ngay lập tức.
3. Tùy chỉnh các thông số mong muốn: Kích thước, Mức sửa lỗi, Lề khoảng trắng (cell) và Kiểu dáng ô.
4. Nhấn **Sao chép ảnh QR**, **Tải file SVG** hoặc **Tải file PNG** tùy theo nhu cầu sử dụng.

---

## 📝 Thông Tin Phát Triển

* **Tác giả:** Dương Tấn Chánh
* **Công nghệ tích hợp:** HTML5, CSS3 (Variables, Flexbox, Grid), Vanilla JavaScript (ES6+), `qrcode-generator`, `ZXing-JS`, Canvas API, SVG DOM API.
