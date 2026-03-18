# 📌 List Elements in HTML

List elements are used to **display items in a structured format** on a webpage.

There are **three main types of lists** in HTML:

---

## 🔷 Unordered List (`<ul>`)

An unordered list displays items with **bullet points**.  
Used when the **order does not matter**.

### 💻 Example
```html
<ul>
  <li>Apple</li>
  <li>Banana</li>
  <li>Mango</li>
</ul>

# 📌 Ordered List (`<ol>`) & Unordered List (`<ul>`)

HTML provides two common list types to display items:  
**Ordered lists** and **Unordered lists**.

---

## 🔶 Ordered List (`<ol>`)

An ordered list displays items in a **specific order** using numbers or letters.

### ✅ Characteristics
- Items are **numbered (1, 2, 3...)**  
- Used when **order matters**  

### 💻 Example
```html
<ol>
  <li>Wake up</li>
  <li>Study</li>
  <li>Practice coding</li>
</ol>

## 🔷 Unordered List (`<ul>`)

An unordered list displays items with **bullet points**.

### ✅ Characteristics

- Items are shown as **bullets**  
- Used when **order does not matter**  

### 💻 Example

```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>

## 🔷 Unordered List (`<ul>`)

An unordered list displays items with **bullet points**.

### ✅ Characteristics

- Items are shown as **bullets**  
- Used when **order does not matter**  

### 💻 Example

```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>

# 📌 Types of `<ul>` and `<ol>`

HTML lists can be **styled differently** using attributes or CSS.  
Here are the common types:

---

## 🔷 Unordered List (`<ul>`)

By default, `<ul>` uses **solid bullets**, but you can change the style using the `type` attribute (deprecated in HTML5, better to use CSS).

### Types / Styles

| Type | Description | Example (HTML) |
|------|------------|----------------|
| `disc` | Default solid circle bullet | `<ul type="disc">` |
| `circle` | Hollow circle bullet | `<ul type="circle">` |
| `square` | Solid square bullet | `<ul type="square">` |

### Example
```html
<ul type="circle">
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>

## 🔶 Ordered List (`<ol>`)

Ordered lists can use **numbers, letters, or Roman numerals** using the `type` attribute.

---

### ✅ Types / Styles

| Type | Description            | Example (HTML)       |
|------|------------------------|--------------------|
| 1    | Numbers (default)      | `<ol type="1">`     |
| A    | Uppercase letters      | `<ol type="A">`     |
| a    | Lowercase letters      | `<ol type="a">`     |
| I    | Uppercase Roman numerals | `<ol type="I">`   |
| i    | Lowercase Roman numerals | `<ol type="i">`   |

---

### 💻 Example

```html
<ol type="A">
  <li>Wake up</li>
  <li>Study</li>
  <li>Practice coding</li>
</ol>