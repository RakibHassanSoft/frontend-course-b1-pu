# 🎨 CSS Full Notes 

## 🎯 CSS কি?
- **CSS (Cascading Style Sheets)** হল **একটি স্টাইল শিট ভাষা**, যা **HTML বা XML ডকুমেন্টের ডিজাইন নিয়ন্ত্রণ করতে ব্যবহৃত হয়**।
- **CSS এর মাধ্যমে** আপনি **ওয়েব পেজের রং, ফন্ট, লেআউট, মার্জিন, প্যাডিং, বর্ডার ইত্যাদি নিয়ন্ত্রণ করতে পারেন**।
- **HTML কেবল কন্টেন্ট তৈরি করে, CSS সেটিকে ডিজাইন করে আরও আকর্ষণীয় করে তোলে**।

---

## 🎯 CSS এর উদ্দেশ্য
1️⃣ **HTML কন্টেন্ট এবং ডিজাইন আলাদা করা**, যাতে সহজেই ডিজাইন পরিবর্তন করা যায়।  
2️⃣ **ওয়েবসাইটকে সুন্দর ও রেসপন্সিভ করা**।  
3️⃣ **পেজ লোড স্পিড বাড়ানো**।  
4️⃣ **বড় ওয়েবসাইটে সহজে ডিজাইন কন্ট্রোল করা**।  
5️⃣ **CSS পুনঃব্যবহারযোগ্য কোডিং এনাবল করে**।

---

## 🚀 CSS এর গুরুত্ব:
- ✅ **ডিজাইন এবং কন্টেন্টকে আলাদা করে**।
- ✅ **ওয়েবসাইটকে আরও সুন্দর ও আকর্ষণীয় করে**।
- ✅ **রেসপন্সিভ ডিজাইন সহজ করে তোলে**।
- ✅ **ওয়েবসাইটের লোডিং টাইম কমায়**।
- ✅ **একটি CSS ফাইল ব্যবহার করে অনেক পেজের স্টাইল পরিবর্তন করা যায়**।
- ✅ **CSS দিয়ে সহজেই এনিমেশন ও ইফেক্ট যোগ করা সম্ভব**।

---

## 🎨 CSS এর উপকারিতা:
- 🚀 **ওয়েব পেজের লোড সময় কমে যায়**।
- 🚀 **রেসপন্সিভ ওয়েবসাইট তৈরি করা সহজ**।
- 🚀 **ডিজাইন এবং কন্টেন্ট আলাদা করা যায়**।
- 🚀 **ব্যবহারকারী অভিজ্ঞতা (UX) বৃদ্ধি পায়**।
- 🚀 **কোড পুনঃব্যবহারযোগ্য হওয়ায় ডেভেলপমেন্ট সহজ হয়**।

---

## 🎯 CSS কোডের উদাহরণ:
```html
<!DOCTYPE html>
<html lang="bn">
<head>
    <title>CSS উদাহরণ</title>
    <style>
        body {
            
        }
        h1 {
           
        }
        p {
           
        }
    </style>
</head>
<body>
    <h1>এইচটিএমএল + সিএসএস উদাহরণ</h1>
    <p>CSS ব্যবহার করে আমরা এই টেক্সটের রঙ পরিবর্তন করেছি!</p>
</body>
</html>
```

---

## ✅ সংক্ষেপে মনে রাখার উপায়:
- **CSS HTML-এর ডিজাইন কন্ট্রোল করতে ব্যবহৃত হয়**।
- **CSS ওয়েবসাইটকে দ্রুত লোড হতে সাহায্য করে**।
- **CSS ব্যবহার করে রেসপন্সিভ ডিজাইন তৈরি করা যায়**।
- **একটি CSS ফাইল ব্যবহার করে অনেক পেজের ডিজাইন কন্ট্রোল করা যায়**।
- **CSS দিয়ে ওয়েবসাইটে এনিমেশন, ইফেক্ট, এবং ট্রানজিশন যোগ করা সম্ভব**।



# 🎨 CSS styling types in HTML
১. **Inline CSS (ইনলাইন CSS)**

- 🖋️ **প্রকৃত HTML ট্যাগে সরাসরি CSS লেখা হয়।**
- **উদাহরণ:**
  ```html
  <p style="color: red;">এটি একটি লাল টেক্সট</p>
  ```
- **ব্যবহার**: যখন ছোট পরিসরে CSS প্রয়োগ করতে হয়, সাধারণত একক এলিমেন্টের জন্য।

---

২. **Internal CSS (ইন্টারনাল CSS)**

- 🖋️ **HTML ফাইলে `<style>` ট্যাগের ভিতরে CSS লেখা হয়।**
- **উদাহরণ:**
  ```html
  <head>
    <style>
      p { color: blue; }
    </style>
  </head>
  <body>
  ```
- **ব্যবহার**: পৃষ্ঠার মধ্যে অনেকগুলো এলিমেন্টের জন্য একত্রে CSS প্রয়োগ করতে।

---

