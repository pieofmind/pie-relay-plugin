# Pie Relay

Cộng tác thời gian thực trong Obsidian với thư mục nhóm, chạy trên server tự host. Đây là bản fork của [EVC Team Relay Obsidian Plugin](https://github.com/entire-vc/evc-team-relay-obsidian-plugin) (MIT, © Entire VC), xem [LICENSE](LICENSE).

**Cần có server Pie Relay riêng và tài khoản trên server đó.** Plugin gửi nội dung các thư mục được share tới server này; không có server thì plugin không làm gì.

Khác với upstream:
- Share lồng nhau: một thư mục con có thể là share riêng, nằm trong một share lớn hơn.
- Lần đầu một máy vào share thì cấu trúc trên server thắng. File cũ chỉ có trên máy được dời vào `_Pie Relay - bản cũ/<ngày>/…`, không đẩy lên, không xoá.
- Viewer chỉ đọc: không ghi hay xoá được trên server.

## Cài đặt qua BRAT

1. Trong Obsidian: **Settings → Community plugins → Browse**, tìm **BRAT** (Obsidian42 - BRAT), cài và bật.
2. **Settings → BRAT → Add beta plugin**, dán `pieofmind/pie-relay-plugin`, chọn phiên bản mới nhất, bấm **Add plugin**.
3. Bật **Pie Relay** trong Community plugins, đăng nhập vào server của nhóm.

BRAT tự kiểm tra và cập nhật bản mới khi mở Obsidian (bật **Auto-update plugins at startup** trong cài đặt BRAT).
