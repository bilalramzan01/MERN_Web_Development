# 📏 CSS Units of Measurement (Absolute & Relative)

CSS units define the size of elements, text, spacing, and layouts.

---

## 🔹 1. Absolute Units

Fixed size units — they do NOT change based on screen or parent.

### Types:
- px (pixels)
- pt (points)
- cm (centimeters)
- mm (millimeters)
- in (inches)

---

### 1. px (Pixels)
Most commonly used unit.

Example:
p {
  font-size: 16px;
}

✔ Precise control  
❌ Not responsive  

---

### 2. pt (Points)
Used mainly for print.

Example:
p {
  font-size: 12pt;
}

✔ Good for printing  

---

### 3. cm, mm, in
Physical measurement units.

Example:
div {
  width: 5cm;
}

❌ Rarely used in web design  

---

## 🔹 2. Relative Units

Flexible units — depend on parent, root, or screen size.

---

### 1. % (Percentage)
Relative to parent element.

Example:
div {
  width: 50%;
}

✔ Responsive  

---

### 2. em
Relative to parent font-size.

Example:
div {
  font-size: 20px;
}
p {
  font-size: 2em; /* 40px */
}

✔ Flexible  
❌ Can compound (multiply)  

---

### 3. rem (Root em)
Relative to root (html) font-size.

Example:
html {
  font-size: 16px;
}
p {
  font-size: 2rem; /* 32px */
}

✔ Consistent scaling  
✔ Preferred over em  

---

### 4. vw (Viewport Width)
Relative to screen width.

Example:
h1 {
  font-size: 5vw;
}

✔ Responsive text  

---

### 5. vh (Viewport Height)
Relative to screen height.

Example:
div {
  height: 100vh;
}

✔ Full screen layouts  

---

### 6. vmin / vmax
- vmin = smaller of vw or vh  
- vmax = larger of vw or vh  

Example:
div {
  width: 50vmin;
}

✔ Advanced responsive design  

---

## 🔥 Quick Comparison

| Unit | Type | Based On | Use |
|------|------|----------|-----|
| px | Absolute | Fixed | General use |
| pt | Absolute | Print | Printing |
| % | Relative | Parent | Layout |
| em | Relative | Parent font | Text scaling |
| rem | Relative | Root font | Best practice |
| vw | Relative | Screen width | Responsive |
| vh | Relative | Screen height | Full height |

---

## ✅ Best Practice
- Use **px** for borders & small elements  
- Use **rem** for fonts (recommended)  
- Use **%** for layouts  
- Use **vw/vh** for responsive design  
- Avoid overusing **em** (can get confusing)      