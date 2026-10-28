# Diễn đàn M&A Miền Trung 2026

Landing page sự kiện VMAA, chạy bằng HTML, CSS và JavaScript thuần.

Website GitHub Pages: https://kirei1805.github.io/VMMA/

## Chỉnh sửa

- `index.html`: cấu trúc, nội dung các section và khối pha lê mở đầu.
- `content.js`: dữ liệu sự kiện, hồ sơ dự kiến, chương trình và thông tin tham dự.
- `app.js`: animation, tương tác, bộ lọc chương trình, xem hồ sơ và tải lịch ICS.
- `styles.css`, `sections.css`: kiểu chữ, bảng màu và bố cục chung.
- `hero-v2.css`: chữ key visual và M&A lấy từ artwork gốc.
- `takeaways.css`: Section 7 với nội dung gom trái, ảnh đổi theo mục ở bên phải.
- `assets/`: hình ảnh và font tự lưu.
- `licenses/`: giấy phép font.

Chạy thử tại thư mục repo:

```sh
python3 -m http.server 4173
```

Mở http://127.0.0.1:4173/ để xem.

## Xuất bản

Mỗi lần push vào `main`, workflow `.github/workflows/pages.yml` triển khai toàn bộ trang tĩnh lên GitHub Pages. Theo dõi tiến trình tại tab Actions. Repository Settings → Pages dùng nguồn **GitHub Actions**.

Đường dẫn ảnh, font, CSS và JavaScript đều tương đối để hoạt động dưới `/VMMA/`.

## Trạng thái nội dung

Danh sách diễn giả đang là bản dự kiến. Giá vé, hạn đăng ký, địa điểm cụ thể và kênh liên hệ đang chờ thông tin chính thức; cập nhật trong `content.js` khi được chốt. Hiện trang không có backend hoặc biểu mẫu thu thập thông tin cá nhân.

Artwork nhận diện được sử dụng từ bộ tài sản VMAA do chủ dự án cung cấp. Manrope, Plus Jakarta Sans và Outfit được lưu tại chỗ; giấy phép font nằm trong `licenses/`.
