# 🌐 Introduction to HTML

## 📌 What is HTML?

**HTML** stands for **Hyper Text Markup Language**, which is used to create the **structure of web pages**.

### 🔍 Breakdown:

* **Hyper** → Refers to **hyperlinks**, or **reference links** between web pages
* **Text** → The **content** or **information** displayed on a web page
* **Markup** → Defines the **presentation** and **layout** of the text
* **Language** → It is a **computer language** interpreted by web browsers

---

## 🏗️ Structure of an HTML Document

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!-- The content that should appear on the webpage -->
</body>
</html>
```

### 📘 Explanation:

* `<!DOCTYPE html>`
  Declares the document type and version of HTML (HTML5).
  `!` indicates importance (not a tag, but a declaration).

* `<html lang="en">`
  Root tag of the HTML document.
  The `lang="en"` attribute specifies the language (English).

* `<head>`
  Contains **metadata** (data about the document), such as charset, viewport settings, and the page title.

  * `<meta charset="UTF-8">`
    Sets the character encoding (supports most characters & symbols).

  * `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
    Ensures responsive behavior on different screen sizes.

  * `<title>Document</title>`
    Sets the title of the webpage (shown on the browser tab).

* `<body>`
  All visible **content** of the web page goes inside the body tag.
  Example: headings, paragraphs, images, buttons, links, etc.




