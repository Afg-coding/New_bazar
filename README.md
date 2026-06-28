# 🛍️ افغان بازار - نسخه 3.1.0

> بزرگترین بازار آنلاین افغانستان

## ✨ ویژگی‌های اصلی

### 🔐 احراز هویت
- ✅ ثبت‌نام و ورود کاربران
- ✅ بازیابی رمز عبور
- ✅ مدیریت پروفایل

### 📢 مدیریت آگهی‌ها
- ✅ ثبت آگهی‌های جدید
- ✅ بارگذاری چندین تصویر
- ✅ پوشش ویدیو
- ✅ دسته‌بندی‌های مختلف

### 💬 سیستم پیام‌رسانی
- ✅ چت عمومی
- ✅ کانال پشتیبانی
- ✅ پیام‌های خصوصی (آینده)

### 🤖 هوش مصنوعی
- ✅ دستیار هوشمند
- ✅ راهنمایی خرید و فروش
- ✅ پاسخ‌های سریع

### ⭐ ویژگی‌های ویژه
- ✅ تیک آبی برای کاربران تایید‌شده
- ✅ نسخه پریمیوم
- ✅ سیستم گزارش‌دهی
- ✅ علاقه‌مندی‌ها

### 👨‍💼 پنل مدیریت
- ✅ مدیریت کاربران
- ✅ مدیریت آگهی‌ها
- ✅ ارسال اعلانات
- ✅ بررسی گزارشات

## 🚀 شروع کار

### متطلبات
- مرورگر مدرن (Chrome, Firefox, Safari)
- اتصال اینترنت
- حساب Firebase

### نصب

```bash
# Clone کنید
git clone https://github.com/Afg-coding/New_bazar.git

# به دایرکتوری برید
cd New_bazar

# یک سرور محلی شروع کنید
python -m http.server 8000
# یا
npx http-server
```

### آنلاین استفاده
- GitHub Pages: `https://Afg-coding.github.io/New_bazar`
- Netlify/Vercel: آپلوڈ کنید

## ⚙️ تنظیمات Firebase

فایل `app.js` میں Firebase اطلاعات:

```javascript
const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_AUTH_DOMAIN",
    databaseURL: "YOUR_DATABASE_URL",
    projectId: "YOUR_PROJECT_ID",
    storageBucket: "YOUR_STORAGE_BUCKET",
    messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
    appId: "YOUR_APP_ID"
};
```

## 📁 ساختار پروژه

```
New_bazar/
├── index.html          # صفحه اصلی HTML
├── app.js              # منطق اپلیکیشن
├── style.css           # استایل‌ها
├── manifest.json       # PWA مینیفست
└── README.md           # این فایل
```

## 🎨 رنگ‌ها و تم

- **رنگ اساسی**: بنفش (`#7c3aed`)
- **پس‌زمینه**: تاریک (`#0a0a15`)
- **متن**: روشن (`#e8e8f0`)
- **خطر**: قرمز (`#ef4444`)
- **موفقیت**: سبز (`#22c55e`)

## 📱 تجربه موبایل

- ✅ طراحی واکنش‌پذیر
- ✅ تمام صفحات پشتیبانی می‌شوند
- ✅ PWA قابل نصب
- ✅ کار آفلاین (جزئی)

## 🔒 امنیت

- Firebase Authentication
- Database Rules
- HTTPS فقط
- Input Validation

## 📞 تماس و پشتیبانی

📧 **ایمیل**: jabirsitez786@gmail.com

💬 **کانال پشتیبانی**: درون اپ

## 📝 لایسنس

کل این پروژه ملک Afg-coding است.
© 2024 - تمام حقوق محفوظ است.

## 🎯 نقشه راه (Roadmap)

- [ ] چت خصوصی
- [ ] سیستم امتیاز
- [ ] تعلیقات واقعی
- [ ] سیستم پرداخت
- [ ] نسخه دسکتاپ

---

**ساخته شده با ❤️ برای افغانستان**
