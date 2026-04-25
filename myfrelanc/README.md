# Developer Portfolio Website

Professional freelance portfolio va pricing website

## 📋 Nima mavjud?

✅ **Responsive Design** - Barcha devices da yaxshi ko'rinadi
✅ **Telegram Bot Pricing** - 3 tarqali narxlar (Oddiy, Standart, Premium)
✅ **Website Frontend Pricing** - Responsive web design
✅ **Frontend + Backend Pricing** - To'liq veb-ilova
✅ **AI Services Pricing** - Sun'iy intellekt yechimlari
✅ **Contact Form** - Mijozlardan buyurtma olish
✅ **Professional Design** - Modern va chiqiqqa tushunadigan dizayn

## 📁 Fayllar

- `index.html` - Main sahifa
- `styles.css` - CSS styling
- `script.js` - JavaScript funktionallik

## 🚀 Qanday ishga tushirish?

### 1. **Fayllarni o'zingizning serveringizga yuklang**

```bash
# Barcha 3 faylni o'zingizning web serveringizga yuklang:
- index.html
- styles.css
- script.js
```

### 2. **Localhost'da sinab ko'rish (Windows)**

PowerShell'da quyidagi buyruqni bajaring:
```powershell
cd c:\Users\User\Desktop\myfrelanc
python -m http.server 8000
```

Keyin browser'da kiriting: `http://localhost:8000`

## ⚙️ O'zgartirishlar

### Telegram username'ni o'zgartirish

`index.html` faylida line 216 ni toping va o'zgartiring:
```html
<a href="https://t.me/YOUR_USERNAME">@YOUR_USERNAME</a>
```

### Email manzilini o'zgartirish

`index.html` faylida line 221 ni toping:
```html
<a href="mailto:your@email.com">your@email.com</a>
```

### WhatsApp raqamini o'zgartirish

`index.html` faylida line 226 ni toping:
```html
<a href="https://wa.me/YOUR_NUMBER">+998 XX XXX XX XX</a>
```

### Contact Form'ni sozlash

`index.html` faylida line 201 dagi Formspree ID'ni o'zgartiring:
```html
<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

Formspree'dan FREE ID olish:
1. https://formspree.io ga kiring
2. Email manzilingizni kiriting
3. Form ID'ni oling va yuqorida qo'yin

## 💰 Narxlarni o'zgartirish

Barcha narxlar `index.html` faylida mavjud. Quyidagi bloklarni o'zingizga moslashtiring:

### Telegram Bot Narxlari (line 72-110)
### Website Frontend Narxlari (line 114-152)
### Frontend + Backend Narxlari (line 156-194)
### AI Services Narxlari (line 198-236)

## 🎨 Ranglari o'zgartirish

`styles.css` faylida root variables'ni o'zgartiring:

```css
:root {
    --primary-color: #6366f1;      /* Asosiy rang */
    --secondary-color: #8b5cf6;    /* Ikkinchi rang */
    --accent-color: #ec4899;       /* Accent rang */
    --dark-bg: #1f2937;            /* To'q fon */
    --light-bg: #f9fafb;           /* Yengil fon */
}
```

## 📱 Mobile'da sinovdan o'tkazish

1. Browser'da F12 (DevTools) ni bosing
2. Ctrl+Shift+M bosing yoki Toggle device toolbar
3. Turli devices'da sinab ko'ring

## 🔧 Qo'shimcha features'ni qo'shish

### 1. Analytics qo'shish (Google Analytics)
`index.html` ning `<head>` qismiga qo'shing:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR_GA_ID');
</script>
```

### 2. Whatsapp habar ulanishi
```html
<a href="https://wa.me/998XXXXXXXXX?text=Salom%20menga%20buyurtma%20kerak">
  WhatsApp'da yozing
</a>
```

## 💡 Web Hosting variantlari

### BEPUL:
- Vercel (vercel.com)
- Netlify (netlify.com)
- GitHub Pages (github.com)

### PLATALAR:
- Beget.com
- TimeWeb
- Timeweb.cloud

## 📞 Qo'llab-quvvatlash

Sayt'da muammalar bo'lsa:
1. Browser console'ni tekshiring (F12 > Console)
2. HTML, CSS, JS fayllarini tekshiring
3. Internet connection'ni tekshiring

## ✅ Tekshirish ro'yxati

- [ ] Telegram username o'zgartirildi
- [ ] Email manzili o'zgartirildi
- [ ] WhatsApp raqami o'zgartirildi
- [ ] Contact form Formspree'ga ulandi
- [ ] Barcha narxlar to'g'ri o'zgartirildi
- [ ] Logo/branding qo'shildi (opsional)
- [ ] Sayt responsiv - mobile'da ishlaydi
- [ ] Sayt hosting'ga yuklandi

Omad! 🚀
