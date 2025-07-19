# Overlio Landing Page

Đây là landing page cho tên miền **overlio.com** - Hệ thống Live Scoreboard chuyên nghiệp.

## 📁 Cấu trúc thư mục

```
landing/
├── index.html          # Trang chủ landing page
├── assets/             # Thư mục chứa hình ảnh
│   ├── admin-panel.png
│   ├── cards-overlay.png
│   ├── goal-overlay.png
│   ├── lineup-away.png
│   ├── lineup-home.png
│   ├── lineup-overlay.png
│   ├── replay-overlay.png
│   ├── scoreboard-overlay.png
│   └── substitution-overlay.png
├── favicon.ico         # Icon website
├── manifest.json       # PWA manifest
├── robots.txt          # SEO robots
├── sitemap.xml         # SEO sitemap
└── README.md           # File này
```

## 🚀 Cách sử dụng

### 1. Upload lên hosting
- Upload toàn bộ nội dung thư mục `landing/` lên thư mục gốc của domain `overlio.com`
- Đảm bảo file `index.html` nằm ở thư mục gốc

### 2. Cấu hình domain
- Trỏ domain `overlio.com` về hosting
- Cấu hình SSL certificate cho HTTPS
- Đảm bảo tất cả assets load được

### 3. SEO Optimization
- File đã được tối ưu SEO với meta tags
- Open Graph tags cho social media
- Twitter Card tags
- Canonical URL
- Sitemap và robots.txt

## 🎨 Tính năng

- ✅ **Responsive Design** - Tương thích mọi thiết bị
- ✅ **Modern UI** - Giao diện đẹp mắt, chuyên nghiệp
- ✅ **Interactive Cards** - Click để xem preview overlay
- ✅ **Mobile Menu** - Menu hamburger cho mobile
- ✅ **SEO Optimized** - Tối ưu cho search engines
- ✅ **PWA Ready** - Progressive Web App support
- ✅ **Fast Loading** - Tối ưu performance

## 📱 Preview Overlays

Trang có các card tương tác để preview các overlay:
- 📊 Bảng Điểm Chính
- 👥 Đội Hình Thi Đấu  
- 🏠 Đội Nhà
- 🛫 Đội Khách
- 🟡 Thẻ Phạt
- ⚽ Bàn Thắng
- 🔄 Thay Người
- 🎬 Video Replay
- 🏢 Nhà Tài Trợ

## 🔧 Customization

### Thay đổi màu sắc
Chỉnh sửa CSS variables trong `index.html`:
```css
:root {
    --primary: #667eea;
    --secondary: #764ba2;
    /* ... */
}
```

### Thêm overlay mới
1. Thêm ảnh vào thư mục `assets/`
2. Thêm card mới trong HTML
3. Cập nhật JavaScript function `showOverlayImage()`

## 📞 Support

- **Website:** https://overlio.com
- **Email:** support@overlio.com
- **Version:** 2.0

---

© 2025 Overlio - Live Scoreboard System 