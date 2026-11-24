# Nhật ký sử dụng AI

## Thông tin chung

- Sinh viên thực hiện: Bùi Văn Lộc
- Vai trò: Tác giả và người chịu trách nhiệm chính cho bài tập lớn
- Công cụ hỗ trợ: GitHub Copilot
- Ngôn ngữ: Tiếng Việt
- Ngày cập nhật: 24/11/2026

## Phân công và đóng góp

Tôi là người thực hiện chính và chịu trách nhiệm về nội dung, lựa chọn cuối cùng, việc chỉnh sửa và hoàn thiện bài làm. Tôi sử dụng AI như công cụ hỗ trợ theo yêu cầu của mình; nội dung do AI gợi ý không thay thế việc tôi tự rà soát, cá nhân hóa và hiểu sản phẩm trước khi nộp.

| Người thực hiện | Công việc |
|---|---|
| Tôi (Bùi Văn Lộc) | Xác định đây là portfolio cá nhân phục vụ bài tập lớn giữa kỳ, nêu bối cảnh sinh viên năm nhất và yêu cầu nội dung phù hợp trình độ đang học. |
| Tôi (Bùi Văn Lộc) | Chọn tiếng Việt, cung cấp thông tin tác giả và hồ sơ GitHub; xem xét kết quả, yêu cầu điều chỉnh và quyết định nội dung nào được giữ lại. |
| Tôi (Bùi Văn Lộc) | Yêu cầu bổ sung vị trí có thể chèn ảnh chân dung/avatar và ảnh minh họa cho từng dự án; xác định đây là cập nhật tiếp theo của portfolio. |
| Tôi (Bùi Văn Lộc) | Yêu cầu thêm hiệu ứng động cho các khu vực có thể gán ảnh. |
| Tôi (Bùi Văn Lộc) | Tạo/định hướng dự án web game trong thư mục `du an game` và yêu cầu ghi nhận dự án tại các mục báo cáo tương ứng. |
| Tôi (Bùi Văn Lộc) | Yêu cầu xuất bản portfolio lên GitHub Pages. |
| Tôi (Bùi Văn Lộc) | Cập nhật README với liên kết repository để tra cứu phiên bản/nhánh/commit và địa chỉ GitHub Pages theo tên repository `Portfolio-BuiVanLocA3`. |
| Tôi (Bùi Văn Lộc) | Đưa ra yêu cầu thiết kế game “SKY & RHYTHM: BOSS RUSH” với hai chế độ arcade và chỉ định đây là bản đầu tiên còn sơ khai, chưa cần hoàn thiện mọi tính năng nâng cao. |
| Tôi (Bùi Văn Lộc) | Yêu cầu thêm liên kết có thể nhấn từ thẻ dự án trên portfolio để mở trò chơi. |
| Tôi (Bùi Văn Lộc) | Yêu cầu cải tiến giao diện game theo hướng thân thiện và phong cách pixel. |
| Tôi (Bùi Văn Lộc) | Yêu cầu giao diện game thích nghi với màn hình thiết bị, không dư thừa hoặc tràn khỏi vùng nhìn thấy. |
| Tôi (Bùi Văn Lộc) | Yêu cầu bổ sung và báo cáo ảnh nhân vật game theo phong cách pixel. |
| Tôi (Bùi Văn Lộc) | Cung cấp ảnh `boss1.png`–`boss4.png`, `player.png` và `player-evolution.png`; yêu cầu thêm bốn boss, đổi ảnh người chơi khi ăn vật phẩm tiến hóa và chỉ hiển thị chủ thể, không lấy nền. |
| Tôi (Bùi Văn Lộc) | Chịu trách nhiệm bổ sung thông tin cá nhân, ảnh và dự án thật, kiểm tra liên kết, rà soát nội dung và hoàn thiện sản phẩm cuối cùng trước khi nộp. |
| GitHub Copilot | Hỗ trợ soạn bản nháp README, changelog, danh mục minh chứng và nhật ký AI theo yêu cầu. |
| GitHub Copilot | Tạo khung ban đầu cho `Portfolio.html` và `Portfolio.css`, gồm các khu vực phổ biến của portfolio và bố cục đáp ứng màn hình. |
| GitHub Copilot | Theo yêu cầu của tôi, thêm thẻ ảnh avatar dùng `img/avatar.jpg`, khung giữ chỗ ảnh dự án cùng ví dụ đường dẫn và CSS để hiển thị/cắt ảnh. |
| GitHub Copilot | Theo yêu cầu của tôi, thêm hiệu ứng xuất hiện và tương tác rê chuột cho avatar, ảnh/khung ảnh dự án; tôn trọng cài đặt giảm chuyển động. |
| GitHub Copilot | Ghi nhận dự án web game trong portfolio và tài liệu dự án; kiểm tra thấy `game.html` và `game.css` đang rỗng nên đánh dấu là đang khởi tạo, chưa có chức năng chơi. |
| GitHub Copilot | Thêm workflow GitHub Actions để tạo `index.html` từ `Portfolio.html`, đưa CSS/ảnh vào gói triển khai và xuất bản GitHub Pages từ nhánh `main`. |
| GitHub Copilot | Viết prototype trong `du an game/game.html` và `game.css`: vòng lặp `requestAnimationFrame` có delta time, hai chế độ, chướng ngại vật, boss telegraph một kiểu đạn, tự bắn/nhấn `F`, khiên, máu, hạt, rung màn hình, Web Audio tùy chọn, pause và high score bằng localStorage. |
| GitHub Copilot | Làm nút “Chơi game ngay” trong thẻ dự án trỏ tới `du an game/game.html` bằng liên kết tương đối để mở game cùng dự án. |
| GitHub Copilot | Làm mới CSS giao diện game với màu sắc thân thiện, viền và bóng đổ dạng pixel; bổ sung phím tắt dạng keycap và tinh chỉnh menu để hiển thị phù hợp trên màn hình nhỏ. |
| GitHub Copilot | Điều chỉnh bố cục theo kích thước viewport, giữ tỷ lệ khung game, giảm phần phụ ở màn hình thấp và thu gọn overlay/menu/HUD trên điện thoại để tránh tràn khỏi vùng nhìn thấy. |
| GitHub Copilot | Thêm sprite nhân vật pixel vẽ bằng các ô màu trên canvas, kèm đuôi lửa chuyển động và hiệu ứng màu/khiên khi nhặt vật phẩm; không phụ thuộc tệp ảnh bên ngoài. |
| GitHub Copilot | Tách nền caro khỏi sáu ảnh được cung cấp, lưu sprite nền trong suốt trong `img/game-characters/`, gắn ảnh cho người chơi và bốn boss, thêm vật phẩm tiến hóa cùng tiến trình lần lượt qua bốn boss. |