৩. **External CSS (এক্সটার্নাল CSS)**

- 🖋️ **আলাদা `.css` ফাইলে CSS কোড লেখা হয় এবং তারপর সেই ফাইল HTML ফাইলে লিংক করা হয়।**
- **উদাহরণ:**
  ```html
  <link rel="stylesheet" href="styles.css">
  ```
- **ব্যবহার**: বড় ওয়েবসাইট বা প্রকল্পের জন্য, যেখানে একাধিক পৃষ্ঠায় একই CSS প্রয়োগ করা হয়।

---


# 🎨 CSS Properties 

# 📦 ১. Box Model, Display, Positioning

### ✅ color 
- **মান:** red, blue, #FF5733, rgb(255, 0, 0), rgba(255, 0, 0, 0.5)
- **বর্ণনা:** টেক্সটের রং নির্ধারণ করে।

```html
<p style="color: red;">এই টেক্সটটি লাল রঙের হবে</p>
<p style="color: rgb(0, 128, 0);">এই টেক্সটটি সবুজ রঙের হবে</p>
```

---

### ✅ background-color
- **মান:** red, #FF5733, rgb(255, 0, 0), transparent
- **বর্ণনা:** উপাদানের ব্যাকগ্রাউন্ডের রং নির্ধারণ করে।

```html
<div style="background-color: yellow; padding: 20px;">ব্যাকগ্রাউন্ড হলুদ</div>
```

---

### ✅ padding
- **মান:** 10px, 1rem, 20px 30px, 5%
- **বর্ণনা:** কনটেন্ট এবং উপাদানের বর্ডারের মধ্যে স্থান নির্ধারণ করে।

```html
<div style="padding: 20px; background-color: lightblue;">Padding সহ কনটেন্ট</div>
```

---

### ✅ margin
- **মান:** 10px, 1rem, 20px 30px, 5%
- **বর্ণনা:** উপাদানের বর্ডারের বাইরের স্থান নির্ধারণ করে।

```html
<div style="margin: 20px; background-color: lightgray;">Margin সহ কনটেন্ট</div>
```

---

### ✅ border
- **মান:** 1px solid black, 2px dashed #f00, 3px dotted blue
- **বর্ণনা:** উপাদানের চারপাশে বর্ডার নির্ধারণ করে।

```html
<div style="border: 2px solid red; padding: 10px;">Red Border</div>
```

---

### ✅ border-radius
- **মান:** 10px, 50%, 20px 30px
- **বর্ণনা:** উপাদানের কোণ গোলাকার করে।

```html
<div style="border-radius: 10px; background-color: lightgreen; padding: 20px;">Rounded Corners</div>
```

---

## ✍️ ২. Typography, Text Properties, Font

### ✅ font-size
- **মান:** 16px, 1rem, 2em, large, smaller
- **বর্ণনা:** ফন্টের আকার নির্ধারণ করে।

```html
<p style="font-size: 20px;">এই টেক্সটের ফন্ট সাইজ 20px</p>
```

---

### ✅ font-family
- **মান:** "Arial", "Helvetica", sans-serif
- **বর্ণনা:** টেক্সটের জন্য ফন্ট ফ্যামিলি নির্ধারণ করে।

```html
<p style="font-family: Arial, sans-serif;">এই টেক্সট Arial ফন্টে লেখা</p>
```

---

### ✅ font-weight
- **মান:** normal, bold, 100, 200, 300, ..., 900
- **বর্ণনা:** ফন্টের পুরুত্ব নির্ধারণ করে।

```html
<p style="font-weight: bold;">Bold টেক্সট</p>
```

---

### ✅ line-height
- **মান:** 1.5, 2, 20px, normal
- **বর্ণনা:** টেক্সটের লাইনগুলির মধ্যে উল্লম্ব দূরত্ব নির্ধারণ করে।

```html
<p style="line-height: 2;">এই টেক্সটের লাইন স্পেসিং বেশি</p>
```

---

### ✅ text-align
- **মান:** left, right, center, justify
- **বর্ণনা:** টেক্সটকে একটি উপাদানের মধ্যে অনুভূমিকভাবে সজ্জিত করে।

```html
<p style="text-align: center;">এই টেক্সটটি সেন্টারে থাকবে</p>
```

---

### ✅ text-decoration
- **মান:** none, underline, line-through, overline
- **বর্ণনা:** টেক্সটে ডেকোরেশন যোগ করে (যেমন আন্ডারলাইন বা স্ট্রাইকথ্রু)।

```html
<p style="text-decoration: underline;">এই টেক্সটের নিচে আন্ডারলাইন থাকবে</p>
<p style="text-decoration: line-through;">এই টেক্সট কাটা থাকবে</p>
```



 # 🧑‍🏫 CSS Layout Techniques: Flexbox & Grid Layout

