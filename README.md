# 🧵 LUMI – Nón lá cách tân

## 👥 Thông tin nhóm

| STT | Họ tên                | MSSV     | Vai trò          |
| --- | --------------------- | -------- | ---------------- |
| 1   | Võ Thị Ly Ly          | 24126125 | Code & Deploy    |
| 2   | Lê Trần Trà My        | 24126134 | Design & UI      |
| 3   | Nguyễn Mai Khánh Linh | 24126115 | Design & Content |
| 4   | Phạm Nguyễn Thanh Mai | 24126127 | Test & Report    |
| 5   | Nguyễn Thị Trúc Ly    | 24126122 | Test & Quality   |
| 6   | Lê Việt Nhật          | 24126159 | Code & Logic     |

---

## 📌 Mô tả dự án

* **Tên thương hiệu:** LUMI – Nón lá cách tân
* **Slogan:** *"Đội chất riêng – Chạm nét Việt"*
* **Loại dự án:** Website thương mại điện tử (E-commerce)
* **Mục tiêu:** Xây dựng nền tảng bán nón lá cách tân, kết hợp truyền thống và hiện đại

---

## 🔥 Tính năng nổi bật

* 🎨 Giao diện hiện đại, responsive (Desktop / Tablet / Mobile)
* 🛍️ Danh mục sản phẩm + filter + phân trang
* 🛒 Giỏ hàng realtime
* 🔐 Form validation (đăng ký / thanh toán)
* ⚡ Tối ưu hiệu suất & SEO
* 🚀 Deploy tự động bằng GitHub Actions

---

## 🧱 Công nghệ sử dụng

* **Frontend:** Next.js, React, TailwindCSS
* **Backend:** Node.js
* **Database:** PostgreSQL (Neon)
* **ORM:** Prisma
* **Deploy:** Vercel
* **CI/CD:** GitHub Actions

---

## 🔗 Link dự án

* 🎨 Figma (view-only):
  👉 https://www.figma.com/design/h5cigrWrKWJOy10WYGAcGt/Untitled?node-id=0-1&t=6jC02iX5ju0fvOQa-1

* 💻 GitHub:
  👉 https://github.com/vietnhat1507/conical-hat-e-commerce

* 🌐 Website:
  👉 https://conical-hat-e-commerce.vercel.app/

* 🎥 Video demo:
  👉 https://www.youtube.com/watch?v=oetHtP3CBoY

---

## ⚙️ Hướng dẫn chạy local

### 1. Clone project

```bash
git clone https://github.com/vietnhat1507/conical-hat-e-commerce.git
cd conical-hat-e-commerce
```

### 2. Cài đặt dependencies

```bash
npm install
```

### 3. Setup biến môi trường

Tạo file `.env` và thêm:

```env
DATABASE_URL=your_database_url
NEXTAUTH_SECRET=your_secret
NEXTAUTH_URL=http://localhost:3000
STRIPE_SECRET_KEY=your_stripe_key
```

---

### 4. Setup database (Prisma)

```bash
npx prisma generate
npx prisma migrate deploy
```

---

### 5. Chạy project

```bash
npm run dev
```

👉 Truy cập: http://localhost:3000

---

## 🧪 Testing

* Kiểm tra UI trên nhiều thiết bị
* Test luồng đặt hàng
* Validate form (register / checkout)

---

## 📦 Deployment

* Sử dụng **Vercel** để deploy
* Tích hợp CI/CD với GitHub Actions
* Tự động build & deploy khi push code

---

## 📸 Demo giao diện (tuỳ chọn)

> Thêm ảnh vào thư mục `/screenshots`

```md
![Home](./screenshots/home.png)
![Product](./screenshots/product.png)
![Checkout](./screenshots/checkout.png)
```

---

## 📌 Định hướng phát triển

* 🔑 Đăng nhập bằng Google / OAuth
* 💳 Thanh toán online (Stripe / VNPay)
* 📦 Quản lý đơn hàng nâng cao
* 📊 Dashboard admin

---

## 📄 License

Dự án phục vụ mục đích học tập 🎓

---
