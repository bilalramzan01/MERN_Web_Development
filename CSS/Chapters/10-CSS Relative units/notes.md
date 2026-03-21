# Layouts with CSS Units: `rem` vs `em`

## 🔹 Overview

Both `rem` and `em` are **relative CSS units** used for responsive and scalable layouts.

* `rem` = relative to **root (`html`) font-size**
* `em` = relative to **parent element font-size**

---

## 🔸 `rem` (Root EM)

### ✅ Definition

`1rem` = font-size of the `<html>` element

### 📌 Example

```css
html {
  font-size: 16px;
}

h1 {
  font-size: 2rem; /* 32px */
}
```

### 👍 Advantages

* Consistent across the whole page
* Easy to control global scaling
* Predictable behavior

### 👎 Disadvantages

* Less flexible for nested elements

---

## 🔸 `em` (Element EM)

### ✅ Definition

`1em` = font-size of the **parent element**

### 📌 Example

```css
.parent {
  font-size: 20px;
}

.child {
  font-size: 2em; /* 40px */
}
```

### ⚠️ Nested Example (Important)

```css
.parent {
  font-size: 20px;
}

.child {
  font-size: 2em; /* 40px */
}

.grandchild {
  font-size: 2em; /* 80px (2 × 40px) */
}
```

### 👍 Advantages

* Great for component-based scaling
* Flexible inside containers

### 👎 Disadvantages

* Can become complex due to compounding effect

---

## 🔄 Key Differences

| Feature        | `rem`                     | `em`                    |
| -------------- | ------------------------- | ----------------------- |
| Reference      | Root (`html`)             | Parent element          |
| Consistency    | High                      | Can vary                |
| Nesting effect | No                        | Yes (compounds)         |
| Use case       | Global layout, typography | Component-level scaling |

---

## 🧠 Best Practices

### ✅ Use `rem` for:

* Global font sizes
* Spacing (margin, padding)
* Layout consistency

### ✅ Use `em` for:

* Buttons, cards, components
* When scaling relative to parent is needed

---

## 🚀 Pro Tip

Set base font size for easy calculation:

```css
html {
  font-size: 62.5%; /* 1rem = 10px */
}
```

---

## 📌 Summary

* Use **`rem` → for consistency and control**
* Use **`em` → for flexible, component-based design**
