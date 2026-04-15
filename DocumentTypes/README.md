# 🌐 HTML, DOCTYPE (Document Type Definition) & XHTML

---

# 📌 1. What is HTML?

**HTML (HyperText Markup Language)** is the standard language used to create web pages.

👉 It defines the **structure of a webpage**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Page</title>
  </head>
  <body>
    <h1>Hello World</h1>
  </body>
</html>
```

---

# 🔥 Key Features of HTML

* Uses **tags** (`<h1>`, `<p>`, `<div>`)
* Platform independent
* Works with CSS & JavaScript
* Interpreted by browsers

---

# 🧩 Basic Structure of HTML

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
  </head>
  <body>
    Content here
  </body>
</html>
```

---

# 📌 2. What is DOCTYPE?

**DOCTYPE (Document Type Definition)** tells the browser **which version of HTML** is being used.

👉 It helps browser render the page correctly (standards mode vs quirks mode)

---

## ✅ HTML5 DOCTYPE (Modern)

```html
<!DOCTYPE html>
```

✔ Simple
✔ No version needed
✔ Used in all modern apps

---

## 🔹 Older DOCTYPE (HTML 4)

```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN">
```

⚠️ Complex and outdated

---

# 🧠 Why DOCTYPE is Important?

* Ensures **consistent rendering**
* Prevents browser quirks
* Defines rules for markup

---

# ⚠️ Without DOCTYPE

Browser may enter **quirks mode** → layout issues

---

# 📌 3. What is XHTML?

**XHTML (Extensible HyperText Markup Language)** is a stricter, XML-based version of HTML.

👉 HTML + XML rules

---

## 🔥 Key Rules of XHTML

1. All tags must be **properly closed**
2. Tags must be **lowercase**
3. Attributes must be **quoted**
4. Proper nesting required

---

## ❌ Invalid HTML

```html
<BR>
<img src=image.png>
```

---

## ✅ Valid XHTML

```html
<br />
<img src="image.png" />
```

---

# 🔍 XHTML Example

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
  "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">

<html xmlns="http://www.w3.org/1999/xhtml">
  <head>
    <title>XHTML Page</title>
  </head>
  <body>
    <h1>Hello XHTML</h1>
    <br />
  </body>
</html>
```

---

# ⚔️ HTML vs XHTML

| Feature        | HTML               | XHTML                   |
| -------------- | ------------------ | ----------------------- |
| Syntax         | Flexible           | Strict                  |
| Case           | Not case-sensitive | Lowercase required      |
| Closing Tags   | Optional           | Mandatory               |
| Error Handling | Forgiving          | Strict (fails on error) |
| Based On       | SGML               | XML                     |

---

# 🧠 Interview Questions

---

## 1️⃣ What is HTML?

👉 Markup language used to structure web pages.

---

## 2️⃣ What is DOCTYPE?

👉 Declaration that tells browser which HTML version to use.

---

## 3️⃣ Why is DOCTYPE important?

👉 Prevents quirks mode and ensures proper rendering.

---

## 4️⃣ Difference between HTML and XHTML?

👉 XHTML is stricter and follows XML rules.

---

## 5️⃣ What happens if DOCTYPE is missing?

👉 Browser switches to **quirks mode**

---

## 6️⃣ Is XHTML still used?

👉 Rarely — HTML5 replaced it in most applications.

---

# 🚀 Pro Tips

* Always use `<!DOCTYPE html>` in modern apps
* Follow XHTML-like discipline (clean code)
* Proper nesting avoids bugs
* Use semantic HTML (`<header>`, `<section>`, etc.)

---

# 🎯 Summary

* HTML → structure of web page
* DOCTYPE → defines rendering mode
* XHTML → strict version of HTML

---

💡 Master these basics → strong foundation for frontend interviews 🚀
