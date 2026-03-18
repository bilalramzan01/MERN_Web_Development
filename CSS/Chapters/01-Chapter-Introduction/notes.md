# 📌 CSS Basic Syntax

CSS is written using **rules** that describe how HTML elements should be styled.

---

## 🔷 Syntax Structure

```css
selector {
  property: value;
}

## 🔷 2. Internal CSS

Internal CSS is defined inside the `<style>` tag in the `<head>` section of the HTML file.

### 💻 Example
```html
<style>
  p {
    color: blue;
  }
</style>

##3. External CSS

External CSS is written in a separate .css file and linked to the HTML file.

###💻 Example
<link rel="stylesheet" href="style.css">