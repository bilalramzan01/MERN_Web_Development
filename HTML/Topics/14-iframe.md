# 📌 HTML `<iframe>` Element

The `<iframe>` element is used to **embed another HTML page inside the current page**.  
Think of it as a **window to another webpage** within your own page.

---

## 🔑 Key Characteristics

- **Inline frame**: Shows another webpage inside a box  
- Can load any valid URL or HTML file  
- Often used for embedding **videos, maps, or external content**  

---

## 🔷 Common Attributes

| Attribute       | Description |
|----------------|------------|
| `src`           | URL of the page to embed |
| `width`         | Width of the iframe (px or %) |
| `height`        | Height of the iframe (px or %) |
| `title`         | Accessibility title for screen readers |
| `frameborder`   | Whether to show border (`0` = no border, `1` = border) |
| `allowfullscreen` | Allows embedded content to go full screen |
| `loading`       | `lazy` or `eager` loading of iframe content |

---

##   Example

```html
<iframe 
  src="https://www.example.com" 
  width="600" 
  height="400" 
  title="Example Website" 
  frameborder="0" 
  allowfullscreen>
</iframe>