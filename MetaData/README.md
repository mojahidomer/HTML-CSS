# 🌐 Meta Tags, Styles & Scripts (HTML) — Concepts + Interview Questions

---

# 📌 1. Meta Data (Meta Tags)

## 🔥 What is Metadata?

👉 **Metadata = data about data**

In HTML, `<meta>` tags provide **information about the page** (not visible on UI).

---

## ✅ Common Meta Tags

```html
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<meta name="description" content="This is my website" />
<meta name="keywords" content="HTML, CSS, JavaScript" />
<meta name="author" content="Mojahid" />
```

---

## 🔍 Important Meta Tags Explained

### 🔹 Charset

```html
<meta charset="UTF-8" />
```

👉 Defines character encoding (supports all languages)

---

### 🔹 Viewport (VERY IMPORTANT)

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

👉 Makes site **responsive on mobile**

---

### 🔹 Description

```html
<meta name="description" content="Best React course" />
```

👉 Used by search engines (SEO)

---

### 🔹 Keywords

👉 Earlier used for SEO (less important now)

---

# 🧠 Why Meta Tags Matter?

* SEO optimization
* Responsive design
* Browser behavior control
* Social sharing (Open Graph)

---

# 📌 2. Styles in HTML

## 🔥 What is Styling?

👉 Styling defines **how HTML looks**

---

## ✅ Types of CSS

### 1️⃣ Inline CSS

```html
<h1 style="color: red;">Hello</h1>
```

❌ Not recommended (hard to maintain)

---

### 2️⃣ Internal CSS

```html
<style>
  h1 {
    color: blue;
  }
</style>
```

👉 Inside `<head>`

---

### 3️⃣ External CSS (Best)

```html
<link rel="stylesheet" href="styles.css" />
```

✔ Reusable
✔ Clean code
✔ Best practice

---

## ⚡ CSS Priority (Important)

```id="priority-order"
Inline > Internal > External
```

---

# 📌 3. Scripts in HTML

## 🔥 What is Script?

👉 JavaScript used to make page **interactive**

---

## ✅ Adding Script

### 1️⃣ Inline Script

```html
<script>
  alert("Hello");
</script>
```

---

### 2️⃣ External Script

```html
<script src="app.js"></script>
```

✔ Best practice

---

## ⚡ Script Loading (VERY IMPORTANT)

### ❌ Normal Script

```html
<script src="app.js"></script>
```

👉 Blocks HTML parsing

---

### ✅ Async

```html
<script async src="app.js"></script>
```

👉 Loads parallel
👉 Executes immediately
👉 Order not guaranteed

---

### ✅ Defer (BEST)

```html
<script defer src="app.js"></script>
```

👉 Loads parallel
👉 Executes after HTML parsing
👉 Order maintained

---

# ⚔️ Async vs Defer

| Feature   | Async               | Defer             |
| --------- | ------------------- | ----------------- |
| Execution | Immediately         | After HTML        |
| Order     | Not guaranteed      | Maintained        |
| Use Case  | Independent scripts | Dependent scripts |

---

# 📌 Placement of Scripts

👉 Best practice:

```html
<script defer src="app.js"></script>
```

OR

```html
<body>
  ...
  <script src="app.js"></script>
</body>
```

---

# 🧠 Interview Questions

---

## 🟢 Beginner

### 1️⃣ What is a meta tag?

👉 Provides metadata about HTML document

---

### 2️⃣ Why use viewport meta tag?

👉 To make website responsive

---

### 3️⃣ Difference between inline and external CSS?

* Inline → inside tag
* External → separate file

---

### 4️⃣ What is `<script>` tag?

👉 Used to include JavaScript

---

## 🟡 Intermediate

---

### 5️⃣ Difference between async and defer?

👉 Async = no order
👉 Defer = ordered execution after parsing

---

### 6️⃣ Why external CSS is preferred?

* Reusability
* Performance
* Maintainability

---

### 7️⃣ What happens if script is in `<head>` without defer?

👉 Blocks page rendering ❌

---

### 8️⃣ What is SEO role of meta tags?

👉 Helps search engines understand page

---

## 🔴 Advanced

---

### 9️⃣ Critical rendering path impact of CSS & JS?

* CSS blocks rendering
* JS blocks parsing

---

### 🔟 Why defer is preferred in modern apps?

* Non-blocking
* Better performance
* Maintains order

---

### 1️⃣1️⃣ What is Open Graph meta tags?

```html
<meta property="og:title" content="My Page" />
```

👉 Used for social media sharing preview

---

### 1️⃣2️⃣ How browsers handle CSS vs JS loading?

* CSS → render-blocking
* JS → parser-blocking

---

# 💣 Tricky Questions

---

### ❓ What happens here?

```html
<script src="a.js"></script>
<script src="b.js"></script>
```

👉 `b.js` waits for `a.js`

---

### ❓ What about async?

```html
<script async src="a.js"></script>
<script async src="b.js"></script>
```

👉 Order not guaranteed ⚠️

---

### ❓ Can CSS block JS?

👉 Yes, if JS depends on CSSOM

---

### ❓ Why avoid inline CSS?

* Poor performance
* Hard to maintain

---

# 🧠 Pro Tips

* Always use:

  ```html
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  ```
* Prefer **external CSS**
* Use **defer for scripts**
* Optimize loading for performance

---

# 🎯 Summary

* Meta → page info (SEO, responsive)
* CSS → styling
* JS → interactivity
* Defer → best for performance

---

💡 Master this → strong foundation for frontend + React interviews 🚀
