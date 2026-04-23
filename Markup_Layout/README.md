# 📘 HTML Markup Layout (Complete Guide + Interview Prep)

---

# 🧾 1. What is Markup Layout?

👉 Markup layout refers to the **structure of a webpage using HTML**.
It defines how content is organized into sections like header, navigation, main content, sidebar, and footer.

---

# 🧱 2. Basic HTML Layout Structure

```html id="wq3n7k"
<!DOCTYPE html>
<html>
<head>
  <title>My Page</title>
</head>
<body>

  <header>
    <h1>Website Logo</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
  </nav>

  <main>
    <section>
      <h2>Main Content</h2>
    </section>

    <aside>
      Sidebar
    </aside>
  </main>

  <footer>
    Footer Content
  </footer>

</body>
</html>
```

---

# 🧩 3. Semantic Layout Tags

👉 HTML5 introduced semantic tags for better structure.

| Tag         | Purpose                  |
| ----------- | ------------------------ |
| `<header>`  | Top section (logo/title) |
| `<nav>`     | Navigation links         |
| `<main>`    | Main content             |
| `<section>` | Group of related content |
| `<article>` | Independent content      |
| `<aside>`   | Sidebar                  |
| `<footer>`  | Bottom section           |

---

# 🎯 4. Layout Types

---

## 🔹 1. Single Column

👉 Used in mobile UI

---

## 🔹 2. Two Column

👉 Content + Sidebar

---

## 🔹 3. Three Column

👉 Left + Content + Right

---

## 🔹 4. Grid Layout

👉 Used in dashboards

---

# 🎨 5. Layout with CSS (Flexbox)

```css id="u6f3kz"
.container {
  display: flex;
}

.main {
  flex: 3;
}

.sidebar {
  flex: 1;
}
```

---

# ⚖️ 6. Markup vs Layout

| Concept | Meaning                  |
| ------- | ------------------------ |
| Markup  | HTML structure           |
| Layout  | Visual arrangement (CSS) |

👉 HTML = skeleton
👉 CSS = design

---

# 💡 7. Best Practices

✅ Use semantic tags
✅ Avoid unnecessary `<div>`
✅ Keep structure clean
✅ Use Flexbox/Grid for layout
✅ Make responsive

---

# 🔥 8. Interview Questions & Answers

---

## ✅ Beginner

### 1. What is markup layout?

👉 Structure of webpage using HTML.

---

### 2. What are semantic tags?

👉 Tags that describe meaning of content.

---

### 3. What is `<main>` tag?

👉 Represents main content of the page.

---

## ⚡ Intermediate

### 4. Difference between `<section>` and `<article>`?

👉 section → group of content
👉 article → independent content

---

### 5. Why semantic HTML is important?

👉 Improves SEO, accessibility, and readability.

---

### 6. Difference between markup and layout?

👉 markup → structure
👉 layout → design

---

## 🚀 Advanced

### 7. How to create responsive layout?

👉 Using:

* Flexbox
* CSS Grid
* Media queries

---

### 8. Why avoid tables for layout?

👉 Not responsive and poor practice.

---

### 9. What is mobile-first design?

👉 Design for mobile first, then scale up.

---

### 10. How does layout affect performance?

👉 Clean structure improves rendering and maintainability.

---

# 🧠 Pro Tip

> Use semantic HTML + modern CSS (Flexbox/Grid) for scalable layouts.

---

# 📌 Summary

* Markup layout = HTML structure
* Semantic tags improve SEO
* CSS handles layout
* Keep it clean and responsive

---

🚀 Ready for **HTML Layout & Structure interviews!**
