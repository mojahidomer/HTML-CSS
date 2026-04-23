# 📘 CSS Display Property (Complete Guide + Interview Prep)

---

# 🧾 1. What is `display` in CSS?

👉 The `display` property defines **how an element is rendered on the page**.

---

# 🧩 2. Common Display Values

```text id="p8d2vx"
block | inline | inline-block | none | flex | grid
```

---

# 🔹 1. Block

```css id="k3x7md"
div {
  display: block;
}
```

👉 Takes full width
👉 Starts on new line

### Examples:

* `<div>`
* `<p>`
* `<h1>`

---

# 🔹 2. Inline

```css id="z1m9qf"
span {
  display: inline;
}
```

👉 Takes only required width
👉 Does NOT start on new line
👉 Cannot set width/height

### Examples:

* `<span>`
* `<a>`

---

# 🔹 3. Inline-Block

```css id="y5t8lp"
.box {
  display: inline-block;
}
```

👉 Combines inline + block
👉 Can set width/height
👉 Stays in same line

---

# 🔹 4. None

```css id="w2q4zx"
.hidden {
  display: none;
}
```

👉 Removes element from layout completely

---

# 🔹 5. Flex

```css id="j7n3ke"
.container {
  display: flex;
}
```

👉 Used for flexible layouts
👉 Align items easily

---

# 🔹 6. Grid

```css id="m4p9vn"
.container {
  display: grid;
}
```

👉 2D layout system
👉 Rows + columns

---

# ⚖️ 3. Block vs Inline vs Inline-Block

| Feature        | Block | Inline  | Inline-block |
| -------------- | ----- | ------- | ------------ |
| New Line       | ✅     | ❌       | ❌            |
| Width/Height   | ✅     | ❌       | ✅            |
| Margin/Padding | ✅     | Limited | ✅            |

---

# 🎯 4. Visibility vs Display

```css id="z8k1wr"
display: none;
visibility: hidden;
```

| Feature | display:none | visibility:hidden |
| ------- | ------------ | ----------------- |
| Visible | ❌            | ❌                 |
| Space   | ❌            | ✅                 |

---

# 🧠 5. Important Concepts

---

## 🔸 Inline Elements Ignore

👉 width, height (mostly)

---

## 🔸 Block Elements

👉 Take full width by default

---

## 🔸 Flex/Grid

👉 Modern layout systems

---

# 💡 6. Real-World Usage

👉 `block` → layout sections
👉 `inline` → text elements
👉 `inline-block` → buttons
👉 `flex` → navbar, cards
👉 `grid` → dashboard

---

# 🔥 7. Interview Questions & Answers

---

## ✅ Beginner

### 1. What is display property?

👉 Defines how element is rendered.

---

### 2. What is block element?

👉 Takes full width and new line.

---

### 3. What is inline element?

👉 Takes only required width.

---

## ⚡ Intermediate

### 4. Difference between inline and inline-block?

👉 inline → no width/height
👉 inline-block → supports width/height

---

### 5. What is display none?

👉 Removes element from layout.

---

### 6. Difference between display none and visibility hidden?

👉 display:none → removes space
👉 visibility:hidden → keeps space

---

## 🚀 Advanced

### 7. What is flex display?

👉 Used for 1D layout alignment.

---

### 8. What is grid display?

👉 Used for 2D layout (rows + columns).

---

### 9. Can we change display of any element?

👉 Yes, using CSS.

---

### 10. Why inline elements ignore width?

👉 Because they flow with text content.

---

# 🧠 Pro Tips

✅ Use flex/grid for layout
✅ Avoid using inline for layout
✅ Use display:none carefully
✅ Use inline-block for buttons

---

# 📌 Summary

* block → full width
* inline → content width
* inline-block → mixed
* flex → 1D layout
* grid → 2D layout

---

🚀 Ready for **CSS Display interview questions!**
