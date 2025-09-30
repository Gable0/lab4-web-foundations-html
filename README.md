Here’s a clean `README.md` you can drop into your project folder:

```markdown
# Lab 4 – Exploring HTML Elements

## Author
**Gable Krich**  
University of San Diego – Fall 2025  
Course: COMP 305 – Software Design
---

## 📄 Project Description
This lab was a "kitchen sink" of HTML tags. This was done do get me, and my classmates familiar with the basics of HTML and why it is an important language to understand even though it is slowly being forgotten. 

---

## ✅ Features
- Covers most core HTML tags:
  - Text elements (`<p>`, `<h1>`–`<h6>`, `<abbr>`, `<cite>`, `<dfn>`, etc.)
  - Structural elements (`<header>`, `<footer>`, `<section>`, `<article>`, `<main>`)
  - Forms (`<form>`, `<input>`, `<textarea>`, `<label>`, `<fieldset>`, `<legend>`)
  - Tables (`<table>`, `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, `<td>`, `<caption>`)
  - Media (`<img>`, `<audio>`, `<video>`, `<map>`, `<area>`)
  - Interactive elements (`<button>`, `<details>`, `<summary>`, `<dialog>`)
  - Inline elements (`<span>`, `<strong>`, `<em>`, `<mark>`, `<var>`, `<kbd>`)

---

## Validation Notes
When running the HTML through the W3C Validator, several issues were found and addressed:

1. **Duplicate `<head>` blocks inside `<body>`**  
   - Only **one `<head>`** is allowed, and it must be before `<body>`.  
   - Fix: Removed extra `<head>` tags from inside `<body>`

2. **Duplicate `<meta charset>` declarations**  
   - Only one `<meta charset>` is permitted at the top of the `<head>`.  
   - Fix: Removed additional copies inside the body

3. **`<style>` inside `<body>`**  
   - The validator does not allow `<style>` in the body.  
   - Fix: due to assignment rules, I did not fix

4. **Label `for` attributes not matching IDs**  
   - Every `<label for="…">` must match the `id` of a valid form control.  
   - Fix: Adjusted input IDs so they are unique

5. **Improperly closed tags**  
   - Fix: Closed all unclosed tags and cleaned up stray quotes in attributes.

6. **Demonstrating metadata tags**  
   - Metadata (`<title>`, `<meta>`, `<link>`) cannot be shown literally in `<body>`.  
   - Fix: Represented these tags as escaped text using `<pre><code>` or due to assignment rules, I did not fix

---

