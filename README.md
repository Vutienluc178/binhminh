# Phòng Khám Sản Phụ Khoa – BS CKII Lê Đàm Vân

Website tĩnh chuẩn SEO, responsive. Có thể deploy trên **GitHub Pages** hoặc **Vercel**.

## Cấu trúc
- `index.html` (Trang chủ) — chứa hero, dịch vụ, form đặt lịch, blog, liên hệ.
- `about.html`, `contact.html`
- `dich-vu/*.html` — 5 trang dịch vụ SEO riêng.
- `assets/img/*` — ảnh placeholder, logo, ảnh Open Graph.
- `robots.txt`, `sitemap.xml`

## Tuỳ chỉnh nhanh
- Tìm `https://formspree.io/f/your-id` trong `index.html` để thay endpoint form.
- Thay `https://example.com` trong `sitemap.xml` và thẻ `canonical` theo domain thực tế.
- Thay ảnh thật trong `assets/img` (giữ nguyên tên file để khỏi sửa HTML).

## Deploy GitHub Pages
1. Tạo repo mới, kéo thả toàn bộ thư mục lên.
2. Vào **Settings → Pages → Deploy from branch**: chọn branch `main`, folder `/root`.
3. Chờ build xong. Website sẽ có URL: `https://<username>.github.io/<repo>/`

## Deploy Vercel
1. Import repo trên vercel.com (Project → New → Import Git Repository).
2. Framework: **Other** (static). Output = root (mặc định).
3. Deploy và gán custom domain (nếu có).

## SEO Note
- Giữ tiêu đề/description ngắn gọn (≤ 60/160 ký tự).
- Viết bài blog đều đặn, mỗi bài ≥ 600 từ, dùng heading H2–H3 hợp lý.
- Nén ảnh thực tế dưới 200–300 KB nếu có thể.
