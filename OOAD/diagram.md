# UML và Diagram
UML 2.0 cung cấp 14 loại biểu đồ, được chia thành 2 nhóm chính:
    - Biểu đồ mô hình hóa cấu trúc (Structural Diagrams)

    - Biểu đồ mô hình hóa chức năng (Behavioral Diagrams)

## Nhóm 1: Biểu đồ mô hình hóa cấu trúc (Structural Diagrams)
- Các biểu đồ trong nhóm này mô tả các thành phần tĩnh của hệ thống.

### Class Diagram (Biểu đồ lớp)
- Mô tả cấu trúc hệ thống thông qua các lớp (class) và mối quan hệ giữa chúng.

- Chứa các thành phần:

    - Class (Lớp): Đại diện cho một thực thể trong hệ thống.

    - Attributes (Thuộc tính): Mô tả dữ liệu bên trong lớp.

    - Methods (Phương thức): Các hành động mà lớp có thể thực hiện.

    - Relationships (Quan hệ): Mối quan hệ giữa các lớp (kế thừa, kết hợp, liên kết, phụ thuộc).

### Object Diagram (Biểu đồ đối tượng)
- Giống Class Diagram, nhưng mô tả các đối tượng cụ thể tại một thời điểm nhất định.

- Giúp kiểm tra hệ thống trong runtime.

### Package Diagram (Biểu đồ gói)
- Mô tả cách tổ chức các module trong hệ thống.

- Giúp phân nhóm các lớp thành từng gói (package).

### Component Diagram (Biểu đồ thành phần)
- Mô tả cấu trúc phần mềm và cách các thành phần giao tiếp với nhau.

- Thường dùng để mô tả các module hoặc microservices.

### Deployment Diagram (Biểu đồ triển khai)
- Mô tả cách hệ thống được triển khai trên phần cứng hoặc cloud.

- Bao gồm máy chủ, thiết bị mạng, kết nối giữa chúng.

### Composite Structure Diagram (Biểu đồ cấu trúc phức hợp)
- Mô tả cấu trúc bên trong của một lớp hoặc một thành phần.

- Sử dụng khi cần chi tiết về cấu trúc nội bộ của các phần trong hệ thống.

## Nhóm 2: Biểu đồ mô hình hóa chức năng (Behavioral Diagrams)
- Các biểu đồ trong nhóm này tập trung vào các hành vi động của hệ thống.

### Use Case Diagram (Biểu đồ Use Case)
- Mô tả các trường hợp sử dụng của hệ thống.

- Giúp xác định ai (actors) sử dụng hệ thống và hệ thống cung cấp những chức năng gì.

### Activity Diagram (Biểu đồ hoạt động)
- Mô tả luồng công việc hoặc quy trình xử lý trong hệ thống.

- Thường dùng để biểu diễn luồng nghiệp vụ hoặc thuật toán.

### Sequence Diagram (Biểu đồ tuần tự)
- Mô tả cách các đối tượng tương tác theo trình tự thời gian.

- Mỗi thành phần (object) được biểu diễn bằng một đường dọc.

- Dòng message (tin nhắn) giữa các đối tượng thể hiện sự tương tác.

### Collaboration Diagram (Biểu đồ cộng tác)
- Tương tự Sequence Diagram, nhưng tập trung vào cấu trúc giao tiếp giữa các đối tượng thay vì thứ tự thời gian.

### State Diagram (Biểu đồ trạng thái)
- Mô tả các trạng thái khác nhau của một đối tượng trong hệ thống và cách nó chuyển đổi giữa các trạng thái.

- Ví dụ: Một đơn hàng có thể có các trạng thái Đang xử lý -> Đã giao hàng -> Hoàn thành.

### Timing Diagram (Biểu đồ thời gian)
- Giống Sequence Diagram, nhưng tập trung vào thời gian thay đổi trạng thái của các đối tượng.

### Interaction Overview Diagram (Biểu đồ khái quát tương tác)
- Kết hợp giữa Activity Diagram và Sequence Diagram, giúp mô tả các luồng điều khiển trong hệ thống.

### Protocol State Machine (Biểu đồ trạng thái giao thức)
- Một dạng đặc biệt của State Diagram, mô tả các quy tắc giao tiếp giữa các đối tượng theo giao thức.