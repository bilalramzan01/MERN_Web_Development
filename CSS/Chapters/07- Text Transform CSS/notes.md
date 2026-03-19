# 🔤 CSS Text Transform (Complete Guide)

The `text-transform` property is used to control the capitalization of text.

---

## 🔹 1. text-transform: none
Default value — text appears as written.

Example:
p {
  text-transform: none;
}

✔ No changes applied  

---

## 🔹 2. text-transform: uppercase
Converts all text to CAPITAL letters.

Example:
p {
  text-transform: uppercase;
}

Output: HELLO WORLD  

✔ Common for headings  

---

## 🔹 3. text-transform: lowercase
Converts all text to small letters.

Example:
p {
  text-transform: lowercase;
}

Output: hello world  

✔ Useful for normalization  

---

## 🔹 4. text-transform: capitalize
Capitalizes the first letter of each word.

Example:
p {
  text-transform: capitalize;
}

Output: Hello World  

✔ Good for titles  

---

## 🔹 5. Global Values
Used for inheritance and reset behavior.

### Values:
- inherit → takes value from parent  
- initial → default value  
- unset → resets based on inheritance  

Example:
p {
  text-transform: inherit;
}

✔ Used in advanced styling  

---

## 🔥 Quick Summary

| Value | Effect |
|-------|--------|
| none | No change |
| uppercase | ALL CAPS |
| lowercase | all small |
| capitalize | First Letter Capital |

---

## ✅ Best Practice
- Use **uppercase** for headings  
- Use **capitalize** for titles  
- Avoid overusing ALL CAPS (bad UX)  
- Keep readability in mind  