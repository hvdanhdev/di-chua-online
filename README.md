# 🏯 Đi Chùa Online & Đi Chùa Xõa Stress 3D

Dự án web game 3D tương tác trực tuyến trên trình duyệt (Three.js + Web Audio Synthesizer), bao gồm **2 phiên bản đặt cạnh nhau** để trải nghiệm và so sánh thiết kế UI/UX & Game Design:

1. **[✨ Cổng So Sánh 2 Phiên Bản (`index.html`)](./index.html)**: Trang chủ đối chiếu UI/UX, có chế độ **Chia đôi màn hình (Split-Screen Live 3D)** để trải nghiệm song song.
2. **[🔥 Version 2 (Mới): Đi Chùa Xõa Stress 3D (`chua-xoa-stress/`)](./chua-xoa-stress/index.html)**:
   - **Giao diện Sansa Moonlight UI**: Lấy cảm hứng từ *Sansa Temple* với kính mờ Glassmorphism, bảng màu đêm trăng thanh tịnh, thanh đo mức Stress (`75% → 0% Giác Ngộ!`) và nút chuyển nhạc nhanh.
   - **12 Nhân Vật Chibi 3D (`Naruto × One Piece`)**: Luffy Gear 5, Naruto Tiên Nhân, Zoro, Sasuke, Sanji, Kakashi, Trafalgar Law, Itachi, Ace, Shanks, Minato, Kaido — dựng 100% bằng hình khối 3D kèm vũ khí và hiệu ứng chiêu thức riêng.
   - **3 Khu Vực Xõa Stress 3D Ngay Trong Chánh Điện**:
     - 🎧 **Sàn DJ Ánh Trăng**: Sàn nhảy LED 16 ô nháy theo nhịp bass, bàn DJ 2 mâm xoay, tháp loa Subwoofer, quả cầu gương Hoa Sen & tia Laser 3D (hỗ trợ *Chú Đại Bi Remix 136 BPM*, *Tâm Kinh Lo-Fi Chillhop*, *Trống Giải Phóng Gear 5*).
     - 🥊 **Võ Đài Đấm Bốc Xả Nghiệp**: Treo **5 Bao Cát Nghiệp Chướng 3D** có vật lý lò xo lắc lư (*Deadline Dí*, *Sếp Khó Tính*, *Overthinking*, *Kẹt Xe Giờ Tan Tầm*, *Người Cũ / Crush*).
     - 🥁 **Đại Mõ Neon Phản Lực**: Mõ khổng lồ mạ vàng phát sáng Neon, gõ liên thanh tạo sóng xung kích 3D và tăng cao độ theo chuỗi Combo.
3. **[🪷 Version 1 (Bản Gốc): Đi Chùa Online Truyền Thống (`chua-online/`)](./chua-online/index.html)**:
   - Không gian lễ Phật, dâng hương, tụng kinh, lần chuỗi hạt, ngồi thiền và thả đèn hoa đăng tại 15 ngôi chùa Việt Nam 3D.

---

## 🚀 Cách Chơi & Chia Sẻ

### Cách 1: Chơi trực tiếp trên GitHub Pages (Không cần cài đặt)
Sau khi bật **GitHub Pages**, bạn chỉ cần gửi đường link cho bạn bè:
- Cổng so sánh: `https://<username>.github.io/<ten-repo>/`
- Bản Mới (Đi Chùa Xõa Stress 3D): `https://<username>.github.io/<ten-repo>/chua-xoa-stress/`
- Bản Cũ (Đi Chùa Online Truyền Thống): `https://<username>.github.io/<ten-repo>/chua-online/`

### Cách 2: Mở trực tiếp trên máy tính (`file:///`)
Tải thư mục về máy và click đúp trực tiếp vào `index.html` hoặc `chua-xoa-stress/index.html` (đã tích hợp bộ nạp `file-bundle.js` không cần server).

### Cách 3: Chạy Server Multiplayer (`Node.js`)
Nếu muốn chạy máy chủ WebSocket đồng bộ nhiều người chơi thời gian thực:
```bash
node server.js
# Mở http://localhost:3000
```
Nếu bạn chỉnh sửa mã nguồn trong `js/` hoặc `data/`, chạy lệnh sau để đóng gói lại `file-bundle.js`:
```bash
npm run build
```
