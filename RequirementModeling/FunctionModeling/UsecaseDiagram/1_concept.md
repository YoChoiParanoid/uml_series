# Concept
## System Boundary

- Là đường biên xác định phạm vi của hệ thống, cho biết những gì thuộc về hệ thống và những gì nằm ngoài hệ thống.

- Các thành phần bên trong System Boundary là các chức năng, quy trình và dữ liệu thuộc hệ thống.

- Các đối tượng bên ngoài System Boundary (không thuộc hệ thống) nhưng có tương tác với hệ thống được gọi là Actor.

## Actor
### Khái niệm


- Actor là bất kỳ thực thể nào (con người, phần mềm, phần cứng) tương tác với hệ thống để thực hiện một chức năng nhất định.

- Actor không thuộc hệ thống, nhưng có vai trò kích hoạt hoặc nhận phản hồi từ hệ thống.

### Cách xác định Actor
- Ý 1
    - Một Actor có thể đại diện cho một cá nhân hoặc một nhóm người cùng thực hiện một vai trò.

    - Actor cũng có thể là một hệ thống khác tương tác với hệ thống chính thông qua API hoặc giao tiếp dữ liệu.

    - Ví dụ: trong hệ thống Quản lý đăng ký môn học, các Actor có thể là:
        - Sinh viên (Đăng ký môn học, xem thời khóa biểu)

        - Giảng viên (Xem danh sách sinh viên, nhập điểm)

        - Hệ thống thanh toán (kiểm tra và xác nhận học phí)

- Ý 2
    - Một người dùng có thể đóng nhiều vai trò khác nhau tùy vào quyền hạn của họ.

    - Ví dụ:
        - Một Giảng viên có thể vừa là Người nhập điểm, vừa là Cố vấn học tập kiểm tra lịch sử đăng ký của sinh viên.

- Ý 3
    - Nếu nhiều người có cùng quyền và thực hiện cùng chức năng, ta có thể gom họ vào một Actor chung.

    - Ví dụ: Trong hệ thống Quản lý thư viện, các Actor có thể là:
        - Người mượn sách (gồm sinh viên, giảng viên, nhân viên).

        - Nhân viên thư viện (quản lý kho sách, duyệt yêu cầu mượn).

- Ý 4
    - Mỗi nhóm người dùng (Actor) có thể sử dụng một hoặc nhiều chức năng trong hệ thống

    - Ví dụ:
        - Sinh viên có thể
            - Tra cứu sách

            - Đặt mượn sách

            - Gia hạn sách

        - Nhân viên thư viện có thể:

            - Quản lý sách

            - Xác nhận mượn sách

            - Kiểm tra vi phạm

- Ý 5
    - Một chức năng không nhất thiết chỉ dành cho một Actor mà có thể dùng chung.
    
    - Ví dụ:
        - Chức năng "Tra cứu tài liệu" có thể dùng bởi Sinh viên, Giảng viên, Nhân viên.

- Ý 6
    - Nếu nhiều nhóm người dùng có cùng vai trò, ta có thể gom lại và xem họ như một Actor chung.

    - Ví dụ:
        - Trong hệ thống Quản lý bán hàng, Nhân viên kho và Nhân viên bán hàng có thể cùng có quyền "Kiểm tra tồn kho".

- Ý 7
    - Khi thiết kế hệ thống, cần xác định rõ các Actor bằng cách phân tích luồng công việc thực tế.

    - Ví dụ: Trong hệ thống Quản lý bệnh viện, cần xem xét các Actor như:
        - Bệnh nhân (đặt lịch khám, tra cứu kết quả).

        - Bác sĩ (xem hồ sơ bệnh án, nhập kết quả khám).

        - Nhân viên kế toán (xử lý thanh toán, xuất hóa đơn).

        - Hệ thống bảo hiểm (kiểm tra quyền lợi bảo hiểm).