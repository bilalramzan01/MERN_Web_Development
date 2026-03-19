# 📦 CSS Box Model (Padding, Margin, Width & Height)

The CSS Box Model defines how elements are structured and spaced in a webpage.

Every element is a rectangular box made of:

👉 Content → Padding → Border → Margin  

---

## 🔹 1. Content
This is the actual text or image inside the element.

Example:
div {
  width: 200px;
  height: 100px;
}

✔ Defines size of content area  

---

## 🔹 2. Padding (Inner Space)
Space between content and border.

Example:
div {
  padding: 20px;
}

✔ Adds space inside the box  
✔ Increases element size  

---

## 🔹 3. Border
Wraps around padding and content.

Example:
div {
  border: 2px solid black;
}

✔ Visible boundary  

---

## 🔹 4. Margin (Outer Space)
Space outside the element.

Example:
div {
  margin: 20px;
}

✔ Creates space between elements  
✔ Does NOT increase background  

---

## 🔹 5. Width & Height
Controls size of the content area.

Example:
div {
  width: 300px;
  height: 150px;
}

✔ Does NOT include padding & margin (by default)  

---

## 🔥 Box Model Structure

| Layer   | Description |
|--------|------------|
| Content | Actual data |
| Padding | Inner space |
| Border  | Edge of box |
| Margin  | Outer space |

---

## 📐 Total Size Calculation

Actual size of element:

Total Width = width + padding + border + margin  
Total Height = height + padding + border + margin  

---

## 🔹 box-sizing Property (Important)

### 1. content-box (default)
Width/height only apply to content.

### 2. border-box
Includes padding & border in width/height.

Example:
div {
  box-sizing: border-box;
}

✔ Easier layout control  
✔ Recommended  

---

## 🔥 Quick Summary

| Property | Use |
|----------|-----|
| width/height | Size of content |
| padding | Space inside |
| border | Box edge |
| margin | Space outside |
| box-sizing | Size calculation control |

---

## ✅ Best Practice
- Use **margin** for spacing between elements  
- Use **padding** for inner spacing  
- Use **box-sizing: border-box** for easier layouts  
- Avoid unnecessary large margins/padding  