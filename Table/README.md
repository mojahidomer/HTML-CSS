# 📘 HTML Table Tags (Complete Guide)

---

# 🧾 1. What is an HTML Table?

An HTML table is used to **display data in rows and columns**.

👉 Common use cases:

* Reports
* Data grids
* Pricing tables
* Dashboard tables

---

# 🧱 2. Basic Structure of a Table

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
    <th>City</th>
  </tr>
  <tr>
    <td>John</td>
    <td>25</td>
    <td>Delhi</td>
  </tr>
</table>
```

---

# 🔹 Output Structure

| Name | Age | City  |
| ---- | --- | ----- |
| John | 25  | Delhi |

---

# 🧩 3. Important HTML Table Tags

---

## 🔸 `<table>`

* Defines the table

```html
<table></table>
```

---

## 🔸 `<tr>` (Table Row)

* Creates a row

```html
<tr></tr>
```

---

## 🔸 `<td>` (Table Data)

* Defines a normal cell

```html
<td>Data</td>
```

---

## 🔸 `<th>` (Table Header)

* Defines header cell (bold + centered by default)

```html
<th>Header</th>
```

---

# 🏗️ 4. Semantic Table Tags (Very Important)

These improve **SEO + accessibility + readability**

---

## 🔸 `<thead>`

* Groups header content

```html
<thead>
  <tr>
    <th>Name</th>
  </tr>
</thead>
```

---

## 🔸 `<tbody>`

* Groups main data

```html
<tbody>
  <tr>
    <td>John</td>
  </tr>
</tbody>
```

---

## 🔸 `<tfoot>`

* Footer section (summary, totals)

```html
<tfoot>
  <tr>
    <td>Total</td>
  </tr>
</tfoot>
```

---

## 🔥 Full Example

```html
<table border="1">
  <thead>
    <tr>
      <th>Name</th>
      <th>Age</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>John</td>
      <td>25</td>
    </tr>
  </tbody>

  <tfoot>
    <tr>
      <td colspan="2">End</td>
    </tr>
  </tfoot>
</table>
```

---

# 🔗 5. Table Attributes

---

## 🔸 `colspan`

* Merge columns

```html
<td colspan="2">Merged Column</td>
```

---

## 🔸 `rowspan`

* Merge rows

```html
<td rowspan="2">Merged Row</td>
```

---

## 🔥 Example

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th colspan="2">Details</th>
  </tr>
  <tr>
    <td rowspan="2">John</td>
    <td>25</td>
    <td>Delhi</td>
  </tr>
  <tr>
    <td>26</td>
    <td>Mumbai</td>
  </tr>
</table>
```

---

# 🎨 6. Styling Tables with CSS

```css
table {
  border-collapse: collapse;
  width: 100%;
}

th, td {
  border: 1px solid black;
  padding: 8px;
  text-align: left;
}

th {
  background-color: #f2f2f2;
}
```

---

# ⚖️ 7. Best Practices

✅ Use `<thead>`, `<tbody>`, `<tfoot>`
✅ Use `<th>` for headers
✅ Avoid using table for layout (use CSS instead)
✅ Keep table accessible

---

# 🔥 Interview Questions

---

## ✅ Beginner

1. What is `<table>` tag?
2. Difference between `<td>` and `<th>`?
3. What is `<tr>`?

---

## ⚡ Intermediate

4. What is `colspan` and `rowspan`?
5. Difference between `<thead>` and `<tbody>`?
6. Why use semantic table tags?

---

## 🚀 Advanced

7. Why should tables not be used for layout?
8. How to make tables responsive?
9. How accessibility works in tables?
10. Difference between HTML tables and CSS grid?

---

# 🧠 Pro Tip

> Use tables only for **tabular data**, not for layout.
> For layout → use Flexbox or Grid.

---

# 📌 Summary

* `<table>` → Main container
* `<tr>` → Row
* `<td>` → Data cell
* `<th>` → Header cell
* `<thead>`, `<tbody>`, `<tfoot>` → Structure
* `colspan`, `rowspan` → Merge cells

---

🚀 Perfect for interviews + real projects!

# 📘 HTML Table Tags – Interview Questions & Answers

---

# ✅ Beginner Level

### 1. What is `<table>` tag?

