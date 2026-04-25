# 🚀 TEZDA O'RNATISH GAJARI

Bu sahifada faqat zaruriy o'zgartirishlarni qiling:

## 1️⃣ TELEGRAM USERNAMEINI ALMASHTIRING

**index.html faylini oching** → Ctrl+F ni bosing → quyidagini qidiring:

```
@YOUR_USERNAME
```

Mavjud ikkita joyda:
- **Line 41**: Hero section'da
- **Line 216**: Contact section'da

## 2️⃣ EMAIL MANZILINGIZNI ALMASHTIRING

**index.html faylini oching** → Ctrl+F → qidiring:

```
your@email.com
```

## 3️⃣ WHATSAPP RAQAMINI ALMASHTIRING

**index.html faylini oching** → Ctrl+F → qidiring:

```
+998 XX XXX XX XX
```

O'zingizning raqamni kiriting (masalan: +998901234567)

## 4️⃣ CONTACT FORM'NI SOZLASH (MUHIM!)

### Bosqich 1: Formspree'dan ID olish
1. https://formspree.io ga kiring
2. Email kiriting
3. Confirm button ni bosing
4. Dashboard'dan Form ID olish

### Bosqich 2: Form ID'ni sayt'ga qo'shish
**index.html faylini oching** → Ctrl+F → qidiring:

```
YOUR_FORM_ID
```

O'zingizning Formspree ID'ni kiriting (masalan: `f/abc123def456`)

**Natija:**
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

## 5️⃣ NARXLARNI O'ZGARTIRISH

Barcha narxlar **index.html** faylida:

- **Telegram Bot narxlari**: 72-110 qatorlar
- **Website Frontend**: 114-152 qatorlar  
- **Frontend + Backend**: 156-194 qatorlar
- **AI Services**: 198-236 qatorlar

Bu sahifalarning o'zgartirishlarning misollari:

```html
<div class="price">200,000 so'm</div>  <!-- Narxni o'zgartiring -->
<div class="price">500,000 so'm</div>
```

## 6️⃣ VEBSAYT NOMINI O'ZGARTIRISH

**index.html** faylida line 4:
```html
<title>Developer Portfolio - Freelance Xizmatlar</title>
```

O'zingizning nomingizni kiriting:
```html
<title>SIZNING ISMINGIZ - Freelance Xizmatlar</title>
```

**styles.css** faylida logo'ni o'zgartiring:
```html
<div class="logo">DevStudio</div>
```

O'zingizning nomini kiriting:
```html
<div class="logo">SIZNING NOMINGIZ</div>
```

## 7️⃣ VEBSAYT LOKAL'DA SINASH

PowerShell'da:

```powershell
cd c:\Users\User\Desktop\myfrelanc
python -m http.server 8000
```

Browser'da oching: **http://localhost:8000**

## 8️⃣ VEBSAYTNI ONLAYN QO'SHISH

### Variant 1: Vercel (Bepul va Eng Oson) ⭐

1. https://vercel.com ga kiring
2. GitHub/Google account bilan ro'yxatdan o'ting
3. "New Project" - "Import Git Repo"
4. Sayt'ini GitHub'ga yuklang avval
5. Deploy qilinga - Tayyor!

### Variant 2: Netlify (Bepul)

1. https://netlify.com ga kiring
2. GitHub'dan login qiling
3. 3 faylni Drag & Drop qilib yuklang
4. Deploy qilinga - Tayyor!

### Variant 3: O'zingizning Hosting'da

1. Beget.com yoki boshqa hostingni tanlang
2. FTP client'ni (FileZilla) oching
3. 3 faylni upload qiling
4. Domain'ni ulang
5. Tayyor!

## ✅ TEKSHIRISH RO'YXATI

- [ ] Telegram username o'zgartirildi ✓
- [ ] Email kiriting ✓
- [ ] WhatsApp raqam o'zgartirildi ✓
- [ ] Formspree Form ID qo'shildi ✓
- [ ] Narxlar to'g'ri ✓
- [ ] Vebsayt nomi o'zgartirildi ✓
- [ ] Lokal'da sinab ko'rildi (http://localhost:8000) ✓
- [ ] Onlayn hosting'ga yuklandi ✓

## 🎨 Qo'shimcha: RANGLARNI O'ZGARTIRISH

**styles.css** faylining 8-16 qatorlari:

```css
:root {
    --primary-color: #6366f1;      /* Asosiy rang - bu yerda o'zgartiring */
    --secondary-color: #8b5cf6;    /* Ikkinchi rang */
}
```

Rangli kodlar:
- #FF6B6B (Qizil)
- #4ECDC4 (Ko'k-yashil)
- #45B7D1 (Ko'k)
- #F7B731 (Sariq)
- #5F27CD (Binafsha)

Masalan:
```css
--primary-color: #FF6B6B;  /* Qizilga o'zgarish */
```

## 🚀 TAYYOR!

Endi sayt'ingiz:
- ✅ Professional ko'rinadi
- ✅ Mobile'da ishlaydi
- ✅ Buyurtmalarni qabul qiladi
- ✅ Barcha narxlar ko'rsatilgan

**MUVAFFAQIYAT!** 🎉

Agar masalalar bo'lsa, browser console'ni tekshiring (F12 ni bosing).
