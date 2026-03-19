# 🧱 CSS Borders (Complete Guide)

CSS borders are used to define the outline around elements.

---

## 🔹 1. border Property (Shorthand)

Used to define width, style, and color in one line.

### Format:
border: width style color;

### Example:
div {
  border: 2px solid black;
}

✔ Most commonly used  

---

## 🔹 2. Border Width

Defines thickness of the border.

### Values:
- thin
- medium
- thick
- px (e.g., 2px, 5px)

### Example:
div {
  border-width: 3px;
}

---

## 🔹 3. Border Style

Defines the appearance of the border.

### Values:
- solid
- dotted
- dashed
- double
- groove
- ridge
- inset
- outset
- none

### Example:
div {
  border-style: dashed;
}

✔ Required property (border won’t show without style)

---

## 🔹 4. Border Color

Sets the color of the border.

### Example:
div {
  border-color: red;
}

✔ Can use HEX, RGB, etc.  

---

## 🔹 5. Individual Borders

Apply border to specific sides.

### Example:
div {
  border-top: 2px solid red;
  border-right: 2px solid green;
  border-bottom: 2px solid blue;
  border-left: 2px solid black;
}

✔ Full control  

---

## 🔹 6. Border Radius

Used to make rounded corners.

### Example:
div {
  border-radius: 10px;
}

✔ Makes UI modern  

---

## 🔹 7. Border Collapse (Tables Only)

Used to merge table borders.

### Example:
table {
  border-collapse: collapse;
}

✔ Clean table design  

---

## 🔥 Quick Summary

| Property | Use |
|----------|-----|
| border | Shorthand |
| border-width | Thickness |
| border-style | Type |
| border-color | Color |
| border-radius | Rounded corners |

---

## ✅ Best Practice
- Always define **border-style**  
- Use **shorthand** for cleaner code  
- Use **border-radius** for modern UI  
- Keep border colors consistent with design  