👉 The `<table>` tag is used to create a table in HTML. It acts as a **container** for all table elements like rows, headers, and data cells.

---

### 2. Difference between `<td>` and `<th>`?

| Feature       | `<td>`      | `<th>`                     |
| ------------- | ----------- | -------------------------- |
| Meaning       | Table Data  | Table Header               |
| Default Style | Normal text | Bold + Center              |
| Purpose       | Stores data | Defines column/row heading |

👉 `<th>` is semantic and improves accessibility.

---

### 3. What is `<tr>`?

👉 `<tr>` stands for **Table Row**.
It is used to create a row inside a table.

```html id="1rrhp0"
<tr>
  <td>Data</td>
</tr>
```

---

# ⚡ Intermediate Level

### 4. What is `colspan` and `rowspan`?

👉 These are attributes used to merge cells.

* `colspan` → Merge **columns**
* `rowspan` → Merge **rows**

```html id="gbj86u"
<td colspan="2">Merged Columns</td>
<td rowspan="2">Merged Rows</td>
```

---

### 5. Difference between `<thead>` and `<tbody>`?

| Feature    | `<thead>`          | `<tbody>`            |
| ---------- | ------------------ | -------------------- |
| Purpose    | Header section     | Main data section    |
| Content    | `<th>` usually     | `<td>`               |
| Importance | Improves structure | Improves readability |

👉 Helps browsers and screen readers understand table structure.

---

### 6. Why use semantic table tags?

👉 Semantic tags like `<thead>`, `<tbody>`, `<tfoot>`:

* Improve **SEO**
* Improve **accessibility**
* Make code **readable and maintainable**

---

# 🚀 Advanced Level

### 7. Why should tables not be used for layout?

👉 Tables were used earlier for layout, but now it's a **bad practice** because:

* Not responsive
* Hard to maintain
* Poor accessibility
* Messy structure

👉 Use **Flexbox** or **CSS Grid** instead.

---

### 8. How to make tables responsive?

👉 Common approaches:

#### ✅ Scrollable table

```css id="3sz02r"
.table-container {
  overflow-x: auto;
}
```

#### ✅ Stack layout (mobile)

* Convert rows into blocks using CSS

#### ✅ Use media queries

---

### 9. How accessibility works in tables?

👉 Accessibility improvements:

* Use `<th>` instead of `<td>` for headers
* Use `scope` attribute

```html id="c0cxvy"
<th scope="col">Name</th>
<th scope="row">John</th>
```

* Screen readers understand relationships between data and headers

---

### 10. Difference between HTML tables and CSS Grid?

| Feature        | HTML Table   | CSS Grid      |
| -------------- | ------------ | ------------- |
| Purpose        | Tabular data | Layout design |
| Flexibility    | Low          | High          |
| Responsiveness | Limited      | Excellent     |
| Usage          | Data display | UI layout     |

---

# 🧠 Bonus Questions (Very Important)

---

### 11. What is `border-collapse`?

👉 It controls how table borders are displayed.

```css id="kfsy69"
table {
  border-collapse: collapse;
}
```

* `collapse` → Merges borders
* `separate` → Default

---

### 12. What is `scope` attribute in `<th>`?

👉 Defines relationship between header and data.

* `col` → Column header
* `row` → Row header

---

### 13. Difference between inline table and block table?

👉 By default:

* `<table>` behaves like **block element**
* Can be changed using CSS:

```css id="3ho49n"
table {
  display: inline-table;
}
```

---

### 14. Can we nest tables?

👉 Yes, but not recommended unless necessary.

```html id="n7aefl"
<table>
  <tr>
    <td>
      <table>
        <tr><td>Nested</td></tr>
      </table>
    </td>
  </tr>
</table>
```

---

### 15. What is the role of `<caption>`?

👉 Provides a title for the table.

```html id="luhyi3"
<table>
  <caption>Student Data</caption>
</table>
```

* Improves accessibility
* Helps users understand table content

---

# 📌 Final Summary

* `<table>` → Container
* `<tr>` → Row
* `<td>` → Data
* `<th>` → Header
* `<thead>`, `<tbody>`, `<tfoot>` → Structure
* `colspan`, `rowspan` → Merging
* CSS → Styling

---

🚀 You’re now fully ready for **HTML Table interview questions**!

