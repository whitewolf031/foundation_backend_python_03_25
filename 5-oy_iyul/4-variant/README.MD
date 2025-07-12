# 4 - variant: Parol bilan ishlash (while, shartlar)

Ushbu mashqlar foydalanuvchidan **parol kiritishni** talab qiladi. `while` sikli va `if` shartlari orqali foydalanuvchi xatolarini tahlil qilish va xavfsizlik mexanizmlarini yaratish o‘rganiladi.

---

## 🔹 1 - Vazifa (Oson): To‘g‘ri parol kiritilmaguncha so‘rash

### 🎯 Topshiriq:
- Foydalanuvchidan parol kiriting.
- To‘g‘ri parol: `"admin123"`
- Agar noto‘g‘ri parol kiritsa, davomiy kiritishni so‘rash kerak.
- To‘g‘ri parol kiritilgach, `"Xush kelibsiz!"` deb chiqaring.

---

## 🔹 2 - Vazifa (Qiyin):  
Foydalanuvchidan parol kiriting. Har safar **noto‘g‘ri parol** kiritsa, xato hisoblagichi **1 taga ortadi**.  
Agar **3 martadan ko‘p xato** qilsa, `"🚫 Bloklandingiz"` deb chiqsin. Aks holda, `"Xush kelibsiz!"` deb chiqsin.

---

## ✅ Misol:

Parolni kiriting: 123\
Noto‘g‘ri parol. Urinish: 1

Parolni kiriting: admin\
Noto‘g‘ri parol. Urinish: 2

Parolni kiriting: test\
Noto‘g‘ri parol. Urinish: 3

## 3 ta noto'g'ri javob bo'lsa: 🚫 Bloklandingiz!
## To'g'ri javob bo'lsa: Xush kelibsiz!