# 💡 Flexbox (ফ্লেক্সবক্স)
- **Flexbox** (Flexible Box Layout) হল এক-মাত্রিক লেআউট মডেল, যা উপাদানগুলিকে অনুভূমিক (row) বা উল্লম্ব (column) অক্ষ বরাবর সজ্জিত করতে ব্যবহৃত হয়।
- **Flexbox এর মূল বৈশিষ্ট্য:**
  1. **display**
     - **মান:** flex, inline-flex
     - **বর্ণনা:** একটি কন্টেইনারকে ফ্লেক্সবক্স হিসেবে ঘোষণা করতে ব্যবহৃত হয়।
     ```html
     <div style="display: flex;">
         <div>আইটেম ১</div>
         <div>আইটেম ২</div>
         <div>আইটেম ৩</div>
     </div>
     ```

  2. **flex**
     - **মান:** 0 1 100px, 1 1 0, 2 1 100%
     - **বর্ণনা:** flex-grow, flex-shrink, এবং flex-basis নির্ধারণ করে।
     ```html
     <div style="display: flex;">
         <div style="flex: 1;">আইটেম ১</div>
         <div style="flex: 2;">আইটেম ২</div>
     </div>
     ```

  3. **justify-content** (প্রধান অক্ষে আইটেম সাজানো)
     - **মান:** flex-start, flex-end, center, space-between, space-around
     - **বর্ণনা:** ফ্লেক্স আইটেমগুলো প্রধান অক্ষ বরাবর কোথায় থাকবে তা নির্ধারণ করে।
     ```html
     <div style="display: flex; justify-content: space-between;">
         <div>আইটেম ১</div>
         <div>আইটেম ২</div>
         <div>আইটেম ৩</div>
     </div>
     ```

  4. **align-items** (ক্রস অক্ষে আইটেম সাজানো)
     - **মান:** flex-start, flex-end, center, stretch, baseline
     - **বর্ণনা:** ক্রস অক্ষ বরাবর ফ্লেক্স আইটেমগুলোর অবস্থান নির্ধারণ করে।
     ```html
     <div style="display: flex; align-items: center;">
         <div>আইটেম ১</div>
         <div>আইটেম ২</div>
     </div>
     ```

  5. **flex-direction**
     - **মান:** row, row-reverse, column, column-reverse
     - **বর্ণনা:** আইটেমগুলি কোন দিক বরাবর সাজানো হবে তা নির্ধারণ করে।
     ```html
     <div style="display: flex; flex-direction: column;">
         <div>আইটেম ১</div>
         <div>আইটেম ২</div>
     </div>
     ```

  6. **flex-wrap**
     - **মান:** nowrap, wrap, wrap-reverse
     - **বর্ণনা:** ফ্লেক্স আইটেমগুলো এক লাইনে থাকবে নাকি একাধিক লাইনে ব্রেক হবে তা নিয়ন্ত্রণ করে।
     ```html
     <div style="display: flex; flex-wrap: wrap;">
         <div>আইটেম ১</div>
         <div>আইটেম ২</div>
         <div>আইটেম ৩</div>
     </div>
     ```



 # 🖼️ Grid Layout (গ্রিড লেআউট)
- **Grid Layout** একটি দ্বি-মাত্রিক লেআউট সিস্টেম যা সারি (rows) এবং কলামের (columns) মাধ্যমে উপাদান সাজাতে ব্যবহৃত হয়। 
- এটি ফ্লেক্সবক্সের তুলনায় আরও নির্দিষ্ট লেআউট তৈরির জন্য উপযুক্ত।

## 🚀 Grid Layout এর প্রধান বৈশিষ্ট্যসমূহ:
1. **display**
   - **মান:** grid, inline-grid
   - **বর্ণনা:** একটি কন্টেইনারকে গ্রিড হিসেবে ঘোষণা করতে ব্যবহৃত হয়।
   ```html
   <div style="display: grid;">
       <div>আইটেম ১</div>
       <div>আইটেম ২</div>
       <div>আইটেম ৩</div>
   </div>
   ```

2. **grid-template-columns**
   - **মান:** repeat(3, 1fr), 200px 1fr, auto auto auto
   - **বর্ণনা:** গ্রিড কন্টেইনারের কলাম সংখ্যা এবং আকার নির্ধারণ করে।
   ```html
   <div style="display: grid; grid-template-columns: repeat(3, 1fr);">
       <div>আইটেম ১</div>
       <div>আইটেম ২</div>
       <div>আইটেম ৩</div>
   </div>
   ```

3. **grid-template-rows**
   - **মান:** auto, 100px, 1fr, repeat(3, 200px)
   - **বর্ণনা:** গ্রিড কন্টেইনারের সারির সংখ্যা এবং আকার নির্ধারণ করে।
   ```html
   <div style="display: grid; grid-template-rows: 100px 200px;">
       <div>আইটেম ১</div>
       <div>আইটেম ২</div>
   </div>
   ```

4. **gap (row-gap & column-gap)**
   - **মান:** 10px, 20px
   - **বর্ণনা:** গ্রিডের সারি ও কলামের মধ্যে ফাঁকা নির্ধারণ করে।
   ```html
   <div style="display: grid; gap: 20px;">
       <div>আইটেম ১</div>
       <div>আইটেম ২</div>
   </div>
   ```

