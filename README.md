# Tử Vi Đẩu Số — Lập và luận lá số

Web xem Tử Vi miễn phí: nhập ngày giờ sinh, trang lập lá số 12 cung theo phái Tử Vi Việt Nam và luận giải chi tiết từng cung, đại hạn, năm hạn. Toàn bộ chạy trên trình duyệt, không cần máy chủ hay API.

> Nội dung chỉ mang tính tham khảo.

## Đưa lên GitHub Pages

1. Tạo repository mới trên GitHub (ví dụ `tu-vi`), để chế độ **Public**.
2. Bấm **Add file → Upload files**, kéo thả 3 file `index.html`, `README.md`, `.nojekyll` vào, rồi bấm **Commit changes**.
3. Vào **Settings → Pages**. Ở mục **Build and deployment**, chọn **Source: Deploy from a branch**, Branch: **main**, thư mục **/(root)**, bấm **Save**.
4. Đợi 1–2 phút, trang sẽ chạy tại `https://<tên-tài-khoản>.github.io/tu-vi/`.

Muốn dùng tên miền riêng: vào **Settings → Pages → Custom domain**, nhập tên miền, rồi trỏ DNS (CNAME) về `<tên-tài-khoản>.github.io`.

## Sửa thông tin ủng hộ

Mở `index.html`, tìm `const DONATE=` (gần cuối file) và sửa `bank`, `account`, `owner`, `note`. Ảnh QR nằm ở `qrImage` (dạng base64).
