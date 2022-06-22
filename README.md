# Databases

## Mục lục
- [1. Database](#database)
- [2. Database Management System](#DBMS)
- [3. Relational Database Management System](#RDBMS)
- [4. Relational Database Modeling](#realationaldatabase)




<a name = "database"></a>
### Database

Cơ sở dữ liệu là nơi lưu trữ tất cả dữ liệu theo định dạng có cấu trúc. Nó giúp người dùng dễ dàng truy cập, quản lý và cập nhật thông tin cần thiết. Một cách tổng quát, bạn có thể hiểu cơ sở dữ liệu được ví như một thùng chứa lớn trong đó chứa tất cả các thông tin liên quan đến một ứng dụng, một website … được lưu trữ theo một cấu trúc định dạng xác định.

<a name = "DBMS" ></a>
### Database Management System

<img src= "https://imgur.com/P3UOwf2">
<img src = "https://imgur.com/nxFrqiC">
Một Hệ thống quản lý cơ sở dữ liệu (Database Management System) gọi tắt là BDMS là một phần mềm có thể thực hiện việc tạo ra, bảo quản và sử dụng cơ sở dữ liệu. BDMS có thể được hiểu như một phần mềm quản lý tập tin hay hồ sơ (File Manager) và công cụ chính của nó là quản lý dữ liệu trong cơ sở dữ liệu chứ không chỉ là chỉ lưu những dữ liệu ấy trên hệ thống.

<a name = "RDBMS" ></a>
### Relational Database Management System

<img src= "https://imgur.com/LRnvLCG">
  
RDBMS là viết tắt cho Hệ thống quản lý cơ sở dữ liệu các mối quan hệ (Relational Database Management System). RDBMS lưu những dữ liệu vào một tập hợp các bảng biểu, thường sẽ có liên kết trong một số lĩnh vực chung nào đó giữa các cột trong bảng biểu đó. Hệ thống này cũng cung cấp cho các những người điều hành có liên quan cách sử dụng những dữ liệu được lưu trong bảng biếu đó. Ví dụ: server SQL

### Relational Database Modeling

Mô hình Dữ liệu là một ký hiệu để mô tả dữ liệu hoặc thông tin. Mô tả thường bao gồm 3 phần:
- Structure of the data.
- Operations on the data.
- Constraints on the data.

Mỗi cột đại diện cho một thuộc tính của Project và còn được gọi là "attribute"
Tên của một mối quan hệ và tập hợp các thuộc tính cho mối quan hệ đó được gọi là "schemas" (lược đồ)
Một row-hàng của một mối quan hệ được gọi là tuple (hoặc record)

``` 
Table = relation.
Column headers = attributes.
Row = tuple
Relation schema = name(attributes) + other structure info.,e.g., keys, other constraints! 
```


