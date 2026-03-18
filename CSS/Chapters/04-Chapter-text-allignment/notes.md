# 📝 CSS Text Alignment (Complete Guide)

Text alignment in CSS controls how text is positioned horizontally and vertically inside elements.

---

## 1. text-align (Horizontal Alignment)

Used to align text inside a container.

### Values:
- left (default)
- right
- center
- justify

### Example:
p {
  text-align: center;
}

✔ Most commonly used property  

---

## 2. text-align: left
Aligns text to the left.

Example:
p {
  text-align: left;
}

✔ Default alignment  

---

## 3. text-align: right
Aligns text to the right.

Example:
p {
  text-align: right;
}

✔ Used in RTL designs  

---

## 4. text-align: center
Centers the text.

Example:
h1 {
  text-align: center;
}

✔ Very common for headings  

---

## 5. text-align: justify
Spreads text evenly across the line.

Example:
p {
  text-align: justify;
}

✔ Clean paragraph look  
❌ Can create uneven spacing  

---

## 6. Vertical Alignment (vertical-align)

Used for inline or table elements.

### Values:
- top
- middle
- bottom

### Example:
img {
  vertical-align: middle;
}

✔ Works with inline elements  

---

## 7. Line Height (Vertical Spacing Trick)

Used to center single-line text vertically.

Example:
div {
  height: 100px;
  line-height: 100px;
  text-align: center;
}

✔ Simple vertical centering  

---

## 8. Centering with Flexbox (Modern Method)

Best way to center content both horizontally & vertically.

Example:
div {
  display: flex;
  justify-content: center;
  align-items: center;
}

✔ Modern & powerful  

---

## 🔥 Quick Summary

| Property | Use |
|----------|-----|
| text-align | Horizontal alignment |
| vertical-align | Inline vertical alignment |
| line-height | Vertical centering trick |
| flexbox | Full centering |

---

## ✅ Best Practice
- Use **text-align** for simple alignment  
- Use **flexbox** for full centering  
- Avoid old hacks when possible  
- Use **justify** for long text blocks only  