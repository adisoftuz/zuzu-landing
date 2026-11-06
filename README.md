# zuzuchat Landing Page (Ko'prik Sayt)

Instagram target reklamalaridan [@zuzuchatbot](https://t.me/zuzuchatbot) Telegram botiga o'tuvchilar uchun moslashtirilgan bir sahifali ko'prik sayt (pre-landing).

## Afzalliklari:
1. **Deep Linking:** Instagram ichki brauzeridan to'g'ridan-to'g'ri Telegram ilovasini ochadi.
2. **Meta (Facebook) Pixel:** Sayt ichida Meta Pixel o'rnatish joyi mavjud. Foydalanuvchi "Botni Ishga Tushirish" tugmasini bosganda `Lead` va `Contact` hodisalari (events) yuboriladi.
3. **Yuqori tezlik:** Sof HTML va CSS, hech qanday og'ir kutubxonalarsiz, 1 soniyada ochiladi.
4. **Zamonaviy mobil dizayn:** Dark mode, neon gradientlar va qulay interfeys.

## Meta Pixel ulash:
`index.html` faylini ochib, 17-qatordagi:
```javascript
const META_PIXEL_ID = ""; // O'rniga o'z Pixel ID raqamingizni yozing (masalan: "1234567890")
```
bo'sh joyga o'zingizning Meta Pixel ID raqamingizni yozishingiz kifoya.
