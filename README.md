# رابطة Domains

عرض تقديمي تفاعلي (HTML) من 16 شريحة، يعمل على الموبايل والتابلت واللابتوب.

## هيكل الملفات

```
ahli-domains-fan-league/
├── render.yaml          # إعدادات Render Blueprint
├── README.md
├── .gitignore
└── public/
    ├── index.html       # العرض
    └── assets/
        └── domains.webp  # شعار Domains
```

## الرفع على GitHub

```bash
cd ahli-domains-fan-league
git init
git add .
git commit -m "Ahli Aleppo fan league presentation"
git branch -M main
git remote add origin https://github.com/<USERNAME>/ahli-domains-fan-league.git
git push -u origin main
```

## النشر على Render كـ Blueprint

1. من لوحة Render: **New** ← **Blueprint**
2. اختر المستودع `ahli-domains-fan-league`
3. سيقرأ Render ملف `render.yaml` تلقائياً وينشئ موقعاً ثابتاً (Static Site) باسم `ahli-domains-fan-league`
4. اضغط **Apply**، وبعد دقيقة يصبح العرض متاحاً على رابط بصيغة `https://ahli-domains-fan-league.onrender.com`

أي `git push` لاحق على الفرع `main` يعيد النشر تلقائياً.

## التشغيل محلياً

افتح `public/index.html` مباشرة في المتصفح، أو:

```bash
cd public && python3 -m http.server 8000
```

## التنقل في العرض

- عجلة الماوس أو الأسهم: شريحة واحدة لكل حركة
- مربع الانتقال أسفل الشاشة: قائمة بكل الشرائح
- الموبايل والتابلت: السحب العادي
