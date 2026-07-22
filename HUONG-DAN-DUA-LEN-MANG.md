# Hướng dẫn đưa blog lên mạng — miễn phí, không cần cài gì

> Làm một lần, khoảng **15 phút**. Không cần biết code, không cần cài phần mềm.
> Sau khi xong anh sẽ có địa chỉ web thật dạng `https://tên-của-anh.github.io`

---

## Blog này gồm những gì

```
blog/
├── _config.yml        ← tên blog (sửa được)
├── _layouts/
│   └── default.html   ← giao diện (đừng đụng)
├── index.md           ← TRANG CHỦ
└── best-sensory-friendly-school-shoes-2026.md   ← BÀI VIẾT (4.920 chữ)
```

**Anh chỉ cần sửa 2 file `.md`.** Đó là file văn bản thường, mở bằng Notepad cũng được.

---

## BƯỚC 1 — Tạo tài khoản GitHub (5 phút)

1. Vào **https://github.com/signup**
2. Nhập email, đặt mật khẩu
3. **Chọn tên đăng nhập cẩn thận** — tên này sẽ nằm trong địa chỉ web của anh.
   Ví dụ chọn `elinaharts` → web sẽ là `https://elinaharts.github.io`
   → Nên chọn tên gắn với thương hiệu, đừng chọn tên ngẫu nhiên.
4. Xác nhận email
5. Chọn gói **Free**

---

## BƯỚC 2 — Tạo kho chứa (3 phút)

1. Đăng nhập xong, bấm dấu **➕** góc trên bên phải → **New repository**
2. Ô **Repository name**, gõ **chính xác**:
   ```
   tên-đăng-nhập-của-anh.github.io
   ```
   Ví dụ tên đăng nhập là `elinaharts` thì gõ `elinaharts.github.io`
   ⚠️ Phải đúng y như vậy, kể cả phần `.github.io` — sai là không chạy.
3. Chọn **Public** (bắt buộc, bản miễn phí)
4. **Không** tích ô "Add a README file"
5. Bấm **Create repository**

---

## BƯỚC 3 — Tải file lên (5 phút)

Không cần cài Git. Kéo thả bằng trình duyệt là được.

1. Trong kho vừa tạo, bấm dòng chữ **"uploading an existing file"**
   (hoặc vào **Add file** → **Upload files**)
2. Mở thư mục `blog` trên máy anh
3. **Chọn hết mọi thứ bên TRONG thư mục `blog`** — gồm:
   - `_config.yml`
   - thư mục `_layouts`
   - `index.md`
   - `best-sensory-friendly-school-shoes-2026.md`

   ⚠️ Kéo **những thứ bên trong** thư mục blog, **không phải** kéo cả thư mục `blog` vào.
4. Kéo thả vào ô trên trình duyệt
5. Kéo xuống dưới, bấm nút xanh **Commit changes**

---

## BƯỚC 4 — Đợi 2 phút rồi mở web

1. Đợi khoảng **2 phút** (GitHub cần thời gian dựng trang)
2. Mở địa chỉ: **`https://tên-đăng-nhập-của-anh.github.io`**
3. Nếu thấy trang chủ hiện ra → **xong**

**Nếu chưa thấy gì:** vào tab **Settings** → mục **Pages** ở cột trái → xem phần
"Your site is live at…". Nếu báo lỗi, chụp màn hình gửi tôi.

---

## BƯỚC 5 — Dán vào TikTok

Có địa chỉ web rồi:

1. Mở **app TikTok trên điện thoại** (không làm được trên máy tính)
2. Hồ sơ → **Sửa hồ sơ** → ô **Trang web** (Website)
3. Dán `https://tên-của-anh.github.io`
4. **Lưu**

---

## Sau này muốn đăng bài mới thì làm sao

1. Viết bài bằng file `.md` (văn bản thường)
2. Đầu file dán 5 dòng này:

```
---
layout: default
title: "Tên bài viết"
description: "Mô tả ngắn 1 câu"
permalink: /duong-dan-bai-viet
---
```

3. Lên GitHub → **Add file** → **Upload files** → kéo file vào → **Commit changes**
4. Mở `index.md`, bấm biểu tượng bút chì để sửa, thêm dòng link tới bài mới
5. Đợi 2 phút là bài lên mạng

---

## ⚠️ Việc còn lại trước khi bài này kiếm được tiền

Bài đang **không có link affiliate nào** — tôi đã bỏ hết chỗ đánh dấu tạm để trang trông sạch sẽ.

Như vậy là **cố ý và đúng**: đăng trước để Google bắt đầu lập chỉ mục (mất 1–3 tuần),
gắn link sau khi xác nhận được mã thật của anh.

Chỗ cần gắn link nằm ở cuối mỗi mục sản phẩm, chỗ có chữ **Check current price**.
Khi có link thật, đổi thành:

```
[Check current price at Kizik →](DÁN-LINK-CỦA-ANH){:rel="nofollow sponsored"}
```

---

## Vì sao việc này đáng làm ngay

1. **Google không quan tâm anh ngồi ở đâu** — khác hẳn TikTok. Bài này tiếp cận người Mỹ
   không vướng rào địa lý nào.
2. **Awin đòi anh phải có website đang hoạt động** mới duyệt hồ sơ. Đây chính là thứ đó.
3. **Cho TikTok một chỗ để bấm vào** — ô website trong bio.
4. **Google cần 1–3 tuần để xếp hạng bài mới.** Đăng hôm nay thì kịp sóng tựu trường tháng 8;
   đăng cuối tháng 8 là viết cho năm sau.
