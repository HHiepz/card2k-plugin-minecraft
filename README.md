<div align="center">

  <img src="assets/logo/card2k.png" alt="logo" width="200" height="auto" />
  
  <p>
    Sản phẩm thuộc sở hữu của Card2K - 2K9XTEAM - Nexus Studio.
  </p>
  
  <!-- Badges -->
  <p>
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
    <a href="https://discord.card2k.com/">Liên hệ hỗ trợ</a>
  <span> · </span>
    <a href="https://discord.card2k.com/">Website kiểm thử</a>
  </h4>
</div>

<!-- Tính năng -->
## 📃 Tính năng

- Nạp thẻ cào
  - Mốc nạp
  - Thống kê
  - Thông báo biển động (discord)

## ✨ Tương thích

- Dùng được cho các server **Spigot** / **Paper** / **Folia** / **Leaf**
- Hỗ trợ Minecraft từ phiên bản **1.12.*** trở lên (đến phiên bản mới nhất)

<!-- Hướng dẫn sử dụng -->
## Hướng dẫn sử dụng

**Cài đặt:**

- Cài đặt plugin [tại đây](https://github.com/hhiepz/card2k-plugin-minecraft/releases)
- Plugin cần có [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/) để hoạt động modules ngoài

**Danh sách lệnh:**

| Lệnh | Mô tả | Quyền |
|------|-------|-------|
| `/napthe <nhà mạng> <mệnh giá> <serial> <code>` | Nạp thẻ | `card2k.use` |
| `/napthe gui` | Mở giao diện nạp thẻ | `card2k.gui` |
| `/napthe reload` | Tải lại cấu hình | `card2k.reload` |
| `/napthe help` | Xem trợ giúp | - |

**Placeholder:**

| Placeholder | Mô tả |
|---------------------|------------|
| `%card2k_total_topup%` | Tổng nạp của người chơi |
| `%card2k_total_topup_global%` | Tổng nạp của toàn server |

### Phần thưởng theo mệnh giá
```yaml
rewards:
  10000:
    - "give %player% diamond 1"
    - "eco give %player% 10000"
```

### Hệ số nhân thưởng
```yaml
reward_multiplier: 2  # Thưởng x2
```

### Mốc nạp tích lũy
```yaml
mocnap:
  enabled: true
  milestones:
    50000:
      - "give %player% diamond 5"
    100000:
      - "give %player% diamond 10"
```

### Discord Webhook
```yaml
discord:
  enabled: true
  webhook_url: "https://discord.com/api/webhooks/..."
```

## Tác giả

- **Nghialonton** – Developer  
  🔗 GitHub: https://github.com/Megumi1608

- **Nexus Studio** – Organization  
  💬 Discord: https://dsc.gg/nexusstudio


## Phát hành & Hỗ trợ

- **Card2K** – Official Support  
  💬 Discord: https://discord.card2k.com
