# 🔦 سراج | Siraj

<p align="center">
  <b>حقيبة أدوات المطور السريعة والآمنة في المتصفح | Fast & Secure In-Browser Developer Utilities</b>
</p>

<p align="center">
  <a href="https://amr754.github.io/siraj/"><strong>🌐 التجربة المباشرة | Live Demo</strong></a>
</p>

---

## 📖 حول المشروع | About

**العربية:**  
**سراج (Siraj)** هي حقيبة أدوات ويب مفتوحة المصدر وخفيفة موجهة للمطورين، تجمع أهم الأدوات اليومية في صفحة واحدة فائقة السرعة. يعمل التطبيق محلياً بالكامل (Client-side 100%) داخل متصفحك دون إرسال أي بيانات لخوادم خارجية، مما يضمن أقصى درجات الأمان والخصوصية لبياناتك ورموزك الحساسة.

**English:**  
**Siraj** is a lightweight, open-source web toolbox for developers that brings together essential everyday utilities into a single, blazing-fast interface. It operates entirely client-side within your browser—meaning zero data is sent to external servers, ensuring maximum privacy and security for sensitive payloads and tokens.

---

## ✨ المميزات الرئيسية | Key Features

- **🔒 أمان وخصوصية كاملة (100% Client-Side):**  
  *AR:* كل المعالجات وفك التشفير تتم داخل جهازك؛ لا يتم تخزين أو نقل بياناتك إطلاقاً.  
  *EN:* All processing runs locally in your browser. No analytics, tracking, or remote data transfer.

- **🌐 واجهة ثنائية اللغة (Bilingual UI):**  
  *AR:* دعم سلس للغتين العربية والإنجليزية مع تبديل تلقائي للاتجاه (RTL / LTR).  
  *EN:* Seamless toggle between Arabic and English with dynamic RTL/LTR layout adjustment.

- **⚡ كشف تلقائي ذكي (Smart Auto-Detection):**  
  *AR:* يتعرف التطبيق تلقائياً على نوع المحتوى الملصق (JSON, JWT, Base64) وينتقل للأداة المناسبة فوراً.  
  *EN:* Automatically detects the pasted data type (JSON, JWT, Base64) and switches to the corresponding tool instantly.

- **📱 تطبيق ويب تقدمي (PWA & Offline Ready):**  
  *AR:* قابل للتثبيت على الهواتف وأجهزة الكمبيوتر، ويعمل بكفاءة دون الحاجة لشبكة إنترنت.  
  *EN:* Installable on mobile and desktop, functioning completely offline via Service Workers.

---

## 🛠️ الأدوات المدمجة | Built-in Tools

| الأداة | Tool | الوصف | Description |
| :--- | :--- | :--- | :--- |
| **منسق JSON** | **JSON Formatter** | فحص الأخطاء، تنسيق، ضغط، ترتيب المفاتيح، وعرض شجري قابل للطي مع تنزيل الملف. | Validation, prettify, minify, sort keys, foldable tree view, and file export. |
| **مفكك JWT** | **JWT Decoder** | فحص ترويسة الرأس (Header) والحمولة (Payload) وتاريخ الإصدار والانتهاء. | Inspect headers, claims/payload, and calculate expiration timestamps locally. |
| **مختبر Regex** | **Regex Tester** | اختبار التعابير النمطية وتلوين المطابقات في الوقت الفعلي مع عداد النتائج. | Real-time pattern matching, syntax highlighting, flags support, and match counter. |
| **محول Base64** | **Base64 Converter** | ترميز وفك تشفير النصوص والروابط مع دعم كامل للأحرف العربية (UTF-8). | Encode/decode strings and URL-safe data with full UTF-8 Arabic support. |
| **مقارنة النصوص** | **Diff Checker** | مقارنة سطر بسطر بين نصين أو ملفين لاكتشاف الفروقات بدقة. | Side-by-side / inline text comparison with additions and deletions highlighted. |

---

## 🚀 التشغيل المحلي | Local Development

لا يتطلب المشروع أي بيئة تشغيل معقدة أو تثبيت عبر `npm`:

```bash
# استنساخ المستودع | Clone the repository
git clone [https://github.com/Amr754/siraj.git](https://github.com/Amr754/siraj.git)

# الدخول للمجلد | Navigate to folder
cd siraj

# فتح التطبيق | Open in browser
# يمكنك فتح ملف index.html مباشرة في أي متصفح حديث
