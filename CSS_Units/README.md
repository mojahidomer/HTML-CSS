# 📘 CSS Units (Complete Guide + Interview Prep)

---

# 🧾 1. What are CSS Units?

👉 CSS units define the **size of elements, spacing, fonts, and layout**.

Example:

```css
p {
  font-size: 16px;
}
```

---

# 📏 2. Types of CSS Units

👉 There are **two main types**:

```text
1. Absolute Units (fixed)
2. Relative Units (flexible)
```

---

# 🔹 3. Absolute Units (Fixed Size)

👉 These units **do NOT change** based on screen size.

| Unit | Meaning    | Example            |
| ---- | ---------- | ------------------ |
| px   | Pixels     | `width: 100px;`    |
| cm   | Centimeter | `width: 2cm;`      |
| mm   | Millimeter | `width: 10mm;`     |
| in   | Inch       | `width: 1in;`      |
| pt   | Points     | `font-size: 12pt;` |
| pc   | Picas      | `1pc = 12pt`       |

---

## 🔥 Most Used

👉 `px` (pixel) is the most common.

---

# 🔹 4. Relative Units (Responsive)

👉 These units depend on **parent or screen size**

---

## 🔸 1. Percentage (%)

```css
width: 50%;
```

👉 Relative to **parent element**

---

## 🔸 2. em

```css
font-size: 2em;
```

👉 Relative to **parent font-size**

⚠️ Can cause compounding issues

---

## 🔸 3. rem (Root em)

```css
font-size: 2rem;
```

👉 Relative to **root (`html`) font-size**

✅ Preferred over `em`

---

## 🔸 4. vw (Viewport Width)

```css
width: 50vw;
```

👉 1vw = 1% of screen width

---

## 🔸 5. vh (Viewport Height)

```css
height: 100vh;
```

👉 1vh = 1% of screen height

---

## 🔸 6. vmin / vmax

```css
width: 50vmin;
```

* `vmin` → smaller of width/height
* `vmax` → larger of width/height

---

# ⚖️ 5. px vs em vs rem

| Unit | Based On | Issue          |
| ---- | -------- | -------------- |
| px   | Fixed    | Not responsive |
| em   | Parent   | Compounding    |
| rem  | Root     | Best choice    |

---

# 💡 6. Best Practices

✅ Use `rem` for font sizes
✅ Use `%` or `vw/vh` for layout
✅ Avoid too much `px`
✅ Use responsive units for mobile

---

# 🔥 7. Interview Questions & Answers

---

## ✅ Beginner

### 1. What are CSS units?

👉 Units used to define size in CSS.

---

### 2. Difference between absolute and relative units?

👉 Absolute → fixed
👉 Relative → responsive

---

### 3. What is px?

👉 Pixel unit, fixed size.

---

### 4. What is %?

👉 Relative to parent element.

---

## ⚡ Intermediate

### 5. Difference between em and rem?

👉 em → parent-based
👉 rem → root-based

---

### 6. What is vw and vh?

👉 vw → viewport width
👉 vh → viewport height

---

### 7. Why rem is preferred over em?

👉 Avoids compounding issues.

---

### 8. What is vmin and vmax?

👉 vmin → smaller dimension
👉 vmax → larger dimension

---

## 🚀 Advanced

### 9. What is responsive design using units?

👉 Using flexible units like %, rem, vw for adaptability.

---

### 10. When to use px vs rem?

👉 px → precise control
👉 rem → scalable UI

---

### 11. What happens if font-size is set in em recursively?

👉 It multiplies (compounding issue).

---

### 12. How to create fluid typography?

```css
font-size: calc(1rem + 1vw);
```

---

### 13. What is root font-size?

```css
html {
  font-size: 16px;
}
```

---

### 14. How do units affect accessibility?

👉 Relative units improve readability and scaling.

---

### 15. Best unit for mobile UI?

👉 rem + % + vw/vh

---

# 🧠 Pro Tips

✅ Use:

```css
html {
  font-size: 16px;
}
```

✅ Prefer `rem` for consistency
✅ Combine units using `calc()`
✅ Test responsiveness

---

# 📌 Summary

* Absolute units → fixed
* Relative units → flexible
* rem > em (preferred)
* vw/vh for responsive layout

---

🚀 Ready for **CSS Units interview questions**!
