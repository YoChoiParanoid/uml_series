# Mối quan hệ giữa các Actor
- Trong một hệ thống, các Actor có thể có mối quan hệ với nhau. Các loại quan hệ bao gồm:

    - Quan hệ kế thừa (`<<generalization>>`):

        - Một Actor có thể kế thừa từ một Actor khác nếu Actor con có đầy đủ chức năng của Actor cha, đồng thời có thể bổ sung thêm chức năng riêng.
        
        - Ví dụ:

            - "Khách hàng VIP" kế thừa từ "Khách hàng thông thường" vì họ có tất cả các quyền của khách hàng thông thường nhưng có thêm ưu đãi đặc biệt.

# Mối quan hệ giữa các Use Case
- Các Use Case cũng có thể có mối quan hệ với nhau nhằm biểu diễn sự liên kết giữa các chức năng trong hệ thống.

### Quan hệ `<<generalization>>` giữa các Use Case
- Nếu nhiều Use Case có chức năng tương tự, chúng có thể được tổng quát hóa bằng một Use Case chung.

- Use Case tổng quát sẽ đại diện cho các chức năng chung, còn Use Case con có thể mở rộng hoặc tùy chỉnh thêm.

- Ví dụ:

    - Đăng nhập có thể có các Use Case con:

        - Đăng nhập qua số điện thoại
        
        - Đăng nhập qua email
        
    - Thanh toán có thể có các Use Case con:

        - Thanh toán qua ATM

        - Thanh toán qua thẻ quốc tế

        - Thanh toán qua ví điện tử

### Quan hệ `<<include>>` giữa các Use Case
-  Dùng để chia một Use Case lớn thành nhiều Use Case nhỏ để tái sử dụng hoặc làm cho hệ thống dễ quản lý hơn.

- Use Case tách riêng được gọi là Included Use Case và được sử dụng trong các Use Case khác.

- Tính bắt buộc: Một Use Case luôn luôn phải thực hiện Included Use Case khi được kích hoạt.

- Ví dụ:

    - Khi khách hàng đặt hàng, hệ thống sẽ tự động kiểm tra kho

    - Khi khách hàng đăng ký tài khoản, hệ thống sẽ gửi email xác nhận

    - Khi khách hàng thanh toán, hệ thống sẽ tính toán thuế

- Biểu diễn:

    - Đường nét đứt

    - Hình tam giác rỗng

    - Mũi tên trỏ về Use Case được sử dụng (Included Use Case)

    - Ghi `<<includes>>`

### Quan hệ `<<extends>>` giữa các Use Case
- Được sử dụng khi có một Use Case được tạo ra để bổ sung chức năng cho một Use Case có sẵn

- Dùng để mô tả các hành vi mở rộng, không bắt buộc phải có trong Use Case chính.

- Một Use Case chính có thể hoạt động độc lập mà không cần đến Use Case mở rộng.

- Ví dụ:

    - Khi khách hàng đặt hàng, hệ thống có thể đề xuất sản phẩm liên quan (không bắt buộc).

    - Khi khách hàng tìm kiếm sản phẩm, hệ thống có thể gợi ý tìm kiếm nâng cao (không bắt buộc).

    - Khi khách hàng hủy đơn hàng, hệ thống có thể đề xuất chương trình giảm giá (không bắt buộc).

- Biểu diễn:

    - Đường nét đứt

    - Hình tam giác rỗng

    - Mũi tên trỏ về Use Case chính

    - Ghi `<<extends>>`

# Mối quan hệ giữa Actor và Use Case
### Quan hệ Association (Kết nối trực tiếp)
- Mô tả sự tương tác trực tiếp giữa Actor và Use Case.

- Một Actor có thể tham gia vào nhiều Use Case, và một Use Case có thể được thực hiện bởi nhiều Actor.

- Ví dụ:

    - Khách hàng có thể tìm kiếm sản phẩm, đặt hàng, thanh toán.

    - Nhân viên giao hàng có thể xác nhận giao hàng.

    - Nhân viên kho có thể kiểm tra tồn kho.

### Quan hệ kế thừa (Generalization) giữa Actor và Use Case
- Nếu có nhiều Actor có chung một số chức năng nhưng có sự khác biệt, ta có thể tổng quát hóa chúng thành một Actor cha.

- Ví dụ:

    - Người dùng (User) có thể bao gồm Khách hàng và Quản trị viên.

    - Khách hàng VIP kế thừa từ Khách hàng thông thường nhưng có thêm các quyền lợi đặc biệt.