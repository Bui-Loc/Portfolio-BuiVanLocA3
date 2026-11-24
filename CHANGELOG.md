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
- Chụp ảnh giao diện portfolio chủ đề tận thế dung nham và dùng làm ảnh minh họa dự án cá nhân.
- Thêm kiểu hiển thị ảnh avatar dạng tròn và ảnh dự án tỷ lệ 16:9 trong `Portfolio.css`.
- Thêm chuyển động nổi nhẹ, vòng quỹ đạo, ánh sáng nhấp nháy và hiệu ứng nâng/phóng khi rê chuột hoặc focus bàn phím cho avatar.
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
- Thêm trận đại chiến cuối với cả bốn boss cùng hiện diện và tấn công; boss cuối luân phiên bắn vòng đạn, quạt đạn nhắm mục tiêu và loạt đạn tập trung.
- Thêm vật phẩm hồi máu, tăng máu tối đa, tăng 50% sát thương trong 12 giây; tăng nhịp xuất hiện vật phẩm ở trận cuối lên mỗi 3,2 giây.
- Thêm bộ chọn bốn bảng màu cho portfolio và lưu lựa chọn trên thiết bị.
- Thêm hiệu ứng xuất hiện khi cuộn, chuyển động nhẹ cho thẻ kỹ năng và các nhân vật pixel ngẫu nhiên có thể nhấn để tạo vụ nổ hạt pixel.
- Thu nhỏ nhân vật pixel nổi trên trang và cho phép kéo-thả bằng chuột hoặc cảm ứng; sau khi thả, nhân vật tiếp tục tự di chuyển.
- Cho nhân vật pixel xuất hiện từ ngoài mép màn hình và đổi hướng tránh con trỏ khi con trỏ đến gần.
- Tăng hiệu ứng chuyển động/hover xuyên suốt các mục portfolio: điều hướng, tiêu đề, nút, thẻ thông tin/kỹ năng/dự án, dòng thời gian, liên hệ và chân trang.
- Khắc phục nhân vật pixel đứng yên khi bật giảm chuyển động; giờ vẫn di chuyển chậm hơn và né con trỏ nhẹ nhàng.
- Tăng bán kính nhận biết con trỏ và lực/tốc độ né của các nhân vật pixel để chúng phản ứng nhanh hơn.
- Hiển thị đủ sáu sprite player/player-evolution/boss; thu nhỏ hơn, cho nhân vật tự đấu bằng đạn pixel khi chạm và thêm hiệu ứng cào, trúng đòn, hồi sinh.
- Kéo dài các trận đấu sprite bằng cách tăng máu, cho phép tấn công khi ở gần và thêm sáu bộ kỹ năng pixel riêng, có nhãn kỹ năng, loại đạn và hiệu ứng trúng đòn riêng biệt.
- Thay bảng màu bạc hà bằng chủ đề tận thế dung nham đỏ-đen; tự chuyển thiết lập đã lưu trước đây từ bạc hà sang chủ đề mới.
- Giới hạn mỗi lượt chỉ một cặp sprite giao chiến, các sprite còn lại tránh khu vực đấu; thu nhỏ thêm sprite và làm vệt cào ba đường sáng, có hướng cùng hiệu ứng va chạm.
- Sửa lỗi hạ mục tiêu bằng đòn cào làm dừng vòng lặp hoạt ảnh; giữ sprite tiếp tục bay vào từ ngoài màn hình và chỉ cào khi ở gần.
- Tăng độ tương phản của thẻ liên hệ trong chủ đề dung nham bằng nền đỏ đen tối và màu chữ nút dễ đọc.

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
- Cập nhật trận cuối để chỉ chiến thắng sau khi hạ đủ cả bốn boss; thanh HP hiển thị tổng máu nhóm boss, HUD thể hiện máu hiện tại/tối đa và thời gian buff sát thương.
- Tôn trọng thiết lập giảm chuyển động của hệ điều hành trong các hiệu ứng trang và chuyển động nhân vật pixel.
