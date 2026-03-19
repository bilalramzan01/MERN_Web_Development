# 🖥️ CSS Display Property (Complete Guide)

The `display` property defines how an element is displayed on the page.

---

## 🔹 1. display: block

Element takes full width and starts on a new line.

### Example:
div {
  display: block;
}

✔ Takes full width  
✔ Starts on new line  

---

## 🔹 2. display: inline

Element takes only required width and stays in same line.

### Example:
span {
  display: inline;
}

✔ No line break  
❌ Cannot set width/height  

---

## 🔹 3. display: inline-block

Combination of inline + block.

### Example:
div {
  display: inline-block;
  width: 100px;
  height: 100px;
}

✔ Stays inline  
✔ Can set width/height  

---

## 🔹 4. display: none

Element is completely removed from layout.

### Example:
div {
  display: none;
}

✔ Hidden completely  
❌ No space reserved  

---

## 🔹 5. display: flex

Used for flexible layouts (1D layout system).

### Example:
div {
  display: flex;
}

✔ Easy alignment  
✔ Responsive layouts  

---

## 🔹 6. display: grid

Used for grid layouts (2D layout system).

### Example:
div {
  display: grid;
}

✔ Rows + columns layout  

---

## 🔹 7. display: inline-flex / inline-grid

Works like flex/grid but stays inline.

### Example:
div {
  display: inline-flex;
}

✔ Inline + layout power  

---

## 🔥 Quick Summary

| Value | Behavior |
|------|----------|
| block | Full width, new line |
| inline | Same line, no size control |
| inline-block | Inline + size control |
| none | Hidden |
| flex | Flexible layout |
| grid | 2D layout |

---

## ✅ Best Practice
- Use **block** for structure  
- Use **inline** for text elements  
- Use **inline-block** for small layouts  
- Use **flex** for alignment  
- Use **grid** for complex layouts  