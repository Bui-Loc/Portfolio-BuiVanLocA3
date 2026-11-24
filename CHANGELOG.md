# Changelog

Mọi thay đổi đáng chú ý của dự án được ghi nhận trong tài liệu này.

## [Chưa phát hành]

### Thêm

- Tạo cấu trúc tài liệu dự án.
- Thêm mô tả dự án và hướng dẫn sử dụng vào `README.md`.
- Thêm danh mục minh chứng vào `evidence-index.md`.
- Thêm nhật ký sử dụng công cụ AI vào `AI_LOG.md`.
- Tạo khung portfolio sinh viên năm nhất trong `Portfolio.html` và `Portfolio.css`.
- Thêm vị trí ảnh avatar và khung giữ chỗ ảnh cho các dự án trong `Portfolio.html`.
- Thêm kiểu hiển thị ảnh avatar dạng tròn và ảnh dự án tỷ lệ 16:9 trong `Portfolio.css`.
- Thêm hiệu ứng xuất hiện, phóng nhẹ khi rê chuột và chuyển động thẻ cho các khu vực ảnh; hỗ trợ tùy chọn giảm chuyển động của hệ điều hành.
- Thêm mục dự án web game đang khởi tạo vào portfolio; ghi rõ các tệp nguồn hiện chưa có nội dung.
- Thêm GitHub Actions workflow để tạo trang chủ từ `Portfolio.html` và triển khai portfolio lên GitHub Pages khi cập nhật nhánh `main`.
- Thay các tệp game trống bằng prototype arcade 2D chơi được, gồm Flappy Boss, Dash Boss, một boss mỗi lượt, khiên, HUD, tạm dừng, âm thanh tùy chọn và lưu điểm cao.
- Thêm bộ sprite PNG đã tách nền gồm người chơi, dạng tiến hóa và bốn boss; dùng ảnh trong game thay cho hình vẽ tạm.
- Thêm ảnh giao diện bắt đầu game ở thẻ dự án web game trên portfolio và liên kết ảnh tới `img/game-start-screen.svg`.
- Thêm bốn ảnh nền boss và chọn ngẫu nhiên nền cho mỗi trận boss.
- Thêm các bậc parkour pixel trong Dash; làm mới cột Flappy và gai Dash để đồng bộ phong cách cảnh nền.
- Thêm đạn nhắm mục tiêu, quạt đạn, loạt đạn và đợt đạn dày; cảnh báo hướng bắn trước khi boss khai hỏa.
- Tăng dần HP, kích thước, tốc độ đạn và tần suất tấn công của bốn boss.
- Đồng bộ nền theo từng chặng từ đường tiếp cận đến trận boss; kéo dài các chặng lần lượt 8, 10, 12 và 14 chướng ngại vật.
- Quy định HP boss tăng chính xác 1,5 lần qua từng trận; tạo chiêu riêng cho từng boss với số đạn và tần suất tấn công tăng dần.
- Thêm hướng dẫn mở/chạy game và mô tả giới hạn prototype vào `README.md`.
- Làm nổi bật liên kết mở game bằng nút “Chơi game ngay” trong thẻ dự án portfolio.

### Cập nhật

- Chuẩn hóa thông tin tác giả, hồ sơ GitHub và liên kết GitHub Pages trong `README.md`.
- Bổ sung liên kết repository chính thức để tra cứu phiên bản, nhánh và commit; cập nhật địa chỉ GitHub Pages sang `Portfolio-BuiVanLocA3`.
- Ghi rõ vai trò chính của sinh viên và phạm vi hỗ trợ của AI trong `AI_LOG.md`.
- Ghi nhận yêu cầu bổ sung ảnh và phân biệt ảnh avatar hiện có với ảnh dự án còn cần bổ sung.
- Cập nhật README, nhật ký AI và danh mục minh chứng để phản ánh đúng trạng thái khởi tạo của dự án web game.
- Cập nhật mục web game trên portfolio từ “đang khởi tạo” thành prototype chơi được và thêm liên kết mở game.
- Làm mới giao diện game theo phong cách pixel với bảng màu sáng, khung đổ khối, thẻ chọn chế độ và phím điều khiển dễ nhận biết; tinh chỉnh menu cho màn hình nhỏ.
- Tối ưu bố cục game theo chiều rộng và chiều cao viewport; giữ tỷ lệ canvas, thu gọn giao diện ở màn hình thấp và đảm bảo menu/tạm dừng vừa khung trên thiết bị di động.
- Thay hình nhân vật bo tròn bằng sprite pixel vẽ trực tiếp trên canvas, có mắt, mỏ, hiệu ứng đuôi lửa và biến thể màu khi có khiên.
- Bổ sung tiến trình bốn boss theo các mốc điểm; thêm vật phẩm tiến hóa để đổi sprite nhân vật sang `player-evolution.png`.
- Giữ ảnh gốc trong `img/` và tạo các bản sprite nền trong suốt trong `img/game-characters/` để game chỉ hiển thị chủ thể.
- Bổ sung nền boss được chọn ngẫu nhiên, bục parkour có thể đáp xuống, chướng ngại pixel chi tiết và nhiều kiểu đạn có hướng di chuyển riêng; HP, kích thước và nhịp độ tấn công tăng theo thứ tự boss.
- Kéo dài đường tiếp cận các boss theo từng chặng, giữ cùng ảnh nền trước và trong trận rồi đổi nền khi sang chặng; HP đặt theo cấp số nhân 1,5x (12, 18, 27, 40,5) và mỗi boss có tên/mẫu chiêu, đường cảnh báo, mật độ đạn và nhịp khai hỏa riêng.
- Cập nhật thẻ dự án trong portfolio để hiển thị ảnh menu bắt đầu game, sửa đường dẫn nút chơi tới `du an game/game.html` và ghi trạng thái prototype đang tiếp tục được cập nhật.
