# 📘 CSS Positioning (Complete Guide + Interview Prep)

---

# 🧾 1. What is CSS Positioning?

👉 CSS positioning controls **how elements are placed on the page**.

---

# 🧩 2. Types of Positioning

```text id="c7m2x9"
static | relative | absolute | fixed | sticky
```

---

# 🔹 1. Static (Default)

```css id="v2j8xp"
.box {
  position: static;
}
```

👉 Default behavior
👉 Ignores `top`, `left`, `right`, `bottom`

---

# 🔹 2. Relative

```css id="m1k9zy"
.box {
  position: relative;
  top: 10px;
  left: 20px;
}
```

👉 Moves **relative to its original position**
👉 Space is still preserved

---

# 🔹 3. Absolute

```css id="r5d3jq"
.parent {
  position: relative;
}

.child {
  position: absolute;
  top: 0;
  right: 0;
}
```

👉 Positioned relative to **nearest positioned parent**
👉 Removed from normal flow

---

# 🔹 4. Fixed

```css id="q8x1pl"
.box {
  position: fixed;
  top: 0;
}
```

👉 Fixed to **viewport**
👉 Does not move on scroll

---

# 🔹 5. Sticky

```css id="y6t4zn"
.box {
  position: sticky;
  top: 0;
}
```

👉 Acts like relative until scroll, then becomes fixed

---

# ⚖️ 3. Position Comparison

| Type     | Relative To     | Scroll Behavior | Space |
| -------- | --------------- | --------------- | ----- |
| static   | Normal flow     | Scrolls         | Yes   |
| relative | Itself          | Scrolls         | Yes   |
| absolute | Parent          | Scrolls         | No    |
| fixed    | Viewport        | Fixed           | No    |
| sticky   | Scroll position | Hybrid          | Yes   |

---

# 📍 4. Position Properties

👉 Used with positioned elements:

```css id="p9z2mx"
top
right
bottom
left
z-index
```

---

## 🔹 z-index

```css id="c4k7bn"
.box {
  position: absolute;
  z-index: 10;
}
```

👉 Controls stacking order
👉 Higher value = on top

---

# 🧠 5. Important Concepts

---

## 🔸 Positioned Element

👉 Any element with position other than `static`

---

## 🔸 Containing Block

👉 Parent element used as reference for `absolute`

---

## 🔸 Stacking Context

👉 Controls layering using `z-index`

---

# 💡 6. Real-World Usage

👉 `relative` → small adjustments
👉 `absolute` → dropdowns, tooltips
👉 `fixed` → navbar, chat button
👉 `sticky` → headers

---

# 🔥 7. Interview Questions & Answers

---

## ✅ Beginner

### 1. What is CSS positioning?

👉 It defines how elements are placed on the page.

---

### 2. What is default position?

👉 `static`

---

### 3. What is relative positioning?

👉 Moves element relative to itself.

---

## ⚡ Intermediate

### 4. What is absolute positioning?

👉 Positioned relative to nearest positioned parent.

---

### 5. Difference between absolute and relative?

👉 relative → keeps space
👉 absolute → removes from flow

---

### 6. What is fixed positioning?

👉 Fixed to viewport.

---

### 7. What is sticky positioning?

👉 Hybrid of relative and fixed.

---

## 🚀 Advanced

### 8. What is z-index?

👉 Controls stacking order.

---

### 9. Why z-index not working?

👉 Because:

* No position set
* Parent stacking context issue

---

### 10. Difference between fixed and sticky?

👉 fixed → always fixed
👉 sticky → scroll-based

---

### 11. What is containing block?

👉 Parent element used for positioning.

---

### 12. How to center using absolute?

```css id="s8m3kp"
.child {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
```

---

# 🧠 Pro Tips

✅ Always set parent as `position: relative` for absolute child
✅ Use `z-index` carefully
✅ Avoid overuse of absolute positioning
✅ Prefer Flexbox/Grid for layout

---

# 📌 Summary

* static → default
* relative → adjust position
* absolute → parent-based
* fixed → viewport
* sticky → scroll-based

---

🚀 Ready for **CSS Positioning interviews!**
