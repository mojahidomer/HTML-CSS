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

# 📘 CSS Rules & Selectors – Interview Questions & Answers

---

# ✅ Beginner Level

### 1. What is a CSS rule?

👉 A CSS rule defines how an HTML element should be styled.
It consists of a **selector** and a **declaration block (property + value)**.

---

### 2. What is a selector?

👉 A selector is used to **target HTML elements** that you want to style.

Example:

```css
p {
  color: red;
}
```

Here, `p` is the selector.

---

### 3. Difference between class and ID?

| Feature     | Class (`.`)       | ID (`#`)       |
| ----------- | ----------------- | -------------- |
| Usage       | Multiple elements | Single element |
| Reusability | Reusable          | Unique         |
| Specificity | Lower             | Higher         |

👉 Best practice: Prefer **class over ID**

---

# ⚡ Intermediate Level

### 4. What is specificity?

👉 Specificity determines **which CSS rule is applied** when multiple rules target the same element.

Priority order:

```
Inline > ID > Class > Element
```

---

### 5. Difference between descendant and child selector?

| Selector  | Meaning                                      |
| --------- | -------------------------------------------- |
| `div p`   | Selects all `<p>` inside `<div>` (any level) |
| `div > p` | Selects only direct child `<p>`              |

---

### 6. What are pseudo-classes?

👉 Pseudo-classes define **special states of elements**.

Examples:

```css
a:hover { color: red; }
input:focus { border: blue; }
li:nth-child(2) { color: green; }
```

---

# 🚀 Advanced Level

### 7. How CSS specificity works with conflicts?

👉 When multiple rules apply:

1. Highest specificity wins
2. If same specificity → last rule wins

Example:

```css
p { color: red; }
.class { color: blue; }
#id { color: green; }
```

👉 Final color = **green** (ID has highest priority)

---

### 8. Difference between pseudo-class and pseudo-element?

| Feature | Pseudo-class | Pseudo-element  |
| ------- | ------------ | --------------- |
| Purpose | State        | Part of element |
| Syntax  | `:`          | `::`            |
| Example | `:hover`     | `::before`      |

---

### 9. What is attribute selector?

👉 Selects elements based on attributes.

Example:

```css
input[type="text"] {
  border: 1px solid black;
}
```

---

### 10. How to optimize CSS selectors?

👉 Best practices:

* Avoid deep nesting
* Use class selectors
* Avoid overuse of ID
* Keep selectors short and simple
* Reduce specificity conflicts

---

# 🔥 Bonus (Real Interview Follow-ups)

---

### 11. What happens if two selectors have same specificity?

👉 The **last declared rule** will be applied.

---

### 12. What is `!important`?

👉 Forces a rule to override all other styles.

```css
p {
  color: red !important;
}
```

⚠️ Avoid using it unless necessary.

---

### 13. What is cascading in CSS?

👉 CSS stands for **Cascading Style Sheets**
Styles are applied based on:

1. Importance
2. Specificity
3. Source order

---

### 14. What is inheritance in CSS?

👉 Some properties (like `color`, `font`) are inherited from parent to child.

---

### 15. Why avoid inline CSS?

👉

* Hard to maintain
* No reusability
* Breaks separation of concerns

---

# 🧠 Pro Tip

> Write clean, reusable CSS using classes and avoid specificity wars.

---

# 📌 Final Summary

* CSS rule = selector + property + value
* Specificity decides priority
* Classes > IDs (best practice)
* Keep selectors simple
* Avoid `!important`

---

🚀 You’re now fully prepared for **CSS Selectors Interview Questions**!

