# 📘 CSS Rules & Selectors (Complete Guide)

---

# 🧾 1. What is a CSS Rule?

👉 A CSS rule defines **how HTML elements should be styled**.

### 🔹 Syntax

```css
selector {
  property: value;
}
```

### 🔹 Example

```css
p {
  color: blue;
  font-size: 16px;
}
```

👉 Here:

* `p` → Selector
* `color`, `font-size` → Properties
* `blue`, `16px` → Values

---

# 🎯 2. Types of CSS Selectors

---

# 🔹 1. Universal Selector

```css
* {
  margin: 0;
  padding: 0;
}
```

👉 Selects **all elements**

---

# 🔹 2. Element Selector

```css
p {
  color: red;
}
```

👉 Selects all `<p>` elements

---

# 🔹 3. Class Selector

```css
.box {
  background: yellow;
}
```

👉 Selects elements with `class="box"`

---

# 🔹 4. ID Selector

```css
#header {
  background: black;
}
```

👉 Selects element with `id="header"`

---

# 🔹 5. Group Selector

```css
h1, h2, p {
  color: blue;
}
```

👉 Apply same style to multiple elements

---

# 🔹 6. Descendant Selector

```css
div p {
  color: green;
}
```

👉 Selects `<p>` inside `<div>`

---

# 🔹 7. Child Selector

```css
div > p {
  color: orange;
}
```

👉 Selects **direct child** only

---

# 🔹 8. Adjacent Sibling Selector

```css
h1 + p {
  color: purple;
}
```

👉 Selects next `<p>` after `<h1>`

---

# 🔹 9. General Sibling Selector

```css
h1 ~ p {
  color: pink;
}
```

👉 Selects all `<p>` siblings after `<h1>`

---

# 🔹 10. Attribute Selector

```css
input[type="text"] {
  border: 1px solid black;
}
```

👉 Select elements based on attributes

---

# 🔹 11. Pseudo-class Selector

```css
a:hover {
  color: red;
}
```

👉 Applies style on **state**

Common:

* `:hover`
* `:focus`
* `:nth-child()`

---

# 🔹 12. Pseudo-element Selector

```css
p::first-letter {
  font-size: 30px;
}
```

👉 Styles part of element

Common:

* `::before`
* `::after`
* `::first-line`

---

# ⚖️ 3. Specificity (Very Important)

👉 Priority of selectors:

```
Inline > ID > Class > Element
```

### Example

```css
#id { color: red; }      /* High priority */
.class { color: blue; }
p { color: green; }
```

---

# 🔥 4. CSS Rule Types

---

## 🔸 Inline CSS

```html
<p style="color: red;">Text</p>
```

---

## 🔸 Internal CSS

```html
<style>
  p { color: blue; }
</style>
```

---

## 🔸 External CSS

```html
<link rel="stylesheet" href="styles.css" />
```

👉 Best practice

---

# 💡 5. Best Practices

✅ Use classes instead of IDs
✅ Avoid inline styles
✅ Keep selectors simple
✅ Use meaningful class names
✅ Avoid deep nesting

---

# 🔥 Interview Questions

---

## ✅ Beginner

1. What is CSS rule?
2. What is selector?
3. Difference between class and ID?

---

## ⚡ Intermediate

4. What is specificity?
5. Difference between descendant and child selector?
6. What are pseudo-classes?

---

## 🚀 Advanced

7. How CSS specificity works with conflicts?
8. Difference between pseudo-class and pseudo-element?
9. What is attribute selector?
10. How to optimize CSS selectors?

---

# 🧠 Pro Tip

> Keep selectors simple and avoid over-specificity for scalable CSS.

---

# 📌 Summary

* Selector → Target element
* Property → Style type
* Value → Style value
* Specificity → Priority system

---

🚀 Ready for CSS interviews!
