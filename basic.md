- `downgrade attack`
  - Tấn công hạ cấp
  - Là một hình thức tấn công vào hệ thống máy tính hoặc giao thức truyền thông làm cho nó từ bỏ một phương thức hoạt động chất lượng cao (ví dụ như kết nối được mã hóa) để dùng một phương thức hoạt động cũ và kém chất lượng hơn thường được cung cấp cho khả năng tương thích ngược
- `backward compatibility` 
  - tương thích ngược
  - version mới tương thích với các version cũ, nếu không có khả năng tương thích ngược, chương trình hoạt động với một bộ xử lý máy tính hoặc hệ điều hành sẽ ngừng hoạt động với version mới
- `OpenSSL`
  - là một thư viện phần mềm sử dụng các mã nguồn mở để triển khai các giao thức mạng và mã hóa dữ liệu khác nhau như SSL và TLS. OpenSSL được sử dụng trong trường hợp cần xác định phe truyền thống ở phía đầu bên kia hoặc các ứng dụng bảo mật truyền thông qua mạng máy tính để phòng chống nghe trộm
- `SASL: Simple Authentication and Security Layer`
  - Lớp xác thực vào bảo mật đơn giản
  - là một framework cho việc cung cấp 2 dịch vụ cho các protocol hướng kết nối
    - authentication 
    - security layer
- `DNSSEC`
  - DNS security
  - Phần mở rộng bảo mật tên miền, là một tính năng DNS nâng cao thêm một lớp bảo mật phụ cho tên miền bằng cách đính kèm bản ghi chữ số (DS) vào thông tin DNS của chúng
- `soft bounce`
  - Message được chuyển đi nhưng không chuyển đến được người nhận vì một số lý do tạm thời
    + email quá lớn, nội dung quá nặng
    + hộp thư đến của người nhận bị đầy
    + máy chủ email quá tải, không hoạt động
      - => cố gắng gửi lại message
- `hard bounce`
  - message được chuyển đi nhưng không đến được người nhận vì một số lý do:
    - domain email không hợp lệ
    - server nhận không chấp nhận email
    - địa chỉ email sai
      - => hard bounce cao: giảm uy tín
      