5. **justify-items**
   - **মান:** start, end, center, stretch
   - **বর্ণনা:** প্রতিটি গ্রিড আইটেমের অনুভূমিক অবস্থান নির্ধারণ করে।
   ```html
   <div style="display: grid; justify-items: center;">
       <div>আইটেম ১</div>
       <div>আইটেম ২</div>
   </div>
   ```

6. **align-items**
   - **মান:** start, end, center, stretch
   - **বর্ণনা:** প্রতিটি গ্রিড আইটেমের উল্লম্ব অবস্থান নির্ধারণ করে।
   ```html
   <div style="display: grid; align-items: center;">
       <div>আইটেম ১</div>
       <div>আইটেম ২</div>
   </div>
   ```

7. **grid-auto-flow**
   - **মান:** row, column, row dense, column dense
   - **বর্ণনা:** গ্রিড আইটেমগুলো কীভাবে স্বয়ংক্রিয়ভাবে সাজানো হবে তা নিয়ন্ত্রণ করে।
   ```html
   <div style="display: grid; grid-auto-flow: column;">
       <div>আইটেম ১</div>
       <div>আইটেম ২</div>
   </div>
   ```

## ⚖️ Flexbox বনাম Grid Layout:
- **Flexbox** এক-মাত্রিক লেআউট সিস্টেম এবং এটি শুধুমাত্র অনুভূমিক বা উল্লম্বভাবে উপাদানগুলি সাজাতে পারে।
- **Grid Layout** একটি দ্বি-মাত্রিক লেআউট সিস্টেম, যা কলাম এবং সারি নিয়ে কাজ করে এবং আরও জটিল লেআউট তৈরি করতে সাহায্য করে।

---




## 🔀 Flexbox vs Grid: পার্থক্য

| **বৈশিষ্ট্য**              | **Flexbox**                                   | **Grid**                               |
|-------------------------|---------------------------------------------|---------------------------------------|
| **লেআউটের ধরন**           | এক-মাত্রিক (row বা column)                   | দ্বি-মাত্রিক (row এবং column)          |
| **প্রধান ব্যবহার**         | কন্টেন্ট সজ্জিত করা                         | পূর্ণ পৃষ্ঠার লেআউট তৈরি করা          |
| **Row & Column**          | শুধুমাত্র একটি দিক (row বা column)          | উভয় দিক (row এবং column)             |
| **গ্যাপ ব্যবস্থাপনা**      | margin ও padding প্রয়োজন                   | gap, row-gap, column-gap সহজেই ব্যবহৃত হয় |
| **জটিলতা**               | অপেক্ষাকৃত সহজ                              | অপেক্ষাকৃত জটিল                        |

## 🧑‍💻 উপসংহার:
- **Flexbox** ছোট লেআউট এবং উপাদানগুলি সাজানোর জন্য উপযুক্ত। 
- **Grid** সম্পূর্ণ ওয়েবসাইট লেআউট বা জটিল ডিজাইন ব্যবস্থাপনার জন্য আরও কার্যকর।

--- 





 ## 🧑‍💻 Positioning, Overflow, Visibility

1. **position**
- মান: `static`, `relative`, `absolute`, `fixed`, `sticky`
- বর্ণনা: উপাদানের অবস্থান নির্ধারণ করে। 
- উদাহরণ: 
  ```css
  .box {
      position: absolute;
      top: 20px;
      left: 30px;
  }
  ```

2. **top, right, bottom, left**
- মান: `10px`, `20%`, `auto`, `0`
- বর্ণনা: উপাদানটি যে প্রান্ত থেকে শুরু হবে তা নির্ধারণ করে।
- উদাহরণ:
  ```css
  .box {
      position: relative;
      top: 10px;
      left: 20px;
  }
  ```

3. **z-index**
- মান: `1`, `10`, `100`, `auto`
- বর্ণনা: উপাদানগুলির স্তরের অর্ডার নির্ধারণ করে (এটি position ছাড়া অন্য কোন মানে কাজ করে না)।
- উদাহরণ:
  ```css
  .box1 {
      position: absolute;
      z-index: 10;
  }
  .box2 {
      position: absolute;
      z-index: 5;
  }
  ```

4. **overflow**
- মান: `visible`, `hidden`, `scroll`, `auto`
- বর্ণনা: উপাদানের বক্সের বাইরে যদি কনটেন্ট চলে যায় তবে কী হবে তা নির্ধারণ করে।
- উদাহরণ:
  ```css
  .box {
      width: 200px;
      height: 100px;
      overflow: scroll;
  }
  ```

5. **opacity**
- মান: `1`, `0.5`, `0`, `0.75`
- বর্ণনা: উপাদানের স্বচ্ছতা নির্ধারণ করে (0 পুরোপুরি স্বচ্ছ, 1 পুরোপুরি অস্বচ্ছ)।
- উদাহরণ:
  ```css
  .box {
      opacity: 0.5;
  }
  ```




 ## 🎨 Effects and Transitions

