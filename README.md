# Gun-Sus 2D 🎮

Một trò chơi 2D platformer hành động được phát triển bằng **Unity** với các tính năng AI thông minh, hệ thống chiến đấu, và gameplay hấp dẫn.

---

## ✨ Tính Năng

- ✅ **Nhân vật có thể điều khiển**: Chuyển động mượt mà, nhảy, tấn công
- ✅ **AI Kẻ thù thông minh**: Sử dụng A* pathfinding để theo dõi người chơi
- ✅ **Hệ thống chiến đấu**: Cơ chế tấn công và phòng thủ
- ✅ **Hệ thống vật phẩm**: Nhặt vật phẩm để tăng cường năng lực
- ✅ **Quản lý sức khỏe**: UI trực quan với thanh máu
- ✅ **Nhạc và âm thanh nền**: Âm thanh bắn súng, nhảy, nhặt vật phẩm
- ✅ **Nhiều cảnh chơi**: Menu, chọn bản đồ, gameplay chính
- ✅ **Cơ chế tăng tốc độ**: Boost sức mạnh chiến đấu tạm thời

---

## 🎮 Cách Chơi

### Điều khiển
- **Mũi tên Trái/Phải** (←/→): Di chuyển nhân vật
- **Mũi tên Lên** (↑): Nhảy
- **Phím khác**: Tấn công/Hành động

### Mục tiêu
- Tiêu diệt tất cả kẻ thù trên bản đồ
- Thu thập vật phẩm để tăng cường năng lực
- Tồn tại sống sót với máu còn lại

---

## 📋 Cấu Trúc Dự Án

```
Gun-Sus-2D/
├── Assets/
│   ├── Scenes/              # Các cảnh chơi
│   │   ├── Menu.unity       # Menu chính
│   │   ├── chonmap.unity    # Chọn bản đồ
│   │   └── choi.unity       # Gameplay chính
│   ├── Scripts/             # C# Scripts cho gameplay
│   │   ├── p2.cs            # Điều khiển nhân vật chính
│   │   ├── EnemyAI.cs       # AI của kẻ thù
│   │   ├── UI.cs            # Hệ thống UI
│   │   ├── thanhmau.cs      # Thanh máu
│   │   ├── nhatitem.cs      # Nhặt vật phẩm
│   │   ├── audio.cs         # Quản lý âm thanh
│   │   └── ...
│   ├── audio/               # Tệp âm thanh
│   ├── Sprites/             # Hình ảnh & tài liệu đồ họa
│   └── Prefabs/             # Preset các đối tượng
├── Packages/                # Thư viện Unity
├── ProjectSettings/         # Cài đặt dự án
└── README.md
```

---

## 🛠️ Công Nghệ Sử Dụng

- **Engine**: Unity (2D)
- **Ngôn ngữ**: C#
- **Pathfinding**: A* Pathfinding Project
- **Physics**: Unity 2D Rigidbody
- **UI Framework**: Unity UI (TextMesh Pro)

---

## 📦 Yêu Cầu

- **Unity 2021 LTS** trở lên
- **.NET Framework 4.7.1+**
- Máy tính với GPU hỗ trợ graphics 2D

---

## 🚀 Hướng Dẫn Cài Đặt & Chạy

### 1. Clone Repository
```bash
git clone https://github.com/locjo/Gun-2D.git
cd Gun-2D
```

### 2. Mở dự án trong Unity
- Khởi động **Unity Hub**
- Chọn **Open Project**
- Chọn thư mục `Gun-2D`
- Chờ Unity import assets

### 3. Chạy dự án
- Vào Scene `Menu.unity` hoặc `choi.unity`
- Nhấn **Play** (hoặc Ctrl + P)
- Chơi và kiểm thử

---

## 📝 Các Scripts Chính

| Script | Chức năng |
|--------|----------|
| `p2.cs` | Điều khiển movement, jump, animation của nhân vật chính |
| `EnemyAI.cs` | AI kẻ thù với pathfinding thông minh, follow player |
| `UI.cs` | Quản lý giao diện người dùng |
| `thanhmau.cs` | Render thanh máu của nhân vật |
| `nhatitem.cs` | Xử lý nhặt vật phẩm |
| `roiitem.cs` | Loại bỏ/drop vật phẩm |
| `audio.cs` | Quản lý âm thanh hiệu ứng |
| `phatnhac.cs` | Phát nhạc nền |
| `thoigian.cs` | Quản lý thời gian trò chơi |

---

## 🎨 Tài Sản Sử Dụng

- **Graphics**: Sprite từ các nguồn mở
- **Audio**: 
  - Background music: *Kamen Rider Geats x Revice MOVIE Battle Royale OST*
  - SFX: Gun shoot, Jump, Collect item
  - Sử dụng nhạc có giấy phép hoặc theo Attribution

---

## 🐛 Lỗi Đã Biết & Cải Tiến Trong Tương Lai

### Known Issues
- [ ] Pathfinding có thể bị lag trên bản đồ lớn
- [ ] Animation transition cần tối ưu hóa

### Planned Features
- [ ] Thêm boss cuối cùng
- [ ] Hệ thống cấp độ (leveling)
- [ ] Multiplayer (cùng chơi 2 người)
- [ ] Menu tạm dừng (pause menu)
- [ ] Kỷ lục cao (leaderboard)

---

## 👨‍💻 Nhà Phát Triển

**Tác giả**: [locjo](https://github.com/locjo)

---

## 📄 Giấy Phép

Dự án này được công khai trên GitHub. Vui lòng kiểm tra LICENSE file (nếu có) để biết thêm chi tiết về giấy phép.

---

## 🤝 Đóng Góp

Nếu bạn muốn:
- 🐛 Báo cáo lỗi: Mở một **Issue** trên GitHub
- 💡 Đề xuất tính năng: Tạo **Discussion** hoặc **Issue**
- 🔄 Yêu cầu hợp nhất: Gửi **Pull Request** (hãy mô tả rõ thay đổi của bạn)

---

## 💬 Hỗ Trợ & Liên Hệ

Nếu bạn gặp vấn đề:
1. Kiểm tra [Issues](https://github.com/locjo/Gun-2D/issues)
2. Tìm kiếm giải pháp trong README này
3. Tạo một Issue mới với chi tiết về lỗi

---

## 🎯 Mục Tiêu Dự Án

Dự án này được tạo ra để:
- ✨ Thực hành phát triển game 2D bằng Unity
- 🤖 Học cách triển khai AI & pathfinding
- 🎮 Tạo một trò chơi hấp dẫn cho người chơi

---

**Chúc bạn chơi vui vẻ! 🎮**

Nếu bạn thích dự án này, ⭐ **Star repository** để hỗ trợ nhà phát triển!