## Nội dung AI hỗ trợ trong phiên làm việc

- Đề xuất cấu trúc trang gồm giới thiệu, thông tin cá nhân, kỹ năng đang học, dự án, hành trình học tập và liên hệ.
- Soạn mã HTML/CSS ban đầu để minh họa cấu trúc và giao diện.
- Thêm vị trí ảnh cho avatar và ảnh dự án; các khung dự án hiện là chỗ giữ chỗ, chưa phải ảnh dự án thật.
- Prototype game có giao diện pixel thích nghi màn hình; đã kiểm tra menu, HUD và màn tạm dừng ở các cỡ điện thoại, desktop và landscape, không thấy trang tràn ngang/dọc.
- Nhân vật và boss trong game dùng sprite PNG đã tách nền; vật phẩm tiến hóa đổi sprite người chơi từ `player.png` sang `player-evolution.png`.
- README hiện có thông tin nơi lưu trữ phiên bản và địa chỉ Pages mới; các liên kết cần được kiểm tra khi đổi tên repository hoặc cấu hình xuất bản.
- Prototype có bốn boss theo lượt và vật phẩm tiến hóa; power-up ngoài khiên/tiến hóa, nhiều mẫu tấn công, phá chướng ngại vật và cân bằng nâng cao chưa được làm.
- Gợi ý nội dung mẫu phù hợp với portfolio của sinh viên năm nhất làm bài tập giữa kỳ.
- Cập nhật các tài liệu dự án,báo cáo lên các mục .

## Kiểm tra và trách nhiệm

- Bản HTML/CSS do AI hỗ trợ tạo là khung ban đầu; các khung ảnh dự án chưa có ảnh thật, và nội dung mẫu không phải bằng chứng rằng tôi đã hoàn thành các kỹ năng hoặc dự án đó.
- Tôi cần bổ sung ảnh và nội dung sản phẩm có thật; kiểm tra hiển thị, đường dẫn và tính chính xác trước khi công bố.
- Không ghi tỷ lệ phần trăm đóng góp vì chưa có cách đo lường đáng tin cậy. Tôi giữ vai trò chủ động và chịu trách nhiệm cuối cùng về toàn bộ bài nộp.