1. **box-shadow**
- মান: `2px 2px 5px rgba(0, 0, 0, 0.5)`, `0 4px 8px rgba(0, 0, 0, 0.3)`
- বর্ণনা: উপাদানের চারপাশে ছায়া প্রভাব যোগ করে।
- উদাহরণ:
  ```css
  .box {
      box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);
  }
  ```

2. **text-shadow**
- মান: `2px 2px 5px rgba(0, 0, 0, 0.5)`, `1px 1px 3px red`
- বর্ণনা: টেক্সটে ছায়া প্রভাব যোগ করে।
- উদাহরণ:
  ```css
  .text {
      text-shadow: 1px 1px 3px red;
  }
  ```

3. **transition**
- মান: `all 0.3s ease`, `opacity 0.5s linear`, `transform 1s`
- বর্ণনা: উপাদানের প্রপার্টি পরিবর্তন হলে কীভাবে অ্যানিমেশন হবে তা নির্ধারণ করে।
- উদাহরণ:
  ```css
  .box {
      transition: all 0.3s ease;
  }
  .box:hover {
      background-color: blue;
  }
  ```

4. **transform**
- মান: `rotate(45deg)`, `scale(1.2)`, `translateX(50px)`, `skewY(30deg)`
- বর্ণনা: উপাদানকে ঘোরানো, স্কেল করা, স্থানান্তর করা বা বেঁকে দেওয়া ইত্যাদি করে।
- উদাহরণ:
  ```css
  .box {
      transform: rotate(45deg);
  }
  .box:hover {
      transform: scale(1.2);
  }
  ```




 ## ✨ Text Styles and Spacing

1. **font-style**
- মান: `normal`, `italic`, `oblique`
- বর্ণনা: ফন্টের স্টাইল (যেমন নর্মাল বা ইটালিক) নির্ধারণ করে।
- উদাহরণ:
  ```css
  .text {
      font-style: italic;
  }
  ```

2. **font-variant**
- মান: `normal`, `small-caps`
- বর্ণনা: টেক্সটের ভ্যারিয়েন্ট (যেমন স্মল ক্যাপস) নির্ধারণ করে।
- উদাহরণ:
  ```css
  .text {
      font-variant: small-caps;
  }
  ```

3. **letter-spacing**
- মান: `1px`, `0.1em`, `0.05rem`
- বর্ণনা: টেক্সটের মধ্যে অক্ষরের মধ্যে স্পেস নির্ধারণ করে।
- উদাহরণ:
  ```css
  .text {
      letter-spacing: 1px;
  }
  ```

4. **word-spacing**
- মান: `1px`, `0.1em`, `0.05rem`
- বর্ণনা: টেক্সটের মধ্যে শব্দের মধ্যে স্পেস নির্ধারণ করে।
- উদাহরণ:
  ```css
  .text {
      word-spacing: 0.1em;
  }
  ```


 ## ২. CSS এর ধরন

১. **Inline CSS**
- সরাসরি HTML ট্যাগে লেখা হয়।
- উদাহরণ:
  ```html
  <p style="color: red;">This is inline CSS</p>
  ```

২. **Internal CSS**
- `<style>` ট্যাগের ভিতরে লেখা হয়।
- উদাহরণ:
  ```html
  <style>
      p { color: blue; }
  </style>
  ```

৩. **External CSS**
- আলাদা `.css` ফাইলে লেখা হয়।
- উদাহরণ:
  ```css
  p { color: green; }
  <link rel="stylesheet" href="styles.css">
  ```

## ৩. CSS Selectors (নির্বাচক)
- `*` → সব এলিমেন্ট
- `p` → নির্দিষ্ট এলিমেন্ট
- `.class` → নির্দিষ্ট ক্লাস
- `#id` → নির্দিষ্ট আইডি
- `div > p` → নির্দিষ্ট শিশুর এলিমেন্ট
- `div p` → অভ্যন্তরীণ এলিমেন্ট

## ৪. গুরুত্বপূর্ণ CSS Attributes (গুণাবলী)

### ১. টেক্সট ও ফন্ট
- `color: red;` → টেক্সটের রং পরিবর্তন
- `font-size: 16px;` → ফন্টের আকার নির্ধারণ
- `font-family: Arial, sans-serif;` → ফন্ট টাইপ নির্ধারণ
- `font-weight: bold;` → ফন্ট মোটা করা
- `text-align: center;` → টেক্সটের অবস্থান নির্ধারণ
- `text-decoration: underline;` → টেক্সটের নিচে দাগ
- `letter-spacing: 2px;` → অক্ষরের মধ্যে ফাঁকা
- `line-height: 1.5;` → লাইন স্পেসিং নির্ধারণ

কেন ব্যবহার করা হয়?
- ওয়েবসাইটের লেখা আরো সুন্দর ও পড়তে সহজ করতে।
- আলাদা আলাদা সেকশনে ভিন্ন টেক্সট স্টাইল দিতে।

