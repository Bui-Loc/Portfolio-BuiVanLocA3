# Portfolio - Bùi Văn Lộc

Trang portfolio cá nhân giới thiệu thông tin, mục tiêu học tập và các dự án công nghệ của Bùi Văn Lộc.

## Tác giả

- Họ và tên: Bùi Văn Lộc
- Hồ sơ GitHub: [github.com/Bui-Loc](https://github.com/Bui-Loc)
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

Trang được triển khai từ repository [Portfolio-BuiVanLocA3](https://github.com/Bui-Loc/Portfolio-BuiVanLocA3) tại [bui-loc.github.io/Portfolio-BuiVanLocA3](https://bui-loc.github.io/Portfolio-BuiVanLocA3/).

### Chạy bằng máy chủ cục bộ

Tại thư mục dự án, mở terminal và chạy:

```bash
python -m http.server 8000
```

Sau đó truy cập `http://localhost:8000/Portfolio.html`.

## Thay ảnh

- Thay ảnh avatar bằng cách đặt ảnh mới tại `img/avatar.jpg` hoặc cập nhật đường dẫn `src` của thẻ ảnh trong `Portfolio.html`.
- Thêm ảnh dự án vào thư mục `img`, rồi thay khung giữ chỗ trong `Portfolio.html` bằng thẻ `<img>` mẫu ở ngay phần dự án. Cập nhật `src` và nội dung `alt` cho đúng ảnh.

## Công nghệ

- HTML5
- CSS3
- Git và GitHub
- GitHub Pages

## Dự án web game

Mở `du an game/game.html` trực tiếp bằng trình duyệt để chơi, hoặc chạy máy chủ cục bộ từ thư mục dự án:

```bash
python -m http.server 8000
```

Sau đó truy cập `http://localhost:8000/du%20an%20game/game.html`.

Prototype hiện có hai chế độ, chướng ngại vật pixel, bậc parkour trong Dash và bốn boss xuất hiện lần lượt ở ba chặng đầu. Ảnh nền được chọn riêng cho mỗi chặng, đồng bộ từ đoạn đường tiếp cận đến trận boss và đổi khi sang chặng mới. Các chặng tăng độ dài từ 8 đến 14 chướng ngại vật; tốc độ, mật độ chướng ngại và độ khó tăng dần. HP boss theo tỷ lệ 1,5 lần boss trước (12, 18, 27, 40,5); mỗi boss có chiêu đặc trưng, tần suất tung đòn và số đạn tăng dần, kèm vùng cảnh báo trước khi bắn. Chặng cuối là đại chiến đồng thời cả bốn boss với thanh máu tổng, các đòn bắn nhắm người chơi và nhiều biến thể tấn công của boss cuối. Trong trận cuối, vật phẩm xuất hiện mỗi 3,2 giây gồm tiến hóa, khiên, hồi 1 máu, thêm tối đa 1 máu (giới hạn 6) và tăng 50% sát thương trong 12 giây; các chặng trước giữ nhịp xuất hiện vật phẩm cũ. Game có bắn tự động/nhấn `F`, hiệu ứng hạt, âm thanh tùy chọn, tạm dừng và lưu kỷ lục cục bộ. Ảnh giao diện bắt đầu dùng tại portfolio nằm ở `img/game-start-screen.svg`; ảnh nhân vật ở `img/game-characters/`, ảnh nền boss ở `img/game-backgrounds/`. Prototype vẫn đang được cập nhật.
