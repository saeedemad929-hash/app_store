# 🛒 Robin Store - All-in-One E-commerce Solution
### **Android App & Windows Desktop Application**

![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)
![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Windows-green?style=for-the-badge)

**روبين ستور** هو تطبيق تجارة إلكترونية متكامل تم بناؤه باستخدام Flutter. يتميز التطبيق بدعمه لمنصات متعددة (Cross-Platform) حيث يعمل كبرنامج ويندوز وتطبيق أندرويد في آن واحد، مع لوحة تحكم ذكية لإدارة المبيعات والمنتجات وخدمات الصيانة.

---

## 📸 Screenshots (معاينة التطبيق)

| شاشة الترحيب (Splash) | تسجيل الدخول (OTP) | الرئيسية (Home) |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/8514d746-a26d-4dc7-a4a5-1ecfc8de2de8" width="200"> | <img src="https://github.com/user-attachments/assets/f0342281-5b22-480b-b111-67bed494a000" width="200"> | <img src="https://github.com/user-attachments/assets/2e7d9d8c-1f74-47c3-b276-e42f82ec96ab" width="200"> |

| خدمات أورانج | قسم الصيانة | لوحة تحكم الإدارة |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/bf0aa4ff-b7d5-4dd4-af76-0dbaeb4b93bc" width="200"> | <img src="https://github.com/user-attachments/assets/22d6ae5f-ee3a-4bf1-a1e6-6d4a01fc3c83" width="200"> | <img src="https://github.com/user-attachments/assets/23589103-af4b-45a6-86ee-16ba5154aec7" width="200"> |

---

## 🌟 المميزات (Features)

### 📱 تجربة المستخدم (UX/UI)
* **واجهة أمازون العصرية:** تصميم مريح وسلس مستوحى من كبرى تطبيقات التسوق.
* **نظام السلايدر التفاعلي:** عرض العروض الترويجية بشكل جذاب في صدر الصفحة.
* **البحث الفوري:** خاصية البحث عن المنتجات وتصفيتها حسب الفئة (سماعات، ساعات، موبايلات).

### 🛠 التقنيات المتقدمة (Backend & Data)
* **Firebase Integration:** توثيق الحسابات وربط البيانات سحابياً لضمان الأمان والسرعة.
* **Hive Database:** استخدام قاعدة بيانات NoSQL محلية لتجربة مستخدم سريعة جداً ودعم وضع الأوفلاين.
* **Multi-Platform Ready:** كود واحد يعمل بكفاءة على الأندرويد والويندوز.

### 💼 إدارة الأعمال والتحكم (Admin)
* **Secret Admin Panel:** لوحة تحكم سرية محمية بكلمة مرور خاصة لإضافة المنتجات والتحكم في المخزون.
* **Direct WhatsApp Ordering:** العميل يطلب المنتج بضغطة واحدة وتصله رسالة مفصلة بعنوانه عبر الواتساب.
* **Maintenance Management:** قسم مخصص لطلبات الصيانة وخدمات الدفع الإلكتروني (Orange).

---

## ⚙️ بيئة العمل (Architecture)

يعتمد التطبيق على معمارية برمجية منظمة تضمن سهولة التطوير:
1. **View Layer:** واجهات تفاعلية تدعم اللغة العربية (RTL).
2. **Persistence Layer:** إدارة الجلسات (Sessions) والبيانات المحلية عبر `Hive`.
3. **Communication:** تكامل مع تطبيقات خارجية مثل (WhatsApp, Dialer, InstaPay).

---

## 🚀 التثبيت والتشغيل (Installation)

### خطوات التشغيل للمطورين:
```bash
# 1. تحميل المشروع
git clone [https://github.com/YOUR_USERNAME/robin_store.git](https://github.com/YOUR_USERNAME/robin_store.git)

# 2. تنزيل المكتبات المطلوبة
flutter pub get

# 3. تشغيل التطبيق على الأندرويد
flutter run

# 4. بناء نسخة الويندوز (EXE)
flutter build windows
