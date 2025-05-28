# 📌 HTML Tags – Beginner's Guide

In HTML, **tags** are special codes used to define the structure and content of a webpage. Tags are enclosed within angle brackets `<>`.

## 🏷️ What is a Tag?

A **tag** gives meaning to the content in an HTML document. Tags are enclosed in angle brackets like this:

```html
<tagname>Content</tagname>
```

There are **two main types** of HTML tags:

---

## 1️⃣ Paired Tags (Container Tags)

These tags come in a **pair**:

- An **opening tag**: `<tagname>`
- A **closing tag**: `</tagname>`

The content between these tags is called:

- `innerHTML`
- `innerText`
- or simply the **text content**

### ✨ Example:

```html
<p>This is a paragraph.</p>
```

Here:

- `<p>` is the **opening tag**
- `</p>` is the **closing tag**
- `This is a paragraph.` is the **inner text**

---

## 2️⃣ Unpaired Tags (Self-Closing Tags / Empty Tags)

These tags **do not need a closing tag**. They are called **self-closing** or **empty** tags.

### ✨ Example:

```html
<hr />
```

- `<hr/>` is a horizontal line tag.
- It doesn't need a closing tag like `</hr>`.

Other common self-closing tags:

```html
<br />
<!-- Line Break -->
<img />
<!-- Image -->
<input />
<!-- Input Field -->
```

---

## ✅ Summary

| Tag Type     | Has Opening & Closing? | Example       |
| ------------ | ---------------------- | ------------- |
| Paired Tag   | Yes                    | `<p>Text</p>` |
| Unpaired Tag | No (self-closing)      | `<hr/>`       |

---

> 🔰 **Tip for Beginners:**
> Always use proper tag pairs unless it's a self-closing tag. It helps browsers understand and display your webpage correctly.

