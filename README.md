# Wrid وريد حجوزات — Windows installer

Installers for **Wrid وريد حجوزات** (reservations management for staff) on Windows 10 / 11 (64-bit). This repository holds the installers only, no source code.

## Download

**[⬇ Download WridMyReservation-1.0.0-x64.msi](https://github.com/3nady/wrid-myreservation-desktop-releases/releases/download/v1.0.0/WridMyReservation-1.0.0-x64.msi)** (version 1.0.0, 50 MB)

```
https://github.com/3nady/wrid-myreservation-desktop-releases/releases/download/v1.0.0/WridMyReservation-1.0.0-x64.msi
```

- All versions: [Releases](https://github.com/3nady/wrid-myreservation-desktop-releases/releases)
- Version info as JSON (version, size, sha256, link): [latest.json](https://raw.githubusercontent.com/3nady/wrid-myreservation-desktop-releases/main/latest.json)
- Installation guide: [install-guide.html](https://htmlpreview.github.io/?https://github.com/3nady/wrid-myreservation-desktop-releases/blob/main/install-guide.html) · as JSON (Arabic and English): [install-guide.json](https://raw.githubusercontent.com/3nady/wrid-myreservation-desktop-releases/main/install-guide.json)

## Install

1. Download and double-click `WridMyReservation-1.0.0-x64.msi`.
2. If Windows shows "Windows protected your PC", click **More info**, then **Run anyway** (the file is not code-signed yet).
3. Click **Next** twice. On the options page choose "Launch after installation" (on by default), "Create desktop shortcut" (on by default) and "Start with Windows" (off by default), then **Next**, **Install**, and accept the administrator prompt.
4. Click **Finish**. The app installs to `C:\Program Files\Wrid MyReservation`.

Sign in with the same staff mobile number and password as the mobile app.

Silent install for many PCs (administrator Command Prompt): `msiexec /i WridMyReservation-1.0.0-x64.msi /qn`. Add `DESKTOP_SHORTCUT=0` to skip the desktop shortcut or `START_WITH_WINDOWS=1` to start the app with Windows.

A newer version installs over the old one and keeps the sign-in, settings, printer and install options.

SHA-256: `b793c43c850302aa54e7ab018716e3c089fc0c57110b600feaf3724f81b4b78c`

## التنزيل والتثبيت

**[⬇ تنزيل WridMyReservation-1.0.0-x64.msi](https://github.com/3nady/wrid-myreservation-desktop-releases/releases/download/v1.0.0/WridMyReservation-1.0.0-x64.msi)** (الإصدار 1.0.0)

1. نزّل الملف وانقر عليه نقراً مزدوجاً.
2. إذا ظهرت رسالة «حمى Windows جهاز الكمبيوتر» اضغط «مزيد من المعلومات» ثم «تشغيل على أي حال».
3. اضغط Next مرتين. في صفحة الخيارات اختر «تشغيل البرنامج بعد التثبيت» (مفعّل افتراضياً) و«إنشاء اختصار على سطح المكتب» (مفعّل افتراضياً) و«التشغيل تلقائياً مع بدء Windows» (غير مفعّل افتراضياً)، ثم Next ثم Install، ووافق على طلب صلاحية المسؤول.
4. اضغط Finish، وسجّل الدخول بنفس رقم الجوال وكلمة المرور المستخدمة في تطبيق الجوال.

الدعم عبر واتساب: +966 55 690 0966
