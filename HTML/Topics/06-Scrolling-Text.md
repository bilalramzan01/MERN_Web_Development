# 📌 HTML `<marquee>` Element

The `<marquee>` tag in HTML is used to **create scrolling text or images** on a webpage.  

> ⚠️ Note: The `<marquee>` tag is **obsolete** and not recommended in modern HTML. It's better to use CSS animations for scrolling effects.  

---

## 🔹 Syntax

```html
<marquee>Scrolling Text Here</marquee>

## 🔹 Attributes of `<marquee>`

| Attribute      | Description                                           | Example                                      |
|----------------|-------------------------------------------------------|----------------------------------------------|
| `direction`    | Sets the scroll direction (`left`, `right`, `up`, `down`) | `<marquee direction="up">Text</marquee>`   |
| `behavior`     | Sets the scroll behavior (`scroll`, `slide`, `alternate`) | `<marquee behavior="alternate">Text</marquee>` |
| `scrollamount` | Sets the speed of scrolling (number of pixels)       | `<marquee scrollamount="10">Text</marquee>` |
| `loop`         | Number of times the marquee should scroll            | `<marquee loop="5">Text</marquee>`          |
| `bgcolor`      | Background color of the marquee                      | `<marquee bgcolor="yellow">Text</marquee>`  |
| `width / height` | Size of the marquee                                | `<marquee width="300" height="50">Text</marquee>` |