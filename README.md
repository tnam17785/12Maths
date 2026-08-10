# 12Maths

Website tĩnh học **Toán lớp 12** với giao diện hiện đại, nền particle chuyển động chuyên nghiệp.

**Live demo (sau khi bật GitHub Pages):**  
https://tnam17785.github.io/12Maths/

## Tính năng

- Giao diện tối (dark theme) đẹp, màu indigo + cyan + gold
- Nền particle network chuyển động mượt
- Responsive (mobile + desktop)
- Cấu trúc đa trang dễ mở rộng
- Menu navigation sẵn sàng thêm trang mới

## Cấu trúc thư mục

```
12Maths/
├── index.html          # Trang chủ
├── ham-so.html         # Hàm số & Đạo hàm
├── tich-phan.html      # Tích phân
├── so-phuc.html        # Số phức
├── hinh-hoc.html       # Hình học không gian
├── xac-suat.html       # Xác suất & Thống kê
├── css/
│   └── style.css
├── js/
│   └── main.js
└── README.md
```

## Cách thêm trang mới

1. Tạo file HTML mới (ví dụ `luong-giac.html`) theo mẫu các trang hiện có.
2. Copy header + footer + link CSS/JS từ trang sẵn có.
3. Thêm link vào menu navigation ở **tất cả** các trang:

```html
<a href="luong-giac.html" class="nav-link">Lượng giác</a>
```

4. (Tùy chọn) Thêm card mới vào phần "Chuyên đề" ở `index.html`.

Chỉ cần đặt tên file đúng và cập nhật menu là xong!

## Bật GitHub Pages

1. Vào repo → **Settings** → **Pages**
2. Source: Deploy from a branch
3. Branch: `main` / root
4. Save → đợi 1-2 phút

## Công nghệ

- HTML5 + CSS3 (pure)
- Vanilla JavaScript (particle background)
- Google Fonts (Inter + Playfair Display)

---

© 2026 12Maths
