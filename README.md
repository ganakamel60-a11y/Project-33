# ومضة — Wamda

موقع بسيط بيعرض اقتباسات (ومضات) ملهمة، مع إمكانية توليد اقتباس جديد عشوائيًا ونسخه للحافظة. مبني بالكامل بـ HTML/CSS/JavaScript خالص من غير أي مكتبات أو Build خطوات.

**🔗 Live Demo:** _(ضيفي رابط Vercel هنا بعد الرفع)_

## المميزات

- اقتباس عشوائي جديد بضغطة زرار، مع تغيير لون الخلفية والألوان الأساسية لكل اقتباس.
- نسخ الاقتباس والكاتب للحافظة بضغطة واحدة (Clipboard API).
- تصميم متجاوب لكل أحجام الشاشات، وواجهة عربية RTL كاملة.
- ملف واحد فقط (`index.html`) — مفيش أي اعتمادية خارجية.

## التشغيل محليًا

افتحي `index.html` مباشرة في أي متصفح، أو شغّلي سيرفر بسيط:

```bash
npx serve .
```

## الرفع على GitHub

```bash
git init
git add .
git commit -m "Initial commit: Wamda quotes app"
git branch -M main
git remote add origin https://github.com/<username>/wamda.git
git push -u origin main
```

## الرفع على Vercel

1. روحي [vercel.com](https://vercel.com) وسجّلي دخول بحساب GitHub بتاعك.
2. اضغطي **Add New → Project** واختاري الريبو `wamda`.
3. المشروع static بالكامل، فمفيش Build Command مطلوب — سيبي Framework Preset على **Other** واضغطي **Deploy**.
4. بعد ما يخلص، انسخي رابط الـ Live Demo وحطيه فوق في أول سطر بالـ README.

## بنية المشروع

```
wamda/
├── index.html   # كل الكود (HTML + CSS + JS) في ملف واحد
└── README.md
```

## تحسينات ممكنة لاحقًا

- توحيد اسم المشروع (العنوان في `<title>` مكتوب "حافز" بينما اسم البراند في الصفحة "ومضة").
- إضافة meta description و Open Graph tags عشان تظهر معاينة حلوة لما اللينك يتشارك على السوشيال ميديا.
- إضافة favicon.
