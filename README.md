# Grenninn
Quản lý phòng trọ

Mô tả dự án

Hệ thống quản lý phòng trọ được thiết kế để hỗ trợ quản lý thông tin về các loại phòng trọ, người thuê phòng, và chủ phòng. Dự án nhằm tự động hóa việcphysics://i.stack.imgur.com/a/8qYkJ.png) Dự án được thực hiện theo nhóm, bao gồm các bước từ lập kế hoạch, thiết kế, triển khai mã nguồn, đến kiểm thử.

Tiến độ thực hiện

Câu 1: Lập kế hoạch dự án





Xác định yêu cầu: Quản lý thông tin phòng trọ, người thuê, và chủ phòng.



Phân chia công việc nhóm: Thiết kế, lập trình, kiểm thử, và tài liệu hóa.



Lập kế hoạch thời gian: Hoàn thành các bước từ Câu 1 đến Câu 5 trong thời gian quy định.

Câu 2: Thiết kế sơ bộ





Xác định các đối tượng chính:





LoaiPhong: Quản lý mã phòng và giá thuê.



NguoiThuePhong: Quản lý CCCD và số điện thoại của người thuê.



ChuPhong: Quản lý LanlordID, tên, và số điện thoại của chủ phòng.



Thiết kế các thuộc tính và phương thức cơ bản cho từng class.

Câu 3: Cấu trúc thư mục dự án

Cấu trúc thư mục được tổ chức để hỗ trợ làm việc nhóm và quản lý mã nguồn:

/QuanLyPhongTro
├── /src
│   ├── /main
│   │   ├── /java
│   │   │   ├── /model
│   │   │   │   ├── LoaiPhong.java
│   │   │   │   ├── NguoiThuePhong.java
│   │   │   │   ├── ChuPhong.java
│   │   │   ├── /controller
│   │   │   ├── /view
│   │   │   ├── /utils
│   ├── /test
│   │   ├── /java
│   │   │   ├── /model
│   │   │   │   ├── LoaiPhongTest.java
├── /docs
│   ├── requirements.md
│   ├── design.md
├── /resources
│   ├── config.properties
├── README.md
├── pom.xml

Câu 4: Triển khai mã nguồn

Ba class chính đã được viết trong package model:





LoaiPhong: Chứa các thuộc tính maPhong (String), gia (double).



NguoiThuePhong: Chứa các thuộc tính cccd (String), soDienThoai (String).



ChuPhong: Chứa các thuộc tính lanlordID (String), name (String), soDienThoai (String). Mỗi class bao gồm constructor, getter, setter, và phương thức toString.

Câu 5: Kiểm thử





Đã viết class kiểm thử LoaiPhongTest sử dụng JUnit.



Kiểm tra các phương thức getter, setter, và toString của class LoaiPhong.



Các test case đảm bảo tính đúng đắn của các thuộc tính maPhong và gia.

Hướng dẫn cài đặt





Cài đặt JDK 11 hoặc cao hơn.



Cài đặt Maven để quản lý thư viện.



Sao chép repository: git clone <URL>



Chạy lệnh mvn compile để biên dịch mã nguồn.



Chạy lệnh mvn test để thực hiện kiểm thử.

Công nghệ sử dụng





Ngôn ngữ: Java



Công cụ quản lý thư viện: Maven



Framework kiểm thử: JUnit



IDE đề xuất: IntelliJ IDEA hoặc Eclipse

Thành viên nhóm
Lê Quang Thắng




(Danh sách thành viên nhóm sẽ được cập nhật)

Tài liệu tham khảo





Tài liệu môn học về lập trình hướng đối tượng.



Hướng dẫn sử dụng Maven và JUnit.
