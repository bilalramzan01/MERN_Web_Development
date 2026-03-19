# 📏 CSS Margins (Complete Guide)

Margins are used to create space **outside** an element, separating it from other elements.

---

## 🔹 1. margin Property (Shorthand)

Used to set margin on all sides.

### Example:
div {
  margin: 20px;
}

✔ Applies to all sides (top, right, bottom, left)

---

## 🔹 2. Individual Margins

Set margin for specific sides.

### Example:
div {
  margin-top: 10px;
  margin-right: 20px;
  margin-bottom: 30px;
  margin-left: 40px;
}

✔ Full control over spacing  

---

## 🔹 3. Shorthand Values (TRBL Rule)

Order: Top → Right → Bottom → Left

### Example:
div {
  margin: 10px 20px 30px 40px;
}

---

### 2 Values:
Top-Bottom | Left-Right

div {
  margin: 10px 20px;
}

---

### 3 Values:
Top | Left-Right | Bottom

div {
  margin: 10px 20px 30px;
}

---

## 🔹 4. Auto Margin (Centering)

Used to center block elements horizontally.

### Example:
div {
  width: 200px;
  margin: auto;
}

✔ Centers element  

---

## 🔹 5. Negative Margins

Allows elements to overlap.

### Example:
div {
  margin-top: -10px;
}

✔ Advanced layouts  
❌ Use carefully  

---

## 🔹 6. Margin Collapse

Vertical margins of elements can merge.

### Example:
Two divs with margin-top and margin-bottom → margins combine

✔ Saves space automatically  

---

## 🔥 Quick Summary

| Property | Use |
|----------|-----|
| margin | All sides |
| margin-top | Top space |
| margin-right | Right space |
| margin-bottom | Bottom space |
| margin-left | Left space |
| margin: auto | Centering |

---

## ✅ Best Practice
- Use **margin** for outer spacing  
- Use **auto** for centering  
- Avoid too many large margins  
- Be careful with **negative margins**  