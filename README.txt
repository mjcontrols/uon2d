LANDING PAGE MÁY 2D

1. CÁCH MỞ WEBSITE
- Giải nén toàn bộ thư mục.
- Bấm đúp vào file index.html để mở bằng trình duyệt.
- Giữ nguyên cấu trúc thư mục assets/images để hình ảnh hiển thị đúng.

2. ĐỔI SỐ ĐIỆN THOẠI
- Mở index.html bằng trình soạn thảo văn bản.
- Tìm “0985 238 368” để đổi phần hiển thị.
- Tìm “0985238368” để đổi liên kết gọi điện tel:.

3. ĐỔI ĐỊA CHỈ
- Tìm “Bình Dương, TP.HCM” trong index.html và thay bằng địa chỉ mới.
- Cập nhật addressLocality trong khối dữ liệu LocalBusiness ở cuối file.

4. THAY LOGO
- Logo chính MJ Việt Nam: assets/images/logo-mj.webp.
- Logo thương hiệu máy Trung Quốc: assets/images/logo-phuong-hoang.webp.
- Giữ nguyên tỉ lệ ảnh khi thay logo để tránh méo nhận diện.

5. THAY ẢNH
- Chép ảnh mới vào assets/images.
- Ưu tiên WebP, tên file không dấu và không có khoảng trắng.
- Đổi thuộc tính src và alt của ảnh tương ứng trong index.html.

6. ĐƯA WEBSITE LÊN HOSTING
- Có thể tải toàn bộ thư mục lên GitHub Pages, Netlify, Vercel hoặc hosting thông thường.
- index.html phải nằm ở thư mục gốc khi xuất bản.
- Đổi canonical https://example.com/ thành tên miền thật trước khi chạy chính thức.

7. FORM GOOGLE SHEETS / API
- Biến endpoint nằm trong đoạn JavaScript cuối file index.html.
- Endpoint hiện tại là Google Apps Script được cung cấp trong yêu cầu.
- Các trường gửi đi: name/hoTen, phone/soDienThoai, need/nhuCau, source, submittedAt.
- Nếu đổi API, cập nhật endpoint và phần fetch trong trình xử lý submit.
- Thư mục google-sheet có sẵn file Excel mẫu, Code.gs và SETUP.txt để triển khai.

LƯU Ý
- Thông số sản phẩm trên trang dùng để định hướng và cần xác nhận theo từng cấu hình máy.
- Hãy thay canonical và bổ sung logo chính thức nếu có trước khi xuất bản trên tên miền riêng.
