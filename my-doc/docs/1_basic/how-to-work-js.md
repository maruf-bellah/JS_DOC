---
sidebar_position: 2
---



# JS কীভাবে কাজ করে ?

### 🔹 JavaScript কি?

JavaScript হলো একটি **High-level, Interpreted Programming Language** যা মূলত ওয়েবপেজে **ইন্টার‌অ্যাকটিভ ফিচার** (যেমন: বাটনে ক্লিক করলে কিছু দেখা যাবে, ছবি পরিবর্তন হবে, ফর্ম সাবমিট হবে ইত্যাদি) যুক্ত করার জন্য ব্যবহৃত হয়।

---

### 🟩 **JavaScript কীভাবে ব্রাউজারে কাজ করে?**

প্রতিটি মডার্ন ওয়েব ব্রাউজারে (যেমন: Chrome, Firefox, Edge) একটি **JavaScript Engine** থাকে।
উদাহরণ: Chrome এ আছে 👉 V8 Engine

#### ✅ কাজ করার প্রক্রিয়া:

1. **HTML লোড হয়** → ওয়েবপেজের স্ট্রাকচার তৈরি হয়
2. **CSS লোড হয়** → পেজের ডিজাইন তৈরি হয়
3. **JavaScript লোড হয়** → তারপর ব্রাউজার JavaScript Code execute করে
4. ব্রাউজার DOM তৈরি করে, এরপর JavaScript সেই DOM-এর সঙ্গে কাজ করে

---

### 🧩 **Execution Flow (Code কীভাবে চলে)**

1. JavaScript কোড এক লাইনে এক লাইনে টপ থেকে বটম পর্যন্ত পড়ে (Synchronous Execution)
2. যদি টাইম ডিলে বা ক্লিক ইভেন্ট থাকে, তাহলে সেগুলো **Call Stack**, **Web APIs**, **Callback Queue** আর **Event Loop** এর মাধ্যমে পরিচালিত হয় (Asynchronous Execution)
3. সবশেষে ফাইনাল Output ব্রাউজারে দেখা যায়।

> আপনি চাইলে আমি এই পুরো Execution Flow-র একটি চিত্র বা Diagram বানিয়ে দিতে পারি।

---

## 🌐 **JavaScript কোথায় কোথায় ব্যবহার হয়?**

JavaScript কেবল ব্রাউজারেই না — আজ অনেক জায়গায় ব্যবহার হয়:

| ব্যবহার ক্ষেত্র        | উদাহরণ                                 |
| ---------------------- | -------------------------------------- |
| ✅ **ওয়েবসাইটে**        | বাটন ক্লিক, পপ-আপ, ফর্ম ভ্যালিডেশন     |
| ✅ **ওয়েব অ্যাপ**       | Gmail, Facebook, YouTube               |
| ✅ **মোবাইল অ্যাপ**     | React Native দিয়ে অ্যাপ বানানো         |
| ✅ **ডেস্কটপ অ্যাপ**    | Electron দিয়ে বানানো (যেমন: VS Code)   |
| ✅ **Server-side**      | Node.js দিয়ে Backend বানানো            |
| ✅ **Game Development** | Phaser.js দিয়ে 2D গেম                  |
| ✅ **IoT Devices**      | JavaScript দিয়ে Smart Device নিয়ন্ত্রণ |

---

## 🧪 **কেন JavaScript শিখব?**

1. ✅ **Frontend Development এর জন্য অপরিহার্য**
2. ✅ একমাত্র ভাষা যা ব্রাউজারে চলে
3. ✅ Backend, Mobile App, Desktop App – সব জায়গায় কাজ করে
4. ✅ চাকরির বাজারে সবচেয়ে বেশি চাহিদা
5. ✅ Framework (React, Vue, Angular) শিখতে JavaScript লাগবেই
6. ✅ বড় বড় কোম্পানি (Google, Facebook, Netflix) ব্যবহার করে

---

## 🛠️ **JavaScript কীভাবে ব্যবহার করব?**

### ✅ 1. HTML ফাইলে ব্যবহার:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First JS</title>
  </head>
  <body>
    <h1>Hello JavaScript</h1>
    <script>
      alert("Welcome to JavaScript!");
      console.log("Console এ মেসেজ দেখাচ্ছে");
    </script>
  </body>
</html>
```

### ✅ 2. আলাদা .js ফাইলে:

```html
<script src="script.js"></script>
```

`script.js` ফাইলে আপনার JavaScript কোড থাকবে।

---

## 🎯 সংক্ষেপে:

| বিষয়       | বর্ণনা                                               |
| ---------- | ---------------------------------------------------- |
| JS কী         | একটি প্রোগ্রামিং ভাষা যা ওয়েবপেজে ইন্টার‌অ্যাকশন আনে |
| কোথায় চলে  | ব্রাউজার, সার্ভার, মোবাইল, ডেস্কটপ                   |
| কেন শিখব   | প্রায় সব ওয়েব টেকনোলজির বেস JavaScript               |
| কীভাবে চলে | ব্রাউজারের JavaScript Engine এর মাধ্যমে              |

---

