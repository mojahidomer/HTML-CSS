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


# 📘 HTML & CSS Text Formatting (Complete Guide)

---

# 🧾 1. HTML Text Formatting Tags

HTML text formatting tags are used to define the **structure and meaning (semantic)** of text.

## 🔹 Common Tags

```html
<b>Bold Text</b>
<strong>Important Text</strong>

<i>Italic Text</i>
<em>Emphasized Text</em>

<u>Underlined Text</u>

<mark>Highlighted Text</mark>

<small>Smaller Text</small>

<del>Deleted Text</del>

<ins>Inserted Text</ins>

H<sub>2</sub>O
x<sup>2</sup>
```

---

## 🔹 Explanation

| Tag        | Meaning        | Notes                     |
| ---------- | -------------- | ------------------------- |
| `<b>`      | Bold           | Only visual               |
| `<strong>` | Important text | Semantic + SEO            |
| `<i>`      | Italic         | Only visual               |
| `<em>`     | Emphasis       | Screen readers support    |
| `<u>`      | Underline      | Avoid for links confusion |
| `<mark>`   | Highlight      | Yellow background         |
| `<small>`  | Smaller text   | Less important text       |
| `<del>`    | Deleted text   | Strikethrough             |
| `<ins>`    | Inserted text  | Underlined                |
| `<sub>`    | Subscript      | Example: H₂O              |
| `<sup>`    | Superscript    | Example: x²               |

---

## 🔥 Key Differences

### ✅ `<b>` vs `<strong>`

* `<b>` → Styling only
* `<strong>` → Meaning + Accessibility + SEO

### ✅ `<i>` vs `<em>`

* `<i>` → Styling only
* `<em>` → Emphasis (semantic)

---

# 🎨 2. CSS Text Formatting

CSS is used to **style text visually**.

---

## 🔹 Basic Example

```css
p {
  color: blue;
  font-size: 16px;
  font-weight: bold;
  text-align: center;
  text-decoration: underline;
  text-transform: uppercase;
  letter-spacing: 2px;
  line-height: 1.5;
}
```

---

## 🔹 Important Properties

### 1. Color & Size

```css
color: red;
font-size: 18px;
```

### 2. Font Styling

```css
font-weight: bold;
font-style: italic;
```

### 3. Alignment

```css
text-align: left | center | right | justify;
```

### 4. Decoration

```css
text-decoration: underline;
text-decoration: line-through;
text-decoration: none;
```

### 5. Transform

```css
text-transform: uppercase;
text-transform: lowercase;
text-transform: capitalize;
```

### 6. Spacing

```css
letter-spacing: 2px;
word-spacing: 5px;
line-height: 1.6;
```

---

# ⚖️ HTML vs CSS

| Feature       | HTML       | CSS                 |
| ------------- | ---------- | ------------------- |
| Purpose       | Structure  | Styling             |
| Example       | `<strong>` | `font-weight: bold` |
| SEO           | Yes        | No                  |
| Accessibility | Yes        | No                  |
| Flexibility   | Low        | High                |

---

# 💡 Best Practice

👉 Use HTML for **meaning**
👉 Use CSS for **design**

### Example

```html
<p class="important">Important Text</p>
```

```css
.important {
  font-weight: bold;
  color: red;
}
```

---

# 🔥 Interview Questions

## ✅ Beginner

1. Difference between `<b>` and `<strong>`?
2. What is `<em>` tag?
3. How to underline text in HTML and CSS?

---

## ⚡ Intermediate

4. Difference between `text-decoration` and `<u>`?
5. What is `text-transform`?
6. What is `line-height`?

---

## 🚀 Advanced

7. Why avoid HTML styling tags?
8. How semantic HTML improves SEO?
9. Difference between `<i>` and `<em>` in accessibility?
10. How CSS inheritance works for text?

---

# 🧠 Pro Tip

> Always prefer semantic HTML + CSS styling for scalable and maintainable applications.

---

# 📌 Summary

* HTML → Structure & meaning
* CSS → Styling & layout
* Use semantic tags for accessibility
* Avoid inline styling

---

🚀 Ready for interviews + real-world projects!

