# Project Sekai Stickers

<p align="center">
  <a href="https://github.com/mcsstudio/sekai-stickers">
    <img src="./public/og-image.png" alt="Project Sekai Stickers" width="200" height="200">
  </a>
</p>

<h2 align="center"><b>Project Sekai Stickers</b></h2>

<p align="center">
  Một ứng dụng web hiện đại và thân thiện với người dùng, giúp bạn thỏa thích xem, sao chép và tải xuống các sticker cực dễ thương từ Project Sekai!
  <br />
  <br />
  <a href="https://github.com/mcsstudio/sekai-stickers/issues">Báo cáo lỗi (Report Bug)</a>
  ·
  <a href="https://github.com/mcsstudio/sekai-stickers/issues">Đề xuất tính năng (Request Feature)</a>
</p>

## Giới thiệu

Đây là phiên bản được phát triển dựa trên mã nguồn mở của ứng dụng Project Sekai Stickers gốc. Dự án đã được tối ưu hóa lại giao diện (UI/UX), nâng cao hiệu suất tải trang và bổ sung thêm nhiều tính năng tiện ích cho người dùng.

## <img src="https://cdn.discordapp.com/emojis/859424401186095114.png" width="20px" height="20px"> Tính năng nổi bật

- [x] Wonderhoy!
- [x] Miku dayo!
- [x] Tải xuống và sao chép sticker
- [x] Giao diện chuẩn responsive (tương thích với điện thoại và máy tính)
- [x] Tối ưu hóa hiệu suất và khả năng truy cập (accessibility)
- [ ] Chia sẻ lên mạng xã hội

## <img src="https://cdn.discordapp.com/emojis/1028680849195020308.png" width="25px" height="25px"> Hình ảnh minh họa

<p align="center">
  <img src="public/screenshot.png" alt="Ảnh chụp màn hình ứng dụng" width="100%">
</p>

## 🧪 Kiểm thử tự động (Automated Testing)

Dự án đi kèm với một script sử dụng **Playwright** để tự động kiểm tra khả năng hiển thị (responsiveness) của giao diện trên nhiều kích thước màn hình khác nhau (từ Desktop 1920px đến Mobile 320px).

Để chạy bài test, bạn cần cài đặt Playwright và chạy lệnh sau:

```bash
npm install -D playwright
npx playwright install chromium
node test-responsive.mjs
```

Script sẽ tự động chụp ảnh màn hình ở các chế độ khác nhau và quét các lỗi về giao diện (nút quá nhỏ, tràn màn hình, đè chữ, v.v.) và lưu vào thư mục `screenshots/`.

## ✨ Ghi nhận đóng góp (Credits)

Dự án này sẽ không thể hoàn thiện nếu thiếu đi những đóng góp từ cộng đồng:
- Hình ảnh sticker gốc từ [Reddit](https://www.reddit.com/r/ProjectSekai/comments/x1h4v1/after_an_ungodly_amount_of_time_i_finally_made/)
- Hình ảnh được cắt (cropped) bởi [Modder4869](https://github.com/Modder4869)
- Trang web gốc được phát triển bởi [TheOriginalAyaka](https://github.com/TheOriginalAyaka)
- Được phát triển và bảo trì bởi [BedrockDigger](https://github.com/BedrockDigger)
- **Việt hóa, tùy biến và phát triển phiên bản này bởi [mcsstudio](https://github.com/mcsstudio)**

## 🔐 Giấy phép (License)

Dự án được phân phối dưới giấy phép MIT License. Xem chi tiết tại file [`LICENSE`](https://github.com/mcsstudio/sekai-stickers/blob/main/LICENSE).
Dự án này chưa được build, vui lòng build thủ công.

[contributors-shield]: https://img.shields.io/github/contributors/mcsstudio/sekai-stickers.svg?style=for-the-badge
[contributors-url]: https://github.com/mcsstudio/sekai-stickers/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/mcsstudio/sekai-stickers.svg?style=for-the-badge
[forks-url]: https://github.com/mcsstudio/sekai-stickers/network/members
[stars-shield]: https://img.shields.io/github/stars/mcsstudio/sekai-stickers.svg?style=for-the-badge
[stars-url]: https://github.com/mcsstudio/sekai-stickers/stargazers
[issues-shield]: https://img.shields.io/github/issues/mcsstudio/sekai-stickers.svg?style=for-the-badge
[issues-url]: https://github.com/mcsstudio/sekai-stickers/issues
[license-shield]: https://img.shields.io/github/license/mcsstudio/sekai-stickers.svg?style=for-the-badge
[license-url]: https://github.com/mcsstudio/sekai-stickers/blob/main/LICENCE
