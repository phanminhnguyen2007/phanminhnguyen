# Bài Tập Website Tĩnh - PMNStore

## Thông Tin Sinh Viên
- **Họ và tên:** Phan Minh Nguyên
- **Mã số sinh viên:** 2531540259
- **Lớp:** 25ĐHSA03

## Mô Tả Dự Án
Website tĩnh giới thiệu và bán các sản phẩm công nghệ **PMNStore** (Điện thoại, Laptop, Máy tính bảng, Phụ kiện) được xây dựng bằng HTML5, CSS3 và JavaScript. Website sở hữu giao diện hiện đại, tối ưu trải nghiệm người dùng với bộ lọc sản phẩm linh hoạt, trung tâm tra cứu cấu hình kỹ thuật thông minh và khả năng hiển thị tương thích trên mọi thiết bị (Responsive).

## Cấu Trúc Website
- `index.html`: Trang chủ giới thiệu chung, banner nổi bật và sản phẩm nổi bật.
- `about.html`: Trang giới thiệu về cửa hàng, tầm nhìn và giá trị cốt lõi.
- `products.html`: Trang cửa hàng tích hợp bộ lọc danh mục sản phẩm (Điện thoại, Laptop, Phụ kiện) và nhãn dán khuyến mãi.
- `details.html`: Trang hiển thị thông số kỹ thuật chi tiết (tự động đọc tham số URL `?id=...` để hiện cấu hình chi tiết sản phẩm hoặc hiển thị Bảng tra cứu cấu hình nhanh).
- `services.html`: Trang giới thiệu các dịch vụ hậu mãi, bảo hành và sửa chữa.
- `gallery.html`: Trang thư viện bộ sưu tập hình ảnh sản phẩm và không gian cửa hàng.
- `blog.html`: Trang tin tức, đánh giá và cập nhật công nghệ mới.
- `contact.html`: Trang biểu mẫu liên hệ, bản đồ và thông tin hỗ trợ khách hàng.
- `css/style.css`: File định dạng giao diện chung, hiệu ứng hover và responsive.
- `images/`: Thư mục chứa hình ảnh sản phẩm, Logo và Favicon hiển thị trên tab trình duyệt.

## Công Nghệ Sử Dụng
- **HTML5**: Semantic HTML (`<header>`, `<nav>`, `<main>`, `<article>`, `<footer>`).
- **CSS3**: CSS Grid, Flexbox, CSS Animation, Media Queries (Responsive Design).
- **JavaScript (Vanilla JS)**: Lọc sản phẩm theo danh mục không tải lại trang, xử lý `URLSearchParams` để render dữ liệu cấu hình chi tiết theo ngữ cảnh.
- **GitHub Pages**: Triển khai website trực tuyến.
