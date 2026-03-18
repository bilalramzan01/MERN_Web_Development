# 📌 Color & Background Color in CSS

CSS provides properties to control **text color** and **background color** of elements.

---

## 🔷 Color Property

The `color` property is used to set the **text color** of an element.

### 💻 Example
```css
p {
  color: red;
}

## 🔷Background Color Property

The background-color property is used to set the background color of an element.

###💻 Example
div {
  background-color: yellow;
}

# 🎨 Types of Color Codes in CSS

CSS supports multiple ways to define colors.

---

## 1. Named Colors
Example:
color: red;
background-color: blue;

✔ Easy to use  
❌ Limited options  

---

## 2. HEX (Hexadecimal)
Format:
#RRGGBB

Example:
color: #ff0000;  /* Red */
color: #00ff00;  /* Green */
color: #0000ff;  /* Blue */

Short HEX:
color: #f00;

✔ Most common  

---

## 3. RGB (Red, Green, Blue)
Format:
rgb(red, green, blue)

Example:
color: rgb(255, 0, 0);
color: rgb(0, 255, 0);
color: rgb(0, 0, 255);

✔ Good for dynamic values  

---

## 4. RGBA (RGB + Alpha)
Format:
rgba(red, green, blue, alpha)

Example:
color: rgba(255, 0, 0, 0.5);

✔ Supports transparency  

---

## 5. HSL (Hue, Saturation, Lightness)
Format:
hsl(hue, saturation, lightness)

Example:
color: hsl(0, 100%, 50%);
color: hsl(120, 100%, 50%);
color: hsl(240, 100%, 50%);

✔ Easy for design adjustments  

---

## 6. HSLA (HSL + Alpha)
Format:
hsla(hue, saturation, lightness, alpha)

Example:
color: hsla(0, 100%, 50%, 0.5);

✔ Modern UI usage  

---

## 7. CSS Variables
Example:
:root {
  --main-color: #3498db;
}

color: var(--main-color);

✔ Reusable and clean  

---

## 🔥 Quick Comparison

| Type  | Transparency | Ease | Flexibility |
|-------|-------------|------|-------------|
| Named | ❌ | ✔ | ❌ |
| HEX   | ❌ | ✔ | ✔ |
| RGB   | ❌ | ✔ | ✔ |
| RGBA  | ✔ | ✔ | ✔✔ |
| HSL   | ❌ | ✔✔ | ✔✔ |
| HSLA  | ✔ | ✔✔ | ✔✔ |

---

## ✅ Best Practice
- Use HEX or RGB for simple designs  
- Use HSL/HSLA for advanced UI  
- Use RGBA/HSLA for transparency  
- Use CSS variables for scalable projects