### ২. ব্যাকগ্রাউন্ড ও বর্ডার
- `background-color: yellow;` → ব্যাকগ্রাউন্ড রং পরিবর্তন
- `background-image: url('image.jpg');` → ব্যাকগ্রাউন্ড ইমেজ যোগ করা
- `background-size: cover;` → ইমেজের আকার নিয়ন্ত্রণ
- `border: 2px solid black;` → বর্ডার নির্ধারণ
- `border-radius: 10px;` → বর্ডার গোল করা
- `box-shadow: 5px 5px 10px gray;` → ছায়া যোগ করা

কেন ব্যবহার করা হয়?
- UI ডিজাইন উন্নত করতে।
- কন্টেন্টকে আলাদা করে দেখাতে।

### ৩. বক্স মডেল (মার্জিন, প্যাডিং, উচ্চতা, প্রস্থ)
- `width: 300px;` → প্রস্থ নির্ধারণ
- `height: 200px;` → উচ্চতা নির্ধারণ
- `margin: 20px;` → বাহিরের ফাঁকা
- `padding: 10px;` → ভিতরের ফাঁকা

কেন ব্যবহার করা হয়?
- এলিমেন্টের সঠিক আকৃতি ও অবস্থান ঠিক করতে।

### ৪. ফ্লেক্সবক্স (Flexbox)
- `display: flex;` → ফ্লেক্সবক্স সক্রিয়
- `justify-content: center;` → অনুভূমিকভাবে কেন্দ্রীয়করণ
- `align-items: center;` → উল্লম্বভাবে কেন্দ্রীয়করণ
- `flex-wrap: wrap;` → আইটেম ব্রেক করা

কেন ব্যবহার করা হয়?
- রেস্পন্সিভ ডিজাইনের জন্য।
- এলিমেন্ট গুলোকে সহজে স্থানান্তর করতে।

### ৫. গ্রিড (CSS Grid)
- `display: grid;` → গ্রিড সক্রিয়
- `grid-template-columns: repeat(3, 1fr);` → ৩ কলাম তৈরি
- `grid-gap: 10px;` → গ্রিড ফাঁকা

কেন ব্যবহার করা হয়?
- কমপ্লেক্স লেআউট ডিজাইন করার জন্য।

### ৬. পজিশনিং (Positioning)
- `position: absolute;` → নির্দিষ্ট স্থান
- `position: relative;` → আপেক্ষিক স্থান
- `position: fixed;` → স্ক্রল পরিবর্তন হবে না
- `top: 20px;` → উপরে স্থানান্তর

কেন ব্যবহার করা হয়?
- এলিমেন্টের অবস্থান নিয়ন্ত্রণ করতে।

### ৭. CSS এনিমেশন (Animation)
```css
@keyframes move {
    0% { transform: translateX(0); }
    100% { transform: translateX(100px); }
}

.animation {
    animation: move 2s infinite alternate;
}
```

কেন ব্যবহার করা হয়?
- ওয়েবসাইটকে আরো আকর্ষণীয় করতে।

### ৮. CSS ট্রানজিশন (Transition)
```css
div {
    transition: all 0.5s ease-in-out;
}

div:hover {
    background-color: red;
}
```

কেন ব্যবহার করা হয়?
- হোভার ইফেক্ট তৈরি করতে।


# ৩. **বিভিন্ন মিডিয়া কুয়েরি ভ্যারিয়েশন (Different Media Query Variations)**

## ১. **স্মার্টফোন (Mobile Devices)**
 - 📱 ৪৮০px বা এর কম স্ক্রিনের জন্য

```css
/* Default styles for larger screens (desktops) */
    body {
        background-color: lightblue;
        font-size: 18px;
    }

    /* Media query for mobile devices (480px or less) */
    @media (max-width: 480px) {
        body {
            background-color: lightcoral;
            font-size: 14px;
        }
    }
```

## ২. **ট্যাবলেট (Tablets)**
 - 📲 ৪৮০px - ৭৬৮px স্ক্রিনের জন্য

```css
/* Media query for tablets (481px to 768px) */
    @media (min-width: 481px) and (max-width: 768px) {
        body {
            background-color: lightgreen;
            font-size: 16px;
        }
    }

```
## ৩. **ছোট ল্যাপটপ বা ছোট ডেস্কটপ (Small Laptops & Desktops)**
 - 💻 ৭৬৯px - ১০২৪px স্ক্রিনের জন্য
```css

/* Media query for small laptops or desktops (769px to 1024px) */
    @media (min-width: 769px) and (max-width: 1024px) {
        body {
            background-color: lightyellow;
            font-size: 17px;
        }
    }
```


## ৪. **ডেস্কটপ (Desktops)**
 - 🖥️ ১০২৫px বা তার বেশি স্ক্রিনের জন্য

```css
/* Media query for desktops (1025px or larger) */
    @media (min-width: 1025px) {
        body {
            background-color: lightblue;
            font-size: 18px;
        }
    }
```






