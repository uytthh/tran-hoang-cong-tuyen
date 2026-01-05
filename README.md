# tran-hoang-cong-tuyen
1. Giới thiệu
  Employee Management System là ứng dụng web được xây dựng bằng ASP.NET Core MVC,

  cho phép quản lý thông tin nhân viên với các chức năng cơ bản như xem danh sách,

  xem chi tiết, thêm, sửa và xóa nhân viên.

  Ứng dụng áp dụng mô hình MVC (Model – View – Controller)

  và kết nối SQL Server để lưu trữ dữ liệu.

3. Công nghệ sử dụng
   
  -ASP.NET Core MVC

  -.NET 8 / .NET 9

  -SQL Server

  -Entity Framework Core

  -Razor View

-Bootstrap (giao diện)

4. Chức năng chính

Hiển thị danh sách nhân viên

Xem chi tiết thông tin nhân viên

Thêm mới nhân viên

Chỉnh sửa thông tin nhân viên

Xóa nhân viên

5. Cấu trúc thư mục

EmployeeManagement

│
├── Controllers
│   └── EmployeeController.cs

│

├── Models
│   └── Employee.cs

│

├── Views


│   ├── Employee


│   │   ├── Index.cshtml


│   │   ├── Details.cshtml


│   │   ├── Create.cshtml


│   │   ├── Edit.cshtml


│   │   └── Delete.cshtml


│   │

│   └── Shared



│       └── _Layout.cshtml
│



├── wwwroot

│   ├── css

│   └── js
│



├── appsettings.json

└── Program.cs


6. Cấu hình cơ sở dữ liệu

Cập nhật chuỗi kết nối trong appsettings.json:

"ConnectionStrings": 
{
  "DefaultConnection": "Server=.;Database=EmployeeDB;User Id=sa;Password=sa;TrustServerCertificate=True"
}

*Sau đó chạy migration:

  Add-Migration InitDB
  
  Update-Database
  
6. Hướng dẫn chạy chương trình

-Mở project bằng Visual Studio

-Kiểm tra kết nối SQL Server

-Build project

-Run (F5)

-Truy cập:

-https://localhost:7138/Employee

7. Mô hình MVC sử dụng

Model: Đại diện cho dữ liệu (Employee)

View: Giao diện hiển thị dữ liệu (Razor View)

Controller: Xử lý logic và điều hướng (EmployeeController)

8. Kết luận
   
-Ứng dụng giúp áp dụng kiến thức về:

-Lập trình ASP.NET Core MVC

-Kết nối và thao tác với cơ sở dữ liệu SQL Server

-Thiết kế ứng dụng theo mô hình MVC

10. Tác giả

Họ tên: Trần Hoàng Công Tuyển

Lớp: CNTT 17-03

Môn học: Công Nghệ Phần Mềm

Giảng viên hướng dẫn: Giảng viên bộ môn Đỗ Quang Thơ
