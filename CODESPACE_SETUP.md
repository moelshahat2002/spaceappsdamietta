# 🎁 Codespace Setup Guide - Forever & Always

## 🚀 طريقة التشغيل في Codespace

### الطريقة الأولى: استخدام npm scripts (الأسهل) ⭐

```bash
# 1️⃣ ثبت dependencies (المرة الأولى فقط)
npm install

# 2️⃣ شغّل السيرفر
npm start
```

ستظهر رسالة:
```
Starting up http-server, serving .

Serving HTTP on port 8080...
```

ثم:
- 📋 **انسخ الرابط**: `http://localhost:8080/Love_Site_Final.html`
- 🌐 **افتح الرابط في متصفحك** (علامة تبويب جديدة)

---

### الطريقة الثانية: استخدام VS Code Tasks

1️⃣ اضغط: `Ctrl+Shift+B` أو `Cmd+Shift+B` (Mac)  
2️⃣ اختر: **"🚀 Start Love Site Server (Port 8080)"**  
3️⃣ اضغط Enter  

ستظهر الرسالة:
```
Starting up http-server...
Serving HTTP on port 8080...
```

ثم افتح الرابط في المتصفح ✨

---

### الطريقة الثالثة: الأوامر اليدوية

```bash
# تثبيت http-server (إذا لم يكن مثبتاً)
npm install -g http-server

# تشغيل السيرفر
http-server . -p 8080
```

---

## 🔗 الروابط الهامة

بعد تشغيل السيرفر، افتح أحد هذه الروابط:

| الرابط | الوصف |
|--------|--------|
| `http://localhost:8080/Love_Site_Final.html` | 💕 الموقع الرومانسي |
| `http://localhost:8080` | 📁 قائمة الملفات |

---

## ✨ المميزات

✅ لا حاجة لـ Desktop VS Code  
✅ يعمل مباشرة من Codespace  
✅ السيرفر يقدم الملفات بشكل صحيح  
✅ يدعم جميع الميزات (animations, touch, keyboard)  

---

## 🛠️ استكشاف الأخطاء

### المشكلة: Port 8080 مشغول بالفعل

```bash
# استخدم port مختلف
http-server . -p 3000

# ثم افتح
http://localhost:3000/Love_Site_Final.html
```

### المشكلة: http-server غير مثبت

```bash
npm install -g http-server
# أو
npm install http-server
```

### المشكلة: الموقع لا يعمل

✅ تأكد من تشغيل السيرفر  
✅ تأكد من الرابط صحيح  
✅ امسح الـ cache (Ctrl+Shift+Delete)  
✅ جرب متصفح مختلف  

---

## 🎮 بعد الفتح

1. اضغط زر **"اضغطي هنا"** للدخول
2. استمتع برؤية الرسائل الرومانسية ❤️
3. استخدم الأسهم أو اسحب للتنقل بين الكروت

---

## 📝 ملاحظات

- الموقع يعمل على **جميع المتصفحات الحديثة**
- **يدعم الهاتف** (responsive design)
- **بدون dependencies خارجية** (HTML + CSS + JS فقط)
- القلوب الطائرة تظهر لمدة دقيقة واحدة

---

## ❤️ استمتع!

Forever & Always ❤️

Made with ❤️ for someone special
