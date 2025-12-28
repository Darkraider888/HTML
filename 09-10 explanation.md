
---

## 📘 Lesson 09: Forms (Basics)

**File:** `09-forms-basics.html`

### What you will learn in Lesson 09:

* What an HTML form is
* How to collect user input
* Basic form elements

---

### 🔹 What is a Form?

A **form** is used to **collect information from users**, such as:

* Name
* Email
* Password

Forms are commonly used for **login pages, sign-up pages, and contact pages**.

---

### 🔹 Important Form Tags

* `<form>` → holds all form elements
* `<label>` → describes what the input is for
* `<input>` → where the user types

---

### Example:

```html
<form>
    <label>Name:</label><br>
    <input type="text"><br><br>

    <label>Email:</label><br>
    <input type="email"><br><br>

    <input type="submit" value="Submit">
</form>
```

---

### 💡 Beginner Tips:

* Always place inputs **inside** a `<form>`
* Use `<label>` to explain inputs
* `<br>` is used here only to keep things simple

---

## 📘 Lesson 10: Input Types

**File:** `10-input-types.html`

### What you will learn in Lesson 10:

* Different types of input fields
* When to use each input type
* How input types help users

---

### 🔹 What is an Input Type?

The `type` attribute tells the browser **what kind of data** the input should accept.

---

### 🔹 Common Input Types

| Input Type | Use           |
| ---------- | ------------- |
| `text`     | Normal text   |
| `password` | Hidden text   |
| `email`    | Email address |
| `submit`   | Submit button |

---

### Example:

```html
<input type="text">
<input type="password">
<input type="email">
<input type="submit" value="Register">
```

---

### 💡 Beginner Tips:

* `password` hides the typed text
* `email` helps validate email format
* `submit` sends the form data
* Always test forms in the browser

---

## ✅ Summary

* Lesson 09 teaches **what forms are**
* Lesson 10 teaches **how different input types work**
* Forms are essential for real websites
* Practice by adding more inputs yourself

---

