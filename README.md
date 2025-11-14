<div align="center">

  <img src="assets/logo/card2k.png" alt="logo" width="200" height="auto" />
  <h1>CARD2K PLUGIN MINECRAFT</h1>
  
  <p>
    Plugin Minecraft hỗ trợ nạp thẻ cào lên website.
  </p>
  
  <!-- Badges -->
  <p>
    <a href="https://github.com/hhiepz/card2k-plugin-minecraft/network/members">
      <img src="https://img.shields.io/github/forks/hhiepz/card2k-plugin-minecraft" alt="forks" />
    </a>
    <a href="https://github.com/hhiepz/card2k-plugin-minecraft/stargazers">
      <img src="https://img.shields.io/github/stars/hhiepz/card2k-plugin-minecraft" alt="stars" />
    </a>
    <a href="https://github.com/hhiepz/card2k-plugin-minecraft/issues/">
      <img src="https://img.shields.io/github/issues/hhiepz/card2k-plugin-minecraft" alt="open issues" />
    </a>
    <a href="https://github.com/hhiepz/card2k-plugin-minecraft/issues/">
      <img src="https://img.shields.io/github/v/release/hhiepz/card2k-plugin-minecraft?style=flat" alt="release" />
    </a>
    <a href="https://discord.card2k.com/">
      <img src="https://img.shields.io/discord/1068941579244539904.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2" alt="discord" />
    </a>
  </p>
   
<h4>
    <a href="https://card2k.com/">Website gửi thẻ</a>
  <span> · </span>
    <a href="https://discord.card2k.com/">Báo cáo lỗi</a>
  <span> · </span>
    <a href="https://discord.card2k.com/">Yêu cầu thêm tính năng</a>
  </h4>
</div>

<!-- Tính năng -->
## 📃 Tính năng

- Nạp thẻ tự động
- Thống kê tổng nạp theo: ngày / tháng / năm / ngày cụ thể
- Placeholder hiện tổng nạp
- Tự động chuyển dữ liệu từ plugin thesieutoc

## ✨ Tương thích

- Dùng được cho các server **Spigot** và **Paper**
- Hỗ trợ Minecraft từ phiên bản **1.13** trở lên (đến phiên bản mới nhất)

<!-- Hướng dẫn sử dụng -->
## Hướng dẫn sử dụng

**Cài đặt:**

- Cài đặt plugin [tại đây](https://github.com/hhiepz/card2k-plugin-minecraft/releases)
- Plugin cần có [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/) để hoạt động

**Danh sách lệnh:**

| Lệnh                             | Mô tả                                 | Quyền        |
|----------------------------------|---------------------------------------|--------------|
| `/napthe`                        | Mở menu click nạp thẻ                 | Người chơi   |
| `/card2kadmin reload`            | Tải lại cấu hình plugin               | Chủ server   |
| `/card2kadmin migrate`           | Chuyển dữ liệu từ plugin thesieutoc   | Chủ server   |
| `/card2kadmin view <thời gian>`  | Xem thống kê nạp thẻ theo thời gian   | Chủ server   |

**Placeholder:**

| Placeholder         | Mô tả      |
|---------------------|------------|
| `%card2k_total%`    | Tổng nạp   |

**Cấu trúc file plugin:**

```
Card2K/
├── card2k.db
├── main-config.yml
├── message-config.yml
├── milestone-config.yml
```

> - `card2k.db`: File lưu trữ toàn bộ dữ liệu nạp thẻ (database).
> - `main-config.yml`: File cấu hình chính để điều chỉnh các thiết lập của plugin.
> - `message-config.yml`: File chứa các thông báo, tin nhắn gửi tới người chơi.
> - `milestone-config.yml`: File cấu hình các mốc nạp và phần thưởng tương ứng cho người chơi.
