# Góc nhìn
- Mô hình này phân chia hệ thống thành 5 góc nhìn chính, mỗi góc nhìn không thể hiện hết hệ thống, nhưng thể hiện rõ hệ thống ở một khía cạnh cụ thể

## Use Case View (Góc nhìn trường hợp sử dụng)
- Mục đích: Giúp hiểu hệ thống có gì, ai sử dụng và cách sử dụng hệ thống như thế nào.

- Vai trò: Tập trung vào yêu cầu của hệ thống từ góc độ người dùng.

- Đặc điểm:

    - Mô tả các chức năng chính của hệ thống.

    - Định nghĩa các tác nhân (actors) và cách họ tương tác với hệ thống.

- Ví dụ sơ đồ: Use Case Diagram (Sơ đồ trường hợp sử dụng).

## Logical View (Góc nhìn logic)
- Mục đích: Cung cấp góc nhìn về chức năng của hệ thống.

- Vai trò: Tập trung vào cấu trúc lớp và mối quan hệ giữa các thành phần trong hệ thống.

- Đặc điểm:

    - Xây dựng mô hình lớp (Class Model) để mô tả các đối tượng và quan hệ của chúng.

    - Định nghĩa cách hệ thống hoạt động từ góc độ lập trình.

- Ví dụ sơ đồ: Class Diagram (Sơ đồ lớp), Object Diagram (Sơ đồ đối tượng).

## Process View (Góc nhìn tiến trình)
- Mục đích: Mô tả cách các thành phần trong hệ thống tương tác với nhau trong thời gian chạy.

- Vai trò: Cung cấp góc nhìn động về hệ thống.

- Đặc điểm:

    - Giúp phân tích hiệu suất, tính sẵn sàng, khả năng chịu lỗi.

    - Mô tả các tiến trình chạy song song, cơ chế giao tiếp giữa các tiến trình.

- Ví dụ sơ đồ: Sequence Diagram (Sơ đồ trình tự), Activity Diagram (Sơ đồ hoạt động), State Diagram (Sơ đồ trạng thái).

## Component View (Góc nhìn thành phần)
- Mục đích: Cung cấp góc nhìn về cấu trúc giúp hiểu cách phân bổ và sử dụng lại các thành phần phần mềm.

- Vai trò: Tập trung vào cách hệ thống được chia thành các module hoặc thành phần riêng biệt.

- Đặc điểm:

    - Mô tả các thành phần phần mềm và cách chúng kết nối với nhau.

    - Giúp quản lý phần mềm, tăng khả năng tái sử dụng và bảo trì.

- Ví dụ sơ đồ: Component Diagram (Sơ đồ thành phần).

## Deployment View (Góc nhìn triển khai)
- Mục đích: Mô tả cách hệ thống được triển khai trên phần cứng.

- Vai trò: Ảnh hưởng đến kiến trúc hệ thống, hiệu suất và khả năng mở rộng.

- Đặc điểm:

    - Xác định cách các thành phần phần mềm được triển khai trên các máy chủ vật lý hoặc cloud.

    - Ảnh hưởng đến hiệu suất, tính sẵn sàng, khả năng chịu lỗi, khả năng mở rộng.

- Ví dụ sơ đồ: Deployment Diagram (Sơ đồ triển khai).