# 📌 HTML Basics Assignment

This assignment covers the core basics of HTML: images, text formatting (subscripts/superscripts), linking, and multi-page navigation.

To help you get started, I've broken down the code required for each of the four tasks.

---

## 1. Images with Specific Width

To display an image and set its width, use the `<img>` tag with the width attribute.

Example Code: `<img src="image1.jpg" width="200px">`

Tip: Repeat this 10 times with different sources to fulfill the requirement.

---

## 2. Horizontal Ruler and Formulas

For the horizontal line, use `<hr>`. For the math and chemistry formulas, you will need the subscript (`<sub>`) and superscript (`<sup>`) tags.

HTML:
## 3. Wikipedia-Style Article with Links

The goal here is to use **anchor tags (`<a>`)** within a block of text.

**Structure:** Create headings (`<h1>`, `<h2>`) and paragraphs (`<p>`).

**Linking Example:** `<a href="https://google.com">Search Engine</a>`

**Variety:** Make sure to include **5 unique URLs** to different websites.

---

## 4. Multi-Page Navigation

You will need **three separate files**: `index.html`, `page2.html`, and `page3.html`.  
All files should be in the **same folder**.

**To move between files:**

In `index.html`, link to the others: `<a href="page2.html">Go to Page 2</a>`

### The "Home" Image Button

On `page2.html` and `page3.html`, use an image inside an anchor tag to return home:

```html
<a href="index.html">
  <img src="home-icon.png" alt="Home">
</a>