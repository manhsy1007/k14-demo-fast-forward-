1. API là 
- API cung cấp công cụ giao tiếp dữ liệu hệ thống với giao diện người dùng
- Định dang: xml, json
- Những trường hợp call nhiều API thì nên test API để test logic nằm bên dưới thay vì test trên giao diện rất nhiều case
2. API components
- http
- https: có mã hóa
- Request
    - URL
        - Base URL
        - Endpoint
        - Parameter ( nêu có param thì sẽ có payload)
            - Đầu tiên: ?
            - Từ thứ 2: &
    - Method
    - Headers
    - Body
- Response
    - Status code    
        - 1xx: Phản hồi thông tin
            - 101: Switching protocol.
        - 2xx: Thành công
            - 200: OK
            - 201: Created
        - 3xx: chuyển hướng
            - 301, 302: Redirected
        - 4xx: lỗi liên quan đến người dùng
            - 400: Bad Request
            - 404: Not Found
        - 5xx: lỗi hệ thống
            - 500: Internal Server Error
            - 502: Bad Gateway    
    - Header
    - Body
- API document: tài liệu chuẩn cho API