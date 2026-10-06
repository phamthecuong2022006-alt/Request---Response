BOOK MANAGEMENT MVC - ASP.NET CORE MVC

Công nghệ:
- ASP.NET Core MVC .NET 8
- Entity Framework Core 8
- SQL Server / LocalDB
- Code First

CHẠY BÀI:
1. Mở file BookManagementMVC.csproj bằng Visual Studio 2022.
2. Nếu máy dùng SQL Server LocalDB thì giữ nguyên connection string trong appsettings.json.
3. Mở Package Manager Console và chạy:
   Add-Migration InitialCreate
   Update-Database
4. Nhấn Ctrl + F5 hoặc nút Run.
5. Website mặc định mở vào /Books/Index.

Nếu không muốn dùng Migration:
- Mở SQL Server Management Studio.
- Chạy toàn bộ file database.sql.
- Đảm bảo connection string trỏ đúng SQL Server của máy.

Chức năng:
- Hiển thị danh sách sách
- Tìm kiếm theo tên sách/tác giả
- Thêm sách
- Xem chi tiết
- Sửa sách
- Xóa sách
- Validation dữ liệu