# ১. **CSS ভ্যারিয়েবল (CSS Variables)**

- **CSS ভ্যারিয়েবল** হল এমন একটি ফিচার যা CSS-এর মধ্যে পুনঃব্যবহারযোগ্য মান সংরক্ষণ করতে সাহায্য করে।
- CSS ভ্যারিয়েবল সাধারণত `--` দিয়ে শুরু হয় এবং তাদের মান `var()` ফাংশনের মাধ্যমে রেফার করা হয়।

---

২. **ভ্যারিয়েবল ডিক্লেয়ার (Variable Declaration)**

- ভ্যারিয়েবল ডিক্লেয়ার করতে **`--`** চিহ্ন দিয়ে নাম নির্ধারণ করতে হয় এবং তারপর **`:`** দিয়ে মান দেওয়া হয়।
- **উদাহরণ:**
  ```css
  :root {
      --primary-color: #3498db;
      --font-size: 16px;
  }
  ```
  - এখানে `--primary-color` এবং `--font-size` দুটি CSS ভ্যারিয়েবল ডিক্লেয়ার করা হয়েছে।

---

৩. **ভ্যারিয়েবল ব্যবহার (Using Variables)**

- ভ্যারিয়েবল ব্যবহার করতে **`var()`** ফাংশন ব্যবহার করতে হয়।
- **উদাহরণ:**
  ```css
  body {
      background-color: var(--primary-color);
      font-size: var(--font-size);
  }
  ```
  - এখানে `--primary-color` এবং `--font-size` ভ্যারিয়েবলগুলি ব্যবহার করা হয়েছে।

---

৪. **ভ্যারিয়েবল স্কোপ (Variable Scope)**

- ভ্যারিয়েবলগুলো সাধারণত `:root` সিলেক্টরের মধ্যে ডিক্লেয়ার করলে পুরো ডকুমেন্টে অ্যাক্সেসযোগ্য থাকে।
- যদি একটি ভ্যারিয়েবল নির্দিষ্ট একটি এলিমেন্টে ডিক্লেয়ার করা হয়, তবে সেটি শুধুমাত্র সেই এলিমেন্ট এবং তার শিশুদের জন্য প্রযোজ্য হবে।
- **উদাহরণ:**
  ```css
  .container {
      --container-width: 1000px;
  }
  
  .box {
      width: var(--container-width);
  }
  ```

---

৫. **দ্বৈত ভ্যারিয়েবল (Fallback Values)**

- **`var()`** ফাংশনের সাথে একটি ডিফল্ট মান দেওয়া যায়, যদি ভ্যারিয়েবলটি না পাওয়া যায়।
- **উদাহরণ:**
  ```css
  p {
      color: var(--text-color, black);
  }
  ```
  - এখানে, যদি `--text-color` ভ্যারিয়েবলটি না থাকে, তাহলে `black` রঙটি ব্যবহৃত হবে।

---

৬. **প্লেটফর্মে CSS ভ্যারিয়েবল সাপোর্ট**

- CSS ভ্যারিয়েবল আধুনিক ব্রাউজারগুলিতে সাপোর্ট পায়, তবে পুরনো ব্রাউজারগুলোতে এটি কাজ নাও করতে পারে।
- সুতরাং, পুরনো ব্রাউজার সাপোর্টের জন্য ফলোব্যাক ব্যবহারের পরামর্শ দেওয়া হয়।

# ১. **CSS শর্থ্যান্ড (CSS Shorthand)**


## ১. **CSS শর্থ্যান্ড (CSS Shorthand)**

# - CSS শর্থ্যান্ড হল একটি পদ্ধতি, যেখানে একাধিক প্রোপার্টি একসাথে এক লাইনে লেখা হয়, যাতে কোড আরও কম্প্যাক্ট এবং পড়তে সহজ হয়।

---

## ২. **মার্জিন (Margin)**

- **শর্থ্যান্ড সিনট্যাক্স:**
  ```css
  margin: top right bottom left;
  ```
- **উদাহরণ:**
  ```css
  margin: 10px 20px 30px 40px;
  ```
  - এখানে, উপরে 10px, ডানে 20px, নিচে 30px এবং বামে 40px মার্জিন দেয়া হয়েছে।

- **যদি দুটি মান দেয়া হয়:**
  ```css
  margin: 10px 20px;
  ```
  - এখানে, উপরে এবং নিচে 10px মার্জিন এবং ডানে এবং বামে 20px মার্জিন দেয়া হয়েছে।

- **একটি মান দিলে:**
  ```css
  margin: 10px;
  ```
  - এখানে, সব চারটি দিকেই 10px মার্জিন দেয়া হয়েছে।

---

## ৩. **প্যাডিং (Padding)**

- **শর্থ্যান্ড সিনট্যাক্স:**
  ```css
  padding: top right bottom left;
  ```
- **উদাহরণ:**
  ```css
  padding: 10px 20px 30px 40px;
  ```
  - এখানে, উপরে 10px, ডানে 20px, নিচে 30px এবং বামে 40px প্যাডিং দেয়া হয়েছে।

