## 📘 Lesson 11: div & span

**File:** `11-div-span.html`

### What you will learn in Lesson 11:

* What `<div>` is
* What `<span>` is
* Difference between **block** and **inline** elements

---

## 🔹 What is `<div>`?

* `<div>` means **division**
* It is a **block-level element**
* It starts on a **new line**
* Used to group content

### Example:

```html
<div>
    <p>This is inside a div.</p>
</div>
```

---

## 🔹 What is `<span>`?

* `<span>` is an **inline element**
* It does **not** start a new line
* Used inside text

### Example:

```html
<p>This is <span>important</span> text.</p>
```

---

## 🔹 Block vs Inline (Simple)

| Element  | Type   | New Line? |
| -------- | ------ | --------- |
| `<div>`  | Block  | Yes       |
| `<span>` | Inline | No        |

---

## 📄 Lesson 11 HTML File

```html
<!DOCTYPE html>
<html>
<head>
    <title>Lesson 11 - div and span</title>
</head>
<body>

    <!-- div example -->
    <div>
        <h2>This is a div</h2>
        <p>Div is a block element.</p>
    </div>

    <!-- another div -->
    <div>
        <p>This is another div. It starts on a new line.</p>
    </div>

    <!-- span example -->
    <p>
        This is a <span>span</span> inside a paragraph.
    </p>

    <p>
        Span does not break the line.
    </p>

    <!-- div = block -->
    <!-- span = inline -->

</body>
</html>
```

---

## 💡 Beginner Tips:

* Use `<div>` to group sections
* Use `<span>` to highlight small text
* `<div>` is used a LOT in real websites
* Styling comes later (CSS)

---

## ✅ Summary

* `<div>` → block element, new line
* `<span>` → inline element, same line
* Both are used for grouping content
* Very important for layout (later with CSS)

---

### 🚀 What’s Next?

You are now ready for **Mini Projects** 🎉
👍
