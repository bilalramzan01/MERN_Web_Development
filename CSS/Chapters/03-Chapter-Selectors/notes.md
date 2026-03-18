# 🎯 CSS Selectors (Complete Guide)

CSS selectors are used to target HTML elements and apply styles.

---

## 1. Universal Selector
Selects ALL elements.

Example:
* {
  margin: 0;
  padding: 0;
}

✔ Used for reset styles  

---

## 2. Element Selector
Selects elements by tag name.

Example:
p {
  color: blue;
}

✔ Targets all <p> tags  

---

## 3. Class Selector
Selects elements with a specific class.

Example:
.myClass {
  color: red;
}

✔ Reusable  
✔ Most commonly used  

---

## 4. ID Selector
Selects a unique element.

Example:
#myId {
  color: green;
}

✔ Used for unique elements  
❌ Avoid overusing  

---

## 5. Group Selector
Apply same style to multiple elements.

Example:
h1, p, div {
  color: black;
}

✔ Saves code  

---

## 6. Descendant Selector
Selects elements inside another element.

Example:
div p {
  color: purple;
}

✔ Targets all <p> inside <div>  

---

## 7. Child Selector (>)
Selects direct children only.

Example:
div > p {
  color: orange;
}

✔ Only direct child, not nested  

---

## 8. Adjacent Sibling Selector (+)
Selects next immediate sibling.

Example:
h1 + p {
  color: brown;
}

✔ First <p> after <h1>  

---

## 9. General Sibling Selector (~)
Selects all siblings after element.

Example:
h1 ~ p {
  color: pink;
}

✔ All <p> after <h1>  

---

## 10. Attribute Selector
Selects elements with attributes.

Example:
input[type="text"] {
  border: 1px solid black;
}

✔ Useful for forms  

---

## 11. Pseudo-class Selector
Defines special state of element.

Example:
a:hover {
  color: red;
}

button:active {
  background: blue;
}

✔ Used for interaction  

---

## 12. Pseudo-element Selector
Styles specific part of element.

Example:
p::first-letter {
  font-size: 30px;
}

p::before {
  content: "👉 ";
}

✔ Advanced styling  

---

## 🔥 Quick Summary

| Selector | Symbol | Use |
|----------|--------|-----|
| Universal | * | All elements |
| Element | p, div | By tag |
| Class | .class | Reusable |
| ID | #id | Unique |
| Group | , | Multiple elements |
| Descendant | space | Inside elements |
| Child | > | Direct child |
| Adjacent | + | Next sibling |
| General | ~ | All siblings |
| Attribute | [] | By attribute |
| Pseudo-class | : | State |
| Pseudo-element | :: | Part of element |

---

## ✅ Best Practice
- Use **class selectors** mostly  
- Avoid too many **ID selectors**  
- Keep selectors **simple & readable**  
- Use **pseudo-classes** for interactivity  