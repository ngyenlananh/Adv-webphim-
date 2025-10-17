# Dự án WebPhim 🎬

# Sinh viên thực hiện
- **Họ và tên:** Nguyễn Thị Lan Anh  
- **Mã sinh viên:** 23010823 
- **Lớp:** Thiết kế web nâng cao-1-1-25 (COUR01.)
  ***
# Mô Tả Dự Án
📖 Giới thiệu

Dự án Web Xem Phim là một ứng dụng web được xây dựng nhằm cung cấp cho người dùng nền tảng xem phim trực tuyến.
Người dùng có thể tìm kiếm, xem thông tin phim, trailer, và xem phim trực tiếp trên website.
Quản trị viên có thể quản lý danh sách phim, thể loại, tài khoản người dùng và các nội dung liên quan.

## Công nghệ sử dụng
Ngôn ngữ lập trình: PHP , blade 

Framework: Laravel

Cơ sở dữ liệu: MySQL( qua XAMPP) 

Công cụ phát triển: Visual Studio Code, XAMPP

Lưu trữ: GitHub

## Chức năng chính
🎬 1. Trang chủ (Home Page)

Hiển thị danh sách các phim nổi bật, mới cập nhật hoặc được xem nhiều.

Có thanh tìm kiếm và bộ lọc theo thể loại, năm phát hành, quốc gia.

📂 2. Trang danh mục phim (Category Page)

Hiển thị phim theo thể loại (hành động, tình cảm, kinh dị,…).

Cho phép sắp xếp theo tên, ngày đăng, lượt xem.

🔍 3. Tìm kiếm phim (Search)

Người dùng có thể nhập tên phim để tìm nhanh.

Kết quả hiển thị danh sách phim khớp với từ khóa.

🎥 4. Trang xem phim (Watch Page)

Phát video phim (thường là embed hoặc file lưu trên server/CDN).

Hiển thị thông tin chi tiết: tên phim, mô tả, diễn viên, năm phát hành.

👤 5. Đăng nhập / Đăng ký (Authentication)

Cho phép người dùng đăng nhập, đăng ký tài khoản.

Có thể lưu lịch sử xem phim, yêu thích phim.

⭐ 6. Quản trị viên (Admin Panel)

Quản lý danh sách phim: thêm, sửa, xóa.

Quản lý thể loại, diễn viên, năm phát hành, ảnh thumbnail, trailer.

Quản lý người dùng (nếu có tính năng thành viên).

💾 7. Lưu dữ liệu (Database Integration)

Toàn bộ thông tin phim, tài khoản người dùng, thể loại được lưu trong cơ sở dữ liệu (MySQL hoặc SQLite).

Các model trong Laravel như Movie, Category, User, v.v. quản lý dữ liệu này.

🌐 8. Giao diện người dùng (Frontend)

Sử dụng HTML, CSS, JS (và có thể Blade template trong Laravel).

Giao diện thân thiện, responsive để xem trên điện thoại và máy tính.

Có gợi ý phim liên quan hoặc phim cùng thể loại.

# Sơ đồ hệ thống Website
## Sơ đồ chức năng

<img width="471" height="902" alt="image" src="https://github.com/user-attachments/assets/162d95cb-e13b-4843-ba1f-9ff10e1a7f4e" />


