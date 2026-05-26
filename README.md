# css<div align="center">

# 🎨 Ultimate CSS Cheat Sheet

**Selectors · Box Model · Flexbox · Grid · Responsive**  
_Every essential property at your fingertips_

[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![W3C](https://img.shields.io/badge/W3C-Validated-brightgreen?style=for-the-badge)](https://jigsaw.w3.org/css-validator/)

</div>

---

## 🔍 1. Selectors (সিলেক্টর)

<div align="center">

| Selector | Description |
|----------|-------------|
| `*` | সব এলিমেন্ট |
| `element` | ট্যাগ সিলেক্টর (যেমন `p`) |
| `.class` | ক্লাস সিলেক্টর |
| `#id` | আইডি সিলেক্টর |
| `parent child` | ডিসেন্ডেন্ট (ভেতরের সব) |
| `parent > child` | ডিরেক্ট চাইল্ড |
| `a:hover` | হোভার স্টেট |
| `:nth-child(n)` | নির্দিষ্ট চাইল্ড (odd/even/3n) |
| `::before`, `::after` | সিউডো-এলিমেন্ট |
| `[type="text"]` | অ্যাট্রিবিউট সিলেক্টর |

</div>

---

## 📦 2. Box Model (বক্স মডেল)

<div align="center">

| Property | Description |
|----------|-------------|
| `width` / `height` | এলিমেন্টের সাইজ |
| `padding: 10px;` | ভেতরের ফাঁকা জায়গা |
| `padding: 10px 20px;` | টপ-বটম 10px, লেফট-রাইট 20px |
| `border: 1px solid red;` | বর্ডার (size style color) |
| `margin: 10px auto;` | বাইরের ফাঁকা (সেন্টারে auto) |
| `box-sizing: border-box;` | প্যাডিং/বর্ডার সাইজের ভেতরে গণনা |
| `outline: none;` | ফোকাস আউটলাইন সরানো |
| `overflow: hidden;` | ওভারফ্লো কন্টেন্ট লুকানো |

</div>

---

## 🎨 3. Typography (টেক্সট স্টাইল)

<div align="center">

| Property | Description |
|----------|-------------|
| `font-family: Arial, sans-serif;` | ফন্ট |
| `font-size: 16px;` | ফন্ট সাইজ |
| `font-weight: bold;` (or `700`) | মোটা |
| `line-height: 1.5;` | লাইন স্পেসিং |
| `text-align: center;` | অনুভূমিক কেন্দ্রীভূত |
| `text-decoration: underline;` | আন্ডারলাইন / none |
| `text-transform: uppercase;` | বড় হাতের অক্ষর |
| `letter-spacing: 2px;` | অক্ষরের ফাঁক |
| `color: #333;` | টেক্সটের রঙ |
| `white-space: nowrap;` | টেক্সট ব্রেক না করা |

</div>

---

## 🌈 4. Colors & Backgrounds

<div align="center">

| Property | Description |
|----------|-------------|
| `color: red;` | টেক্সট কালার |
| `background-color: #f5f5f5;` | ব্যাকগ্রাউন্ড কালার |
| `background-image: url('...');` | ব্যাকগ্রাউন্ড ইমেজ |
| `background-size: cover;` | ইমেজ কাভার করা |
| `background-position: center;` | পজিশন |
| `opacity: 0.5;` | স্বচ্ছতা (0-1) |
| `rgba(255,0,0,0.5)` | কালার + আলফা |
| `linear-gradient(to right, red, blue)` | গ্রেডিয়েন্ট |

</div>

---

## 📐 5. Flexbox

<div align="center">

| Property | Description |
|----------|-------------|
| `display: flex;` | ফ্লেক্স কন্টেইনার |
| `justify-content: center;` | মেইন অ্যাক্সিস বরাবর সেন্টার (space-between, space-around) |
| `align-items: center;` | ক্রস অ্যাক্সিস বরাবর সেন্টার (flex-start, stretch) |
| `flex-direction: column;` | উলম্ব বা অনুভূমিক (row/column) |
| `flex-wrap: wrap;` | ব্রেক করে পরের লাইনে যাওয়া |
| `gap: 20px;` | আইটেমগুলোর মধ্যে ফাঁক |
| `flex: 1;` | চাইল্ডের নমনীয়তা |
| `align-self: flex-end;` | নির্দিষ্ট চাইল্ডের অ্যালাইনমেন্ট |

</div>

---

## 📏 6. Grid

<div align="center">

| Property | Description |
|----------|-------------|
| `display: grid;` | গ্রিড কন্টেইনার |
| `grid-template-columns: 1fr 2fr;` | কলাম ট্র্যাক (repeat(3, 1fr)) |
| `grid-template-rows: auto;` | রো ট্র্যাক |
| `gap: 10px;` | রো ও কলামের ফাঁক |
| `grid-column: span 2;` | কলাম মার্জ |
| `justify-items: center;` | অনুভূমিক অ্যালাইনমেন্ট |
| `align-items: center;` | উলম্ব অ্যালাইনমেন্ট |
| `place-items: center;` | একই সাথে দুই অক্ষ |

</div>

---

## 🧭 7. Positioning & Display

<div align="center">

| Property | Description |
|----------|-------------|
| `display: none;` | এলিমেন্ট লুকানো |
| `display: block;` | ব্লক এলিমেন্ট |
| `display: inline-block;` | ইনলাইন কিন্তু সাইজযোগ্য |
| `position: relative;` | স্বাভাবিক অবস্থান থেকে সরানো |
| `position: absolute;` | নিকটতম positioned ancestor-এর সাপেক্ষে |
| `position: fixed;` | ভিউপোর্টের সাপেক্ষে স্থির |
| `z-index: 10;` | স্তর (বড় মান উপরে) |
| `top`, `right`, `bottom`, `left` | স্থানাঙ্ক (position: relative/absolute/fixed) |

</div>

---

## 🌀 8. Transitions & Animations

<div align="center">

| Property | Description |
|----------|-------------|
| `transition: all 0.3s ease;` | ট্রানজিশন |
| `transition-property: opacity;` | কোন প্রপার্টিতে |
| `animation: slide 1s ease infinite;` | অ্যানিমেশন নাম |
| `@keyframes slide { from { left:0 } to { left:100px } }` | কীফ্রেম |

</div>

---

## 📱 9. Responsive Design (Media Queries)

<div align="center">

| Code | Description |
|------|-------------|
| `@media (max-width: 768px) { ... }` | মোবাইলের জন্য |
| `@media (min-width: 769px) and (max-width: 1024px)` | ট্যাবলেট |
| `@media (min-width: 1025px)` | ডেস্কটপ |
| `<meta name="viewport" content="width=device-width, initial-scale=1.0">` | HTML-এ ভিউপোর্ট সেট |

</div>

---

## 🛠️ 10. Useful Snippets

<div align="center">

| Snippet | What it does |
|---------|--------------|
| `* { margin: 0; padding: 0; box-sizing: border-box; }` | CSS রিসেট |
| `display: flex; justify-content: center; align-items: center;` | পারফেক্ট সেন্টার |
| `transition: all 0.3s ease;` | স্মুথ ইফেক্ট |
| `cursor: pointer;` | হোভারে হাত দেখানো |
| `user-select: none;` | টেক্সট সিলেকশন নিষ্ক্রিয় |
| `:root { --primary: #FF2D20; }` | CSS কাস্টম প্রপার্টি (ভ্যারিয়েবল) |
| `var(--primary)` | ভ্যারিয়েবল ব্যবহার |

</div>

---

<div align="center">

### 🎯 Keep this on your second screen – never google again!  
**Happy Styling!**

[![Profile Views](https://komarev.com/ghpvc/?username=your-username&color=blueviolet&style=flat-square)](https://github.com/your-username)

</div>
