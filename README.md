*   **Docker, docker-compose là gì?**
    *   **Docker:** Một nền tảng mã nguồn mở để phát triển, vận chuyển và chạy ứng dụng. Nó cho phép bạn tách biệt ứng dụng khỏi cơ sở hạ tầng bằng cách đóng gói phần mềm vào các "container" tiêu chuẩn. Điều này giúp tăng tốc quá trình tạo, kiểm thử và triển khai ứng dụng.
    *   **Docker Compose:** Một công cụ của Docker dùng để định nghĩa và chạy các ứng dụng đa-container. Nó sử dụng một tệp YAML duy nhất (`docker-compose.yml`) để cấu hình tất cả các dịch vụ, mạng và ổ đĩa cần thiết cho ứng dụng, giúp đơn giản hóa việc triển khai và quản lý các ứng dụng phức tạp.

*   **Linux vs Unix vs BSD hay *nix? macOS thuộc loại nào?**
    *   **Unix:** Là một hệ điều hành đa nhiệm, đa người dùng, được phát triển lần đầu vào năm 1969. Nó nổi tiếng về tính di động, hiệu quả và ổn định. Unix là nền tảng ban đầu cho nhiều hệ điều hành hiện đại.
    *   **Linux:** Là một hệ điều hành mã nguồn mở dựa trên nhân Linux (được Linus Torvalds phát triển năm 1991). Linux được lấy cảm hứng từ Unix và thường được gọi là một "Unix-like" (giống Unix) hoặc "Unix-compliant" (tương thích Unix) nhưng không phải là Unix chính thức.
    *   **BSD (Berkeley Software Distribution):** Cũng là một hệ điều hành "Unix-like" khác, được phát triển từ mã nguồn của Unix tại Đại học California, Berkeley. Các biến thể phổ biến bao gồm FreeBSD, OpenBSD, NetBSD. BSD có một lịch sử phát triển độc lập và khác biệt so với Linux, mặc dù cả hai đều có nguồn gốc từ Unix.
    *   ***nix:** Là một thuật ngữ chung, không chính thức, dùng để chỉ tất cả các hệ điều hành giống Unix (Unix-like), bao gồm cả Linux, BSD và chính Unix. Nó là một cách gọi ngắn gọn cho "Unix và các hệ thống tương tự Unix".
    *   **macOS thuộc loại nào?** macOS (trước đây là OS X) là một hệ điều hành **Unix-certified** (được chứng nhận Unix). Nhân của macOS, được gọi là Darwin, dựa trên nhân XNU, vốn kết hợp Mach kernel và các thành phần từ FreeBSD. Vì vậy, macOS là một hệ điều hành thuộc họ Unix-like và tuân thủ các tiêu chuẩn của Unix.

*   **Alpine vs Ubuntu?**
    *   **Alpine Linux:** Là một bản phân phối Linux rất nhỏ, nhẹ và tập trung vào bảo mật. Nó sử dụng thư viện `musl libc` và `BusyBox` thay vì `glibc` và `GNU coreutils` thông thường, làm cho kích thước ảnh (image size) cực kỳ nhỏ. Alpine rất phổ biến trong môi trường Docker và container vì nó giúp giảm kích thước container, tăng tốc độ khởi động và giảm bề mặt tấn công.
    *   **Ubuntu:** Là một bản phân phối Linux phổ biến và thân thiện với người dùng, dựa trên Debian. Nó được biết đến với cộng đồng lớn, nhiều gói phần mềm và dễ sử dụng cho cả người dùng desktop và máy chủ. Ubuntu sử dụng `glibc` và các công cụ GNU truyền thống.
    *   **Điểm khác biệt chính:** Kích thước, thư viện tiêu chuẩn, và mục đích sử dụng. Alpine nhỏ gọn và lý tưởng cho container, còn Ubuntu linh hoạt hơn, có nhiều tính năng và phù hợp với nhiều trường hợp sử dụng hơn.

*   **VNC**
    *   **VNC (Virtual Network Computing):** Là một hệ thống đồ họa từ xa (remote display system) cho phép bạn điều khiển màn hình máy tính khác từ xa. Nó truyền tải các sự kiện bàn phím và chuột từ một máy tính đến một máy tính khác, đồng thời hiển thị màn hình đồ họa của máy tính từ xa lên máy tính cục bộ của bạn. VNC hữu ích cho việc hỗ trợ từ xa, quản trị máy chủ không có màn hình vật lý, hoặc truy cập máy tính của bạn từ bất cứ đâu.
