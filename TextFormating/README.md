# 📝 Text Formatting in HTML & CSS — Concepts + Interview Questions

---

# 📌 1. HTML Text Formatting Tags

HTML provides tags to **format text semantically and visually**

---

## 🔥 Common Text Formatting Tags

```html
<b>Bold</b>
<strong>Important</strong>
<i>Italic</i>
<em>Emphasis</em>
<u>Underline</u>
<mark>Highlight</mark>
<small>Small Text</small>
<del>Deleted</del>
<ins>Inserted</ins>
<sub>Subscript</sub>
<sup>Superscript</sup>
```

---

## 🔍 Examples

```html
<p>
  <strong>Important</strong> text and <em>emphasized</em> word.
</p>

<p>
  H<sub>2</sub>O and E = mc<sup>2</sup>
</p>
```

---

## ⚔️ Semantic vs Non-Semantic

| Semantic   | Non-Semantic |
| ---------- | ------------ |
| `<strong>` | `<b>`        |
| `<em>`     | `<i>`        |

👉 Semantic tags add **meaning (SEO + accessibility)**

---

# 📌 2. CSS Text Formatting

CSS controls **how text looks**

---

## 🔥 Common CSS Properties

---

## 1️⃣ Text Color

```css
p {
  color: red;
}
```

---

## 2️⃣ Text Alignment

```css
h1 {
  text-align: center;
}
```

---

## 3️⃣ Text Decoration

```css
a {
  text-decoration: none;
}
```

Values:

* `underline`
* `line-through`
* `overline`

---

## 4️⃣ Text Transform

```css
p {
  text-transform: uppercase;
}
```

Values:

* uppercase
* lowercase
* capitalize

---

## 5️⃣ Letter Spacing

```css
p {
  letter-spacing: 2px;
}
```

---

## 6️⃣ Line Height

```css
p {
  line-height: 1.5;
}
```

---

## 7️⃣ Word Spacing

```css
p {
  word-spacing: 5px;
}
```

---

## 8️⃣ Font Size & Weight

```css
p {
  font-size: 16px;
  font-weight: bold;
}
```

---

## 9️⃣ Font Family

```css
p {
  font-family: Arial, sans-serif;
}
```

---

## 🔟 Text Shadow

```css
h1 {
  text-shadow: 2px 2px 5px gray;
}
```

---

# ⚡ Example (Combined)

```html
<p class="text">
  Hello World
</p>
```

```css
.text {
  color: blue;
  text-align: center;
  text-transform: uppercase;
  letter-spacing: 2px;
  line-height: 1.5;
}
```

---

# 🧠 Interview Questions

---

## 🟢 Beginner

### 1️⃣ Difference between `<b>` and `<strong>`?

👉 `<b>` → visual
👉 `<strong>` → semantic importance

---

### 2️⃣ Difference between `<i>` and `<em>`?

👉 `<i>` → style
👉 `<em>` → meaning (emphasis)

---

### 3️⃣ What is `<sub>` and `<sup>`?

👉 Subscript and superscript

---

### 4️⃣ What is `text-align`?

👉 Aligns text (left, right, center)

---

## 🟡 Intermediate

---

### 5️⃣ What is `text-decoration`?

👉 Adds/removes underline, etc.

---

### 6️⃣ Difference between `display: none` and `visibility: hidden`?

* none → removed from layout
* hidden → still occupies space

---

### 7️⃣ What is `text-transform`?

👉 Changes case of text

---

### 8️⃣ What is line-height?

👉 Controls vertical spacing between lines

---

## 🔴 Advanced

---

### 9️⃣ Difference between `letter-spacing` and `word-spacing`?

* letter-spacing → space between characters
* word-spacing → space between words

---

### 🔟 What is `text-shadow`?

👉 Adds shadow to text

---

### 1️⃣1️⃣ How does font fallback work?

```css
font-family: Arial, Helvetica, sans-serif;
```

👉 Browser picks first available font

---

### 1️⃣2️⃣ What is white-space property?

```css
white-space: nowrap;
```

👉 Controls text wrapping

---

# 💣 Tricky Questions

---

### ❓ Which is better?

```html
<b>Important</b>
<strong>Important</strong>
```

👉 ✅ `<strong>` (semantic)

---

### ❓ Why avoid too much inline styling?

👉 Hard to maintain, not reusable

---

### ❓ What happens?

```css
text-transform: uppercase;
```

👉 Only changes display, not actual data

---

### ❓ Can CSS replace HTML formatting tags?

👉 Yes (mostly), but semantic HTML is still important

---

# 🧠 Pro Tips

* Prefer semantic tags (`<strong>`, `<em>`)
* Use CSS for styling, not HTML
* Keep typography consistent
* Use `line-height` for readability

---

# 🎯 Summary

* HTML → structure + meaning
* CSS → styling + layout
* Semantic tags improve SEO & accessibility

---

💡 Master this → strong frontend + UI foundation 🚀
