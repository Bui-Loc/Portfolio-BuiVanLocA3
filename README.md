# Portfolio - Bùi Văn Lộc

Trang portfolio cá nhân giới thiệu thông tin, mục tiêu học tập và các dự án công nghệ của Bùi Văn Lộc.

## Tác giả

- Họ và tên: Bùi Văn Lộc
- Hồ sơ GitHub: [github.com/Bui-Loc](https://github.com/Bui-Loc)
- Facebook: [facebook.com/morganlef4y](https://www.facebook.com/morganlef4y)
- Email: [rokkudark@gmail.com](mailto:rokkudark@gmail.com)
- Điện thoại: [0934 288 498](tel:+84934288498)
- Nơi lưu trữ phiên bản và các phân nhánh phiên bản,commit: [https://github.com/Bui-Loc/Portfolio-BuiVanLocA3.git]
- Trang GitHub Pages: [https://bui-loc.github.io/Portfolio-BuiVanLocA3/]

## Giới thiệu

Portfolio được xây dựng để trình bày hồ sơ cá nhân, kỹ năng, định hướng nghề nghiệp và sản phẩm của tác giả. Nội dung được tổ chức ngắn gọn, trực quan và dễ tiếp cận trên cả máy tính và thiết bị di động.

## Mục tiêu

- Tập trung phát triển kỹ năng lập trình web với HTML, CSS và JavaScript.
- Xây dựng các dự án thực hành có bố cục rõ ràng và giao diện thân thiện.
- Lưu trữ, theo dõi và cập nhật tiến độ học tập thông qua Git và GitHub.

## Cấu trúc dự án

- `Portfolio.html`: Nội dung chính của trang portfolio.
- `Portfolio.css`: Kiểu dáng và bố cục của trang.
- `img/avatar.jpg`: Ảnh đang được dùng cho avatar.
- `img/`: Thư mục lưu ảnh avatar và ảnh minh họa dự án.
- `img/portfolio-preview.jpg` và các ảnh `img/portfolio-preview-{violet,ocean,sunset}.jpg`: Ảnh chụp portfolio theo bốn chủ đề màu, luân phiên ngẫu nhiên trong thẻ dự án cá nhân.
- `img/game-start-screen.svg`: Ảnh giao diện bắt đầu game hiển thị tại thẻ dự án trong portfolio.
- `img/game-characters/`: Sprite PNG nhân vật và bốn boss đã tách nền, được game nạp trực tiếp.
- `img/game-backgrounds/`: Bốn ảnh nền được chọn ngẫu nhiên trong các màn boss.
- `du an game/game.html` và `du an game/game.css`: Prototype web game arcade 2D; mở `game.html` để chơi.
- `README.md`: Mô tả tổng quan và hướng dẫn sử dụng dự án.
- `CHANGELOG.md`: Lịch sử các thay đổi.
- `evidence-index.md`: Danh mục minh chứng cho quá trình thực hiện.
- `AI_LOG.md`: Ghi nhận quá trình sử dụng công cụ AI hỗ trợ.

## Cách xem dự án

### Xem trực tiếp

Mở file `Portfolio.html` bằng trình duyệt.

### Xem trên GitHub Pages

Trang được tự động triển khai từ nhánh `main` của repository [Portfolio-BuiVanLocA3](https://github.com/Bui-Loc/Portfolio-BuiVanLocA3) bằng GitHub Actions tại [bui-loc.github.io/Portfolio-BuiVanLocA3](https://bui-loc.github.io/Portfolio-BuiVanLocA3/). Workflow đóng gói portfolio, ảnh và game để các liên kết trên website đều dùng được.

### Chạy bằng máy chủ cục bộ

Tại thư mục dự án, mở terminal và chạy:

```bash
python -m http.server 8000
```

Sau đó truy cập `http://localhost:8000/Portfolio.html`.

## Thay ảnh

- Thay ảnh avatar bằng cách đặt ảnh mới tại `img/avatar.jpg` hoặc cập nhật đường dẫn `src` của thẻ ảnh trong `Portfolio.html`.
- Bốn ảnh chụp portfolio tại `img/portfolio-preview.jpg` và `img/portfolio-preview-{violet,ocean,sunset}.jpg` tự chuyển ngẫu nhiên trong thẻ dự án. Với ảnh dự án khác, thêm ảnh vào thư mục `img` và cập nhật thẻ `<img>` cùng nội dung `alt` trong phần dự án của `Portfolio.html`.

## Công nghệ

- HTML5
- CSS3
- Git và GitHub
- GitHub Pages

## Tương tác giao diện portfolio

Trên thanh điều hướng, chọn một trong bốn bảng màu (tím, đại dương, hoàng hôn, tận thế dung nham đỏ-đen); lựa chọn được lưu trên trình duyệt. Nội dung xuất hiện theo nhịp khi cuộn; các nút, thẻ, kỹ năng, dòng thời gian, khu vực liên hệ và điều hướng có hiệu ứng tương tác riêng. Toàn bộ sáu sprite trong `img/game-characters/` (player, player-evolution và bốn boss) lần lượt bay vào màn hình với kích thước nhỏ, né con trỏ, rồi tự di chuyển. Trong mỗi lượt chỉ một cặp sprite đấu nhau; các sprite còn lại tránh xa khu vực giao tranh. Mỗi nhân vật có 12 điểm máu và một kỹ năng pixel riêng (tia pixel, tam tiễn, ảnh trảo, cầu lửa, hổ trảo, bão dung nham); tên kỹ năng, đạn, vệt cào ba đường và hiệu ứng trúng đòn đều hiển thị rõ. Nhân vật bị hạ có thể xuất hiện lại. Người xem cũng có thể kéo-thả hoặc nhấn sprite để tạo vụ nổ pixel. Các chuyển động tuân theo thiết lập giảm chuyển động của thiết bị.

Mỗi chủ đề có hiệu ứng ánh sáng nền chuyển động riêng và biểu tượng động đặc trưng: tia sao cho tím, sóng cho đại dương, mặt trời cho hoàng hôn và hơi nóng cho dung nham.

## Dự án web game

Mở `du an game/game.html` trực tiếp bằng trình duyệt để chơi. Trang game hiển thị tràn màn hình theo viewport, không có khung/tiêu đề ngoài; menu, HUD và nút âm thanh vẫn dùng được. Trên điện thoại, game đề nghị xoay ngang và tự yêu cầu khóa hướng khi trình duyệt hỗ trợ; nếu không, game vẫn chơi được ở hướng hiện tại và giữ đúng tỷ lệ 16:9. Có thể chạy máy chủ cục bộ từ thư mục dự án:

```bash
python -m http.server 8000
```

Sau đó truy cập `http://localhost:8000/du%20an%20game/game.html`.

Prototype hiện có hai chế độ, chướng ngại vật pixel, bậc parkour trong Dash và ba boss thường xuất hiện lần lượt ở ba chặng đầu. Các chặng tiếp cận boss kéo dài lần lượt 10, 15, 20 và 25 giây; tốc độ, mật độ chướng ngại và độ khó tăng dần. Trên đường đến boss có xu vàng để nhặt; mỗi xu cộng 10 điểm. Ảnh nền được chọn riêng cho mỗi chặng; sàn, chướng ngại và bục Dash dùng bảng màu tương ứng với nền. Ba boss thường có HP 12, 18 và 27; mỗi boss có chiêu riêng, gồm đòn cào rộng với vùng nguy hiểm đỏ và vùng an toàn xanh xuất hiện ngẫu nhiên trong tầm di chuyển kịp theo thời gian cảnh báo. Dùng `A`/`D` hoặc phím mũi tên trái/phải để di chuyển vào vùng xanh, `Space`/`W`/mũi tên lên để bay hoặc nhảy, `I` để bắn và `J` để né.

Chặng cuối là chuỗi bốn boss hợp thể có lần lượt 100, 600, 1.100 và 1.600 HP; mỗi phát bắn thường gây đúng 1 sát thương. Sau hiệu ứng kết hợp, một boss khổng lồ có hình dạng ngẫu nhiên xuất hiện với 100.000 HP, lớp khiên định kỳ chặn đạn và các kiểu tấn công của cả bốn boss. Mỗi boss có năm đòn đánh vùng riêng; boss di chuyển né đòn, nhịp và mật độ tấn công tăng dần theo cấp, đặc biệt dày ở dạng khổng lồ. Sát thương mỗi đòn của boss thường tăng theo thứ tự (1, 2, 3...), bốn boss hợp thể gây lần lượt 1–4 sát thương, còn boss khổng lồ gây 15 sát thương mỗi lần trúng. Mọi đòn đánh vùng đều báo trước ô xanh miễn sát thương được đặt trong tầm di chuyển kịp theo thời gian cảnh báo. Lõi tiến hóa cầu vồng lấp lánh trong chặng này rất hiếm; lần đầu nhặt hồi/tăng máu lên 10 tim, mỗi viên đạn cầu vồng gây 36 sát thương và bắn nhanh hơn, thêm kiếm khí, bay tự do bằng `WASD`/phím mũi tên hoặc cụm nút 4 hướng trên điện thoại, cùng tia sáng toàn màn hình gây 1.000 sát thương mỗi 4 giây. Nhặt lõi này lần nữa hồi tối đa 2 máu. Ở các chặng khác, lõi tiến hóa tăng 3 máu tối đa/hiện tại, mở đạn lốc xoáy; nhặt lại hồi tối đa 2 máu. Game có bắn tự động/nhấn `I`, né bằng `J` (lướt nhanh, miễn sát thương 0,42 giây, hồi chiêu 1,35 giây), hiệu ứng hạt, âm thanh tùy chọn, tạm dừng và lưu kỷ lục cục bộ. Bảng xếp hạng ảo cho Flappy và Dash so sánh kỷ lục cao nhất của người chơi với ba đối thủ mô phỏng; đây không phải bảng online, còn kỷ lục cá nhân lưu trong trình duyệt. Ảnh giao diện bắt đầu dùng tại portfolio nằm ở `img/game-start-screen.svg`; ảnh nhân vật ở `img/game-characters/`, ảnh nền boss ở `img/game-backgrounds/`. Trên điện thoại, nút né `J` xuất hiện trong trận boss cùng các nút trái/phải khi cần; nếu có tiến hóa cầu vồng sẽ có thêm cụm bay 4 hướng. Prototype vẫn đang được cập nhật.
