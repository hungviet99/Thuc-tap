# HTTP Cookie , Session, Cache 

## Cookie 

Cookie là phần dữ liệu được web server gửi vào lần đầu tiên trình duyệt truy cập website hoặc khi không tìm thấy trong requests của trình duyệt gửi lên. Sau đó cookie được lưu lại trên trình duyệt của máy người dùng. cookie đó sẽ được trình duyệt gửi lại server theo mọi requests

Cookie thường được set bỏi trình duyệt nhưng nó cũng có thể được tạo ra hoặc thao tác bởi client bằng việc sử dụng JS. Tuy nhiên, nếu các cookie được gắn http only thì chỉ server có quyền thao tác đến các cookie này. 

## Session 

Là Là 1 khái niệm phổ biến được dùng trong lập trình web có kết nối database. Đặc biệt các chức năng như đăng nhập, đăng xuất, người dùng sẽ khó có thể thực hiện được nếu không sử dụng session. 

Một session bắt đầu khi client gửi request đến server, nó tồn tại xuyên suốt từ trang này đến trang khác trong ứng dụng web và chỉ kết thúc khi hết thời gian timeout hoặc khi bạn đóng ứng dụng. Giá trị của session sẽ được lưu trong một file trên server.