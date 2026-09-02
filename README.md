# Nove Store 🛒

Premium FiveM & Discord products store. A fully client-side e-commerce website for selling scripts, bots, and gaming resources.

## ✨ Features
- Storefront with product catalog and categories (FiveM, Discord, custom)
- Product detail view with images
- Shopping cart with PayPal checkout
- User authentication: **Google Sign-In** OR **Email/Password** (register + login)
- Full admin panel (Dashboard, Products, Categories, Orders, Users, Add Admin, Settings)
- Store logo upload + custom store name
- Arabic / English (RTL/LTR) bilingual UI
- Data stored in browser localStorage

## 🚀 Usage
Open `index.html` directly, or host the folder on any static server (GitHub Pages, Netlify, Vercel).

## 🔑 Setup
1. **Google Login**: Set your Client ID in **Admin Panel → Settings → Google Sign-In**.
2. **PayPal**: Add your Client ID in **Admin Panel → Settings → PayPal** (for live payments).
3. **Owner (Admin)**: The owner email is `cr8381062@gmail.com` (configurable in `js/app.js`).

## 📁 Structure
```
├── index.html       # Storefront
├── pages/
│   └── admin.html   # Admin panel
├── css/style.css    # Styling
├── js/app.js        # All application logic
└── img/             # Images
```

## 🛠 Tech
No frameworks — pure HTML, CSS, and vanilla JavaScript.