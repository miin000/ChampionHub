# FlashNoter Project

# Technologies

## Laravel framework
### Laravel basic
1. Routing trong Laravel
  Routing là gì?
  Routing là quá trình khớp yêu cầu (request) đến một đoạn mã cụ thể trong ứng dụng. Laravel cung cấp một hệ thống routing đơn giản và mạnh mẽ, cho phép bạn xác định cách ứng dụng phản hồi các yêu cầu khác nhau.
  
  Cách định nghĩa route trong Laravel:
  
  Class Route: Dùng để khai báo các route.
  Phương thức GET: Được sử dụng để xử lý các yêu cầu HTTP GET.
    Ví dụ:
    ```
    Route::get('/', function () {  
        return "Hello World";  
    });
    ```
    Đoạn mã trên định nghĩa một route tại URL / và trả về chuỗi "Hello World".
  ####Cấu trúc thư mục Routes:
  
  Laravel lưu các route trong thư mục routes. Các file trong thư mục này được load tự động bởi Route Service Provider.
  web.php: Chứa các route dành cho giao diện web và được gắn với middleware web. Middleware này cung cấp các tính năng như session state và CSRF protection.
  api.php: Chứa các route cho API. Các route này không có trạng thái và được gắn với middleware API.
  API routes hoạt động như data provider và có thể dùng thêm các middleware khác, bao gồm authorization và authentication.
    Ví dụ về route API:
    ```
    Route::get('/user', function () {  
        return "User will be loaded";  
    });
    ```
  Chạy server bằng Artisan:
  Dùng lệnh php artisan serve để khởi chạy server. Mặc định, server sẽ chạy ở cổng 8000.

### MVC

### MySQL/SQL/postgresSQL/no-sql Database (Firebase, Mongo DB)

### Programming Language



## PHP (OOP)

### PHP tags
```
<?php
  // Code block
?>
```
### Outputtinng 
```
echo
print
```
### Comments
```
single-line: \\
multiline: /* */
```
### Variables
```
$name = "Minh";
$age = 19;
```
### Functions
```
<?php
  fountion greet($name){
    echo "Hello, $name";
    greet("Minh");
?>

Out put--> Hello, Minh
```
