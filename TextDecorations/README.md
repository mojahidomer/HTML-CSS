# 📘 CSS Decoration Properties (Border, Background, Text)

---

# 🎨 1. Border (Box Styling)

👉 The `border` property is used to define **the outline around an element**.

---

## 🔹 Syntax

```css
border: width style color;
```

---

## 🔹 Example

```css
.box {
  border: 2px solid red;
}
```

---

## 🔹 Individual Properties

```css
.box {
  border-width: 2px;
  border-style: solid;
  border-color: black;
}
```

---

## 🔹 Border Variants

```css
border-top: 2px solid blue;
border-radius: 10px;
```

---

## 🔥 Common Styles

* solid
* dashed
* dotted
* double

---

# 🎯 2. Background

👉 Used to style the **background of an element**.

---

## 🔹 Basic Properties

```css
.container {
  background-color: lightblue;
  background-image: url("image.jpg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}
```

---

## 🔹 Shorthand

```css
background: lightblue url("img.jpg") no-repeat center/cover;
```

---

## 🔹 Important Values

* `cover` → fills entire container
* `contain` → fits inside container
* `no-repeat` → no repetition

---

# ✏️ 3. Text Decoration

👉 Used to decorate text like underline, strike, etc.

---

## 🔹 Example

```css
p {
  text-decoration: underline;
}
```

---

## 🔹 Types

```css
text-decoration: none;
text-decoration: underline;
text-decoration: line-through;
text-decoration: overline;
```

---

## 🔹 Advanced

```css
text-decoration: underline red wavy;
```

---

# 🔤 4. Text Transform

👉 Controls **text casing (uppercase/lowercase)**

---

## 🔹 Example

```css
p {
  text-transform: uppercase;
}
```

---

## 🔹 Values

```css
text-transform: uppercase;
text-transform: lowercase;
text-transform: capitalize;
```

---

# ⚖️ Quick Comparison

| Property        | Purpose                       |
| --------------- | ----------------------------- |
| border          | Outline of element            |
| background      | Element background            |
| text-decoration | Text styling (underline etc.) |
| text-transform  | Text case                     |

---

# 💡 Best Practices

✅ Use shorthand properties
✅ Avoid heavy background images
✅ Use `border-radius` for modern UI
✅ Use `text-decoration: none` for links when needed

---

# 🔥 Interview Questions & Answers

---

## ✅ Beginner

### 1. What is border property?

👉 Defines the outline around an element.

---

### 2. What are border styles?

👉 solid, dashed, dotted, double.

---

### 3. What is background-color?

👉 Sets background color of an element.

---

### 4. What is text-decoration?

👉 Used to style text like underline or strike.

---

### 5. What is text-transform?

👉 Controls text case (uppercase, lowercase, capitalize).

---

## ⚡ Intermediate

### 6. Difference between border and outline?

👉

* Border → takes space
* Outline → does not take space

---

### 7. What is background shorthand?

👉 Combines multiple background properties into one.

---

### 8. Difference between `cover` and `contain`?

👉

* cover → fills container
* contain → fits inside

---

### 9. How to remove underline from links?

```css
a {
  text-decoration: none;
}
```

---

## 🚀 Advanced

### 10. How to create rounded borders?

```css
border-radius: 10px;
```

---

### 11. Can we apply multiple backgrounds?

👉 Yes:

```css
background: url(img1), url(img2);
```

---

### 12. How to style text decoration color?

```css
text-decoration: underline red;
```

---

### 13. How to control background image size?

```css
background-size: cover;
```

---

# 🧠 Pro Tip

> Combine border + background + text styling for modern UI design.

---

# 📌 Summary

* Border → outline
* Background → visual container
* Text-decoration → underline/strike
* Text-transform → case control

---

🚀 Ready for CSS styling interviews!

# 📘 CSS Decoration Properties (Border, Background, Text)

---

# 🎨 1. Border (Box Styling)

👉 The `border` property is used to define **the outline around an element**.

---

## 🔹 Syntax

```css
border: width style color;
```

---

## 🔹 Example

```css
.box {
  border: 2px solid red;
}
```

---

## 🔹 Individual Properties

```css
.box {
  border-width: 2px;
  border-style: solid;
  border-color: black;
}
```

---

## 🔹 Border Variants

```css
border-top: 2px solid blue;
border-radius: 10px;
```

---

## 🔥 Common Styles

* solid
* dashed
* dotted
* double

---

# 🎯 2. Background

👉 Used to style the **background of an element**.

---

## 🔹 Basic Properties

```css
.container {
  background-color: lightblue;
  background-image: url("image.jpg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}
```

---

## 🔹 Shorthand

```css
background: lightblue url("img.jpg") no-repeat center/cover;
```

---

## 🔹 Important Values

* `cover` → fills entire container
* `contain` → fits inside container
* `no-repeat` → no repetition

---

# ✏️ 3. Text Decoration

👉 Used to decorate text like underline, strike, etc.

---

## 🔹 Example

```css
p {
  text-decoration: underline;
}
```

---

## 🔹 Types

```css
text-decoration: none;
text-decoration: underline;
text-decoration: line-through;
text-decoration: overline;
```

---

## 🔹 Advanced

```css
text-decoration: underline red wavy;
```

---

# 🔤 4. Text Transform

👉 Controls **text casing (uppercase/lowercase)**

---

## 🔹 Example

```css
p {
  text-transform: uppercase;
}
```

---

## 🔹 Values

```css
text-transform: uppercase;
text-transform: lowercase;
text-transform: capitalize;
```

---

# ⚖️ Quick Comparison

| Property        | Purpose                       |
| --------------- | ----------------------------- |
| border          | Outline of element            |
| background      | Element background            |
| text-decoration | Text styling (underline etc.) |
| text-transform  | Text case                     |

---

# 💡 Best Practices

✅ Use shorthand properties
✅ Avoid heavy background images
✅ Use `border-radius` for modern UI
✅ Use `text-decoration: none` for links when needed

---

# 🔥 Interview Questions & Answers

---

## ✅ Beginner

### 1. What is border property?

👉 Defines the outline around an element.

---

### 2. What are border styles?

👉 solid, dashed, dotted, double.

---

### 3. What is background-color?

👉 Sets background color of an element.

---

### 4. What is text-decoration?

👉 Used to style text like underline or strike.

---

### 5. What is text-transform?

👉 Controls text case (uppercase, lowercase, capitalize).

---

## ⚡ Intermediate

### 6. Difference between border and outline?

👉

* Border → takes space
* Outline → does not take space

---

### 7. What is background shorthand?

👉 Combines multiple background properties into one.

---

### 8. Difference between `cover` and `contain`?

👉

* cover → fills container
* contain → fits inside

---

### 9. How to remove underline from links?

```css
a {
  text-decoration: none;
}
```

---

## 🚀 Advanced

### 10. How to create rounded borders?

```css
border-radius: 10px;
```

---

### 11. Can we apply multiple backgrounds?

👉 Yes:

```css
background: url(img1), url(img2);
```

---

### 12. How to style text decoration color?

```css
text-decoration: underline red;
```

---

### 13. How to control background image size?

```css
background-size: cover;
```

---

# 🧠 Pro Tip

> Combine border + background + text styling for modern UI design.

---

# 📌 Summary

* Border → outline
* Background → visual container
* Text-decoration → underline/strike
* Text-transform → case control

---

🚀 Ready for CSS styling interviews!
