# 🏠 Mess Manager Pro
![Mess Manager Pro](https://img.shields.io/badge/Version-2.0-f0c040?style=flat-square)
![HTML](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![No Backend](https://img.shields.io/badge/Backend-None-3dd68c?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-9b7ff4?style=flat-square)

> "মেসের হিসাব নিয়ে আর ঝামেলা নয় — প্রতি মাসে কে কত টাকা দেবে, কে পাবে, সব এক জায়গায়।"

**Mess Manager Pro** হলো একটি সম্পূর্ণ **বাংলা ভাষার** মেস খরচ ব্যবস্থাপনা অ্যাপ। এটি একটি single-page HTML অ্যাপ্লিকেশন যেখানে কোনো backend, database বা installation ছাড়াই মেসের বাজার খরচ, fixed খরচ, এবং সদস্যদের মধ্যে টাকার হিসাব নিখুঁতভাবে করা যায়।

🔗 **Live Demo:** [https://almazid82.github.io/mess-manager-pro/](https://almazid82.github.io/mess-manager-pro/)

---

## 📸 Preview

> Dark-themed, modern UI with Bengali language support — designed for everyday mess users.

---

## ✨ Features

- ✅ সম্পূর্ণ **বাংলা ভাষায়** তৈরি UI
- ✅ **৫টি Stage**-এ ধাপে ধাপে হিসাব
- ✅ Multi-currency support (৳ BDT, $ USD, ₹ INR)
- ✅ Custom mess নাম ও মাস সেট করার সুবিধা
- ✅ Dynamic সদস্য যোগ/বাদ দেওয়া যায়
- ✅ Custom fixed খরচের category তৈরি করা যায়
- ✅ সব সদস্যের জন্য এক ক্লিকে global খরচ apply
- ✅ চূড়ান্ত payment flow সহ সম্পূর্ণ Report
- ✅ Print ও Download সুবিধা
- ✅ কোনো internet ছাড়াও কাজ করে (offline capable)
- ✅ Mobile responsive design
- ✅ কোনো installation বা login দরকার নেই

---

## 🔢 How It Works — ৫ ধাপের হিসাব পদ্ধতি

### Stage 1 — বাজার ও খাওয়ার হিসাব
প্রতিটি সদস্যের নাম, মোট খাবার (বেলা), এবং বাজার খরচ ইনপুট করুন।
- সমস্ত বাজার একসাথে যোগ করে **প্রতি বেলার rate** বের করা হয়
- প্রত্যেকের meal cost বের হয় এবং **balance** (পাবেন/দেবেন) নির্ধারিত হয়
- Balance-এর যোগফল অবশ্যই শূন্য হবে — built-in validation আছে

### Stage 2 — Fixed মাসিক খরচ
ভাড়া, বিদ্যুৎ, গ্যাস, ইন্টারনেট ইত্যাদি fixed খরচের category তৈরি করুন।
- প্রতিটি সদস্যের জন্য আলাদা fixed খরচ দেওয়া যায়
- অথবা সবার জন্য একসাথে **"Global Apply"** করা যায়

### Stage 3 — Adjusted হিসাব
Stage 1-এর balance এবং Stage 2-এর fixed খরচ একত্রিত করে **adjusted amount** বের করা হয়।
- সূত্র: `Adjusted = Stage 1 Balance − Fixed Cost`

### Stage 4 — চূড়ান্ত হিসাব
Adjusted amount অনুযায়ী কে কত টাকা **দেবে** এবং কে কত টাকা **পাবে** তার চূড়ান্ত তালিকা।
- পাবেন/দেবেন আলাদাভাবে দেখানো হয়
- মোট payment flow স্পষ্টভাবে প্রদর্শিত হয়

### Stage 5 — সম্পূর্ণ রিপোর্ট
সব ধাপের একত্রিত সারাংশ — **Print** বা **Download** করা যাবে।

---

## 🛠️ Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white)

- **Pure Vanilla JS** — কোনো framework বা library নেই
- **Single HTML File** — সব CSS ও JS একটাই ফাইলে
- **Google Fonts** — Syne, JetBrains Mono, Hind Siliguri
- **CSS Variables** — সহজে theme পরিবর্তনযোগ্য dark design system

---

## 🚀 Getting Started

### Option 1: সরাসরি ব্যবহার করুন
লিংকে ক্লিক করুন এবং সাথে সাথে ব্যবহার শুরু করুন — কোনো setup দরকার নেই:

👉 **[https://almazid82.github.io/mess-manager-pro/](https://almazid82.github.io/mess-manager-pro/)**

### Option 2: Locally চালান
```bash
# Repository clone করুন
git clone https://github.com/almazid82/mess-manager-pro.git

# ফোল্ডারে ঢুকুন
cd mess-manager-pro

# index.html ফাইলটি browser-এ open করুন
open index.html
```

---

## 📋 ব্যবহারের নিয়ম

১. **মাস ও মেসের নাম** দিন উপরের bar-এ
২. **Stage 1** → সদস্যদের নাম, খাবার বেলা ও বাজার খরচ লিখুন → Calculate চাপুন
৩. **Stage 2** → Category যোগ করুন (ভাড়া, বিদ্যুৎ ইত্যাদি) → Fixed খরচ দিন → Calculate চাপুন
৪. **Stage 3** → Adjusted হিসাব দেখুন → Next চাপুন
৫. **Stage 4** → চূড়ান্ত payment দেখুন
৬. **Stage 5** → Report তৈরি করুন এবং Print বা Download করুন

> 💡 **টিপস:** "📥 Sample" বাটন চাপলে demo data লোড হবে, সহজে বুঝতে পারবেন।

---

## 📁 Project Structure

```
mess-manager-pro/
│
└── index.html        # সম্পূর্ণ অ্যাপ (HTML + CSS + JS)
```

---

## 🎨 Design System

| Color | Use |
|-------|-----|
| `#f0c040` (Yellow) | Primary accent, CTA buttons |
| `#3dd68c` (Green) | Positive balance, success states |
| `#f05060` (Red) | Negative balance, debt indicators |
| `#4a9eff` (Blue) | Info stats, neutral data |
| `#9b7ff4` (Purple) | Secondary highlights |
| `#0b0d13` (Dark) | Background |

---

## 🔮 Future Scope

- [ ] Local Storage সংরক্ষণ — পেজ refresh করলেও data থাকবে
- [ ] মাসভিত্তিক history রাখার সুবিধা
- [ ] WhatsApp/Messenger-এ সরাসরি রিপোর্ট শেয়ার
- [ ] PWA (Progressive Web App) — মোবাইলে install করার সুবিধা
- [ ] Excel/CSV export
- [ ] Multi-mess support

---

## 🤝 Contributions

Pull request এবং suggestions সবসময় স্বাগত! কোনো bug পেলে বা নতুন feature চাইলে Issue খুলুন।

---

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/shamsul-al-mazid-073a87286)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/sondartara.tara.777)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shamsulalmazid@gmail.com)

---

## © License

This project is open-sourced under the **MIT License**.
Feel free to use, modify, and share with credit.

---

> _"মেসের হিসাবে আর ভুল নয়, আর ঝামেলা নয় — Mess Manager Pro দিয়ে প্রতি মাসের হিসাব হোক স্বচ্ছ ও নির্ভুল।"_