- **যদি দুটি মান দেয়া হয়:**
  ```css
  padding: 10px 20px;
  ```
  - এখানে, উপরে এবং নিচে 10px প্যাডিং এবং ডানে এবং বামে 20px প্যাডিং দেয়া হয়েছে।

- **একটি মান দিলে:**
  ```css
  padding: 10px;
  ```
  - এখানে, সব চারটি দিকেই 10px প্যাডিং দেয়া হয়েছে।

---

## ৪. **বর্ডার (Border)**

- **শর্থ্যান্ড সিনট্যাক্স:**
  ```css
  border: width style color;
  ```
- **উদাহরণ:**
  ```css
  border: 2px solid red;
  ```
  - এখানে, বর্ডারের প্রস্থ 2px, স্টাইল `solid` এবং রঙ `red` দেয়া হয়েছে।

- **আরো শর্টহ্যান্ড বিকল্প:**
  ```css
  border: 1px dashed blue;
  ```
  - এখানে, বর্ডারের প্রস্থ 1px, স্টাইল `dashed` এবং রঙ `blue`।

---

## ৫. **ফন্ট (Font)**

- **শর্থ্যান্ড সিনট্যাক্স:**
  ```css
  font: font-style font-variant font-weight font-size line-height font-family;
  ```
- **উদাহরণ:**
  ```css
  font: italic small-caps bold 16px/20px Arial, sans-serif;
  ```
  - এখানে, ফন্ট স্টাইল `italic`, ফন্ট ভেরিয়েন্ট `small-caps`, ফন্ট ওয়েট `bold`, ফন্ট সাইজ `16px`, লাইন হাইট `20px`, এবং ফন্ট ফ্যামিলি `Arial, sans-serif` দেয়া হয়েছে।

---

## ৬. **লিস্ট (List)**

- **শর্থ্যান্ড সিনট্যাক্স:**
  ```css
  list-style: type position image;
  ```
- **উদাহরণ:**
  ```css
  list-style: square inside url('image.jpg');
  ```
  - এখানে, লিস্টের আইটেম `square` টাইপ, `inside` পজিশন এবং আইটেমের সামনে একটি ছবি `url('image.jpg')` দেয়া হয়েছে।

---

## ৭. **পজিশনিং (Positioning)**

- **শর্থ্যান্ড সিনট্যাক্স:**
  ```css
  position: type top right bottom left;
  ```
- **উদাহরণ:**
  ```css
  position: absolute 10px 20px 30px 40px;
  ```
  - এখানে, `absolute` পজিশনিং দেয়া হয়েছে, এবং উপরে 10px, ডানে 20px, নিচে 30px এবং বামে 40px স্থানান্তরিত করা হয়েছে।

---

## ৮. **ট্রান্সফর্ম (Transform)**

- **শর্থ্যান্ড সিনট্যাক্স:**
  ```css
  transform: translate(x, y) rotate(angle) scale(x, y) skew(x, y);
  ```
- **উদাহরণ:**
  ```css
  transform: rotate(45deg) scale(1.2);
  ```
  - এখানে, 45° রোটেট করা হয়েছে এবং স্কেল 1.2x করা হয়েছে।

---

## ৯. **ট্রানজিশন (Transition)**

- **শর্থ্যান্ড সিনট্যাক্স:**
  ```css
  transition: property duration timing-function delay;
  ```
- **উদাহরণ:**
  ```css
  transition: all 0.3s ease-in-out 0s;
  ```
  - এখানে, সব প্রোপার্টি 0.3 সেকেন্ডে ট্রানজিশন হবে, এবং `ease-in-out` টাইমিং ফাংশন ব্যবহৃত হবে।

---

## ১০. **ওভারফ্লো (Overflow)**

- **শর্থ্যান্ড সিনট্যাক্স:**
  ```css
  overflow: visible hidden scroll auto;
  ```
- **উদাহরণ:**
  ```css
  overflow: hidden;
  ```
  - এখানে, অতিরিক্ত কন্টেন্ট লুকানো হয়েছে।

---

## ১১. **গ্রিড (Grid)**

- **শর্তহ্যান্ড সিনট্যাক্স:**
  ```css
  grid: rows columns gap;
  ```
- **উদাহরণ:**
  ```css
  grid: 1fr 1fr 1fr / 1fr 1fr 1fr;
  ```
  - এখানে, ৩টি সারি এবং ৩টি কলাম তৈরি করা হয়েছে।

---

# ১২. **ফ্লেক্সবক্স (Flexbox)**

- **শর্তহ্যান্ড সিনট্যাক্স:**
  ```css
  flex: flex-grow flex-shrink flex-basis;
  ```
- **উদাহরণ:**
  ```css
  flex: 1 1 100px;
  ```
  - এখানে, এলিমেন্টটি বেড়ে যাবে এবং কমে যাবে, এবং বেসিস সাইজ 100px থাকবে।
