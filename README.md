## baocao11-12
# Các bài tập đã làm
# Bài 1: tính điểm học kì

-Tạo file DLL.

-Thêm DLL vào References của ứng dụng console.

-Sử dụng các lớp và phương thức từ DLL trong code của console.

https://github.com/giapquocank57/BTVN

# Bài 2: Web giám sát vị trí thành viên trong lớp

1.Phương pháp sử dụng file text

-Tạo file text: Tạo file để lưu thông tin vị trí sinh viên.

-Định dạng dữ liệu: Lưu dữ liệu theo định dạng key-value, mỗi dòng một sinh viên (ví dụ: Q: vị trí sinh viên 1).

-Đọc dữ liệu: Khi cần, đọc file và trích xuất các giá trị theo từng dòng.

-Chuyển đổi sang JSON: Sau khi đọc, chuyển dữ liệu thành JSON để gửi tới client.

-Cập nhật dữ liệu: Ghi đè dữ liệu mới vào file khi vị trí sinh viên thay đổi.

2.Phương pháp sử dụng cơ sở dữ liệu SQL

-Thiết kế cơ sở dữ liệu: Tạo bảng StudentPositions với các trường lưu vị trí của từng sinh viên.

-Kết nối cơ sở dữ liệu: Sử dụng chuỗi kết nối để liên kết ứng dụng với SQL database.

-Truy vấn dữ liệu: Thực hiện lệnh truy vấn để lấy thông tin từ bảng và chuyển đổi thành JSON để gửi tới client.

-Cập nhật dữ liệu: Dùng lệnh UPDATE để thay đổi vị trí trong bảng khi cần.

-Gửi dữ liệu JSON: Sau khi truy vấn hoặc cập nhật, chuyển đổi dữ liệu sang JSON để truyền tới client.

https://github.com/giapquocank57/Web_giapqan

# Bài 3: capcha

1.DLL tạo CAPTCHA:

-Xử lý ảnh nền với hiệu ứng sóng, gạch chéo, nghiêng, và nhiễu.

-Sinh ký tự CAPTCHA từ chuỗi đầu vào với màu sắc và hiệu ứng.

-Trả về hình ảnh CAPTCHA đã tạo.

2.WinForm hiển thị CAPTCHA:

-Gọi DLL để tạo và hiển thị CAPTCHA khi cần.

-Tạo sự kiện kiểm tra nhập CAPTCHA, hiển thị lỗi nếu nhập sai.

-Cho phép tải lại CAPTCHA khi yêu cầu.

3.Web đăng nhập hiển thị CAPTCHA:

-Tạo giao diện CSS cho trang đăng nhập và CAPTCHA.

-Sử dụng jQuery/JS để gửi thông tin đăng nhập qua AJAX.

-Hiển thị lỗi nhập sai và cập nhật CAPTCHA khi tải lại.

https://github.com/giapquocank57/ClassLibrarycapcha

# Web tính thời gian thực 

1.Thiết lập cơ sở dữ liệu (CSDL)

-Thiết kế bảng dữ liệu: Tạo các bảng (thiết bị, dữ liệu giám sát, người dùng,…) tối ưu cho truy xuất dữ liệu lớn.

-Tạo stored procedures (SP): Hỗ trợ thêm, cập nhật, xóa và truy vấn dữ liệu, tự động chuyển đổi sang JSON nếu cần.

-Cấu hình quyền truy cập: Thiết lập quyền truy cập để bảo mật dữ liệu.

2.Tác động của phần cứng đến CSDL

-Thiết bị IoT thu thập và gửi dữ liệu: Tối ưu hóa cấu trúc bảng và chỉ mục để đảm bảo hiệu suất.

3.Tạo DLL độc lập tương tác với CSDL

-Tạo dự án Class Library (DLL): Chứa các phương thức truy vấn, cập nhật, và thao tác với CSDL.

-Thêm thư viện kết nối: Chẳng hạn, System.Data.SqlClient cho SQL Server.

-Biên dịch và xuất DLL độc lập để tái sử dụng.

4.Xây dựng API trên ASP.NET cho giao tiếp JSON

-Tạo dự án ASP.NET Web API: Để giao tiếp HTTP giữa server và client.

-Cấu hình kết nối CSDL: Cấu hình kết nối CSDL trong appsettings.json.

-Xây dựng controller: Xử lý các yêu cầu CRUD, trả dữ liệu dưới dạng JSON.

-Sử dụng JSON serialization/deserialization để chuyển đổi dữ liệu.

5.Xây dựng giao diện với HTML, CSS, jQuery, jQuery-UI, và jQuery-confirm

-Thiết kế HTML/CSS: Tạo giao diện cơ bản với HTML và định dạng bằng CSS.

-Dùng jQuery AJAX: Gửi và nhận dữ liệu JSON từ API mà không cần tải lại trang.

-Sử dụng jQuery-UI và jQuery-confirm: Thêm hiệu ứng và các hộp thoại xác nhận, cải thiện trải nghiệm người dùng.






