# 🔗 HTML Anchor Tag

## 📌 `<a>`: The Anchor Element

The **anchor (`<a>`) tag** is used to create hyperlinks to:
- Web pages  
- Files  
- Email addresses  
- URLs  

---

## ⚙️ How It Works

To make the anchor tag functional, you must use the **`href` attribute**  
(*Hypertext Reference*), which defines the destination.

---

## 💻 Example

```html
<a href="https://www.google.com">Click here to go to Google</a>

# 🔗 href vs src in HTML

## 📌 href (Hypertext Reference)

The `href` attribute is used to **link to another resource**.

- It does NOT display the content directly
- It is used for navigation
- Commonly used in:
  - `<a>` (anchor tag)
  - `<link>` (CSS files)

### 💻 Example

```html
<a href="https://www.google.com">Visit Google</a>
<link rel="stylesheet" href="style.css">

## 📌 src (Source)

The `src` attribute is used to **embed or load content inside the webpage**.

- It displays content directly on the page  
- Used to load external files  

---

## 🔧 Commonly Used In

- `<img>`  
- `<script>`  
- `<iframe>`  

---

## 💻 Example

```html
<img src="image.jpg" alt="Image">
<script src="script.js"></script>


# 🔗 Absolute vs Relative Links in HTML

## 📌 Absolute Links

An **absolute link** is a full URL that points to a complete web address.

- Includes protocol (`http://` or `https://`)
- Used to link external websites

### 💻 Example

```html
<a href="https://www.google.com">Visit Google</a>

# 📌 Relative Links

A **relative link** points to a file or page **within the same project or website**.

- **Does NOT include full URL**  
- **Uses file paths**  
- **Used for internal navigation**

---

## 💻 Examples

```html
<a href="about.html">About Page</a>
<a href="folder/contact.html">Contact Page</a>

# 📌 Linking Files Between Folders

You can link a file in one folder to a file in another folder using **relative paths**.  

---

## Example Folder Structure
# 📌 Linking Files Between Folders

You can link a file in one folder to a file in another folder using **relative paths**.  

---

## Example Folder Structure
