# CV - Middle Frontend Developer

Một mẫu CV chuyên nghiệp được thiết kế cho vị trí Middle Frontend Developer, sử dụng HTML và CSS thuần.

## ✨ Tính năng

- 🎨 Thiết kế hiện đại và chuyên nghiệp
- 📱 Responsive design cho mọi thiết bị
- 🖨️ Tối ưu hóa cho in ấn
- ⚡ Tải trang nhanh với static files
- 🚀 Sẵn sàng deploy lên Vercel

## 🛠️ Công nghệ sử dụng

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- Font Awesome Icons
- Google Fonts (Inter)

## 📁 Cấu trúc dự án

```
cv/
├── index.html          # File HTML chính
├── styles.css          # File CSS styles
├── vercel.json         # Cấu hình Vercel
└── README.md           # File hướng dẫn
```

## 🚀 Deploy lên Vercel

### Cách 1: Deploy trực tiếp từ GitHub

1. Push code lên GitHub repository
2. Truy cập [vercel.com](https://vercel.com)
3. Đăng nhập và chọn "New Project"
4. Import repository từ GitHub
5. Vercel sẽ tự động detect và deploy

### Cách 2: Deploy từ Vercel CLI

```bash
# Cài đặt Vercel CLI
npm i -g vercel

# Login vào Vercel
vercel login

# Deploy
vercel

# Deploy production
vercel --prod
```

## 📝 Tùy chỉnh

### Thay đổi thông tin cá nhân

Chỉnh sửa file `index.html`:

```html
<!-- Thay đổi tên -->
<h1>Nguyễn Văn A</h1>

<!-- Thay đổi thông tin liên hệ -->
<span>nguyenvana@email.com</span>
<span>+84 123 456 789</span>
```

### Thay đổi màu sắc

Chỉnh sửa file `styles.css`:

```css
/* Thay đổi màu chủ đạo */
:root {
  --primary-color: #667eea;
  --secondary-color: #764ba2;
}
```

### Thêm ảnh đại diện

Thay thế icon user bằng ảnh thật:

```html
<div class="avatar">
  <img src="path/to/your/photo.jpg" alt="Profile Photo" />
</div>
```

Và cập nhật CSS:

```css
.avatar img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 50%;
}
```

## 🎯 Các section có sẵn

- **Header**: Thông tin cá nhân và liên hệ
- **Tóm tắt**: Mô tả ngắn gọn về bản thân
- **Kỹ năng kỹ thuật**: Chia theo categories
- **Kinh nghiệm làm việc**: Timeline format
- **Dự án nổi bật**: Grid layout với hover effects
- **Học vấn**: Thông tin bằng cấp
- **Chứng chỉ**: Danh sách certifications
- **Ngoại ngữ**: Trình độ ngôn ngữ

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Tablet**: 768px - 480px
- **Mobile**: < 480px

## 🖨️ Print Styles

CV được tối ưu hóa cho in ấn với:

- Loại bỏ background gradients
- Tối ưu màu sắc cho in
- Layout phù hợp với A4

## 📄 License

MIT License - Tự do sử dụng và chỉnh sửa.

## 🤝 Đóng góp

Mọi đóng góp đều được chào đón! Hãy tạo issue hoặc pull request.

---

**Lưu ý**: Đừng quên cập nhật thông tin cá nhân trước khi deploy!
