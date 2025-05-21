# 📎  Notes for Getting started with CSS

## 🎨 What is CSS and Why It's Important to Me

As I dive deeper into web development, I’ve learned that **CSS** (Cascading Style Sheets) is what makes my websites look amazing. It lets me **style the structure** created with HTML, making everything visually appealing and user-friendly.

- **CSS controls the look and feel** of my site (like colors, fonts, and background images).
- It’s **separate from HTML**, which is the structure. HTML = bones, CSS = clothes and makeup!

---

## 🚀 Why CSS is a Game Changer for My Website

Here’s why I can’t live without CSS:

- **Faster loading times**: Since CSS can be cached, it speeds up my website.
- **Saves time**: I only need to define the style once in my `style.css`, and it’s applied to my whole site.
- **Makes maintenance easier**: Changes in the CSS file apply everywhere, so I don't have to edit each page separately.

---

## 🗂️ Lesson 2: Linking External CSS File

### ⚡ How to Use External CSS to Style My Website

1. **Create a `style.css` file**. This is where all my styles live.
2. **Link `style.css`** to my `index.html` in the `<head>` section:
   ```html
   <head>
     <link rel="stylesheet" href="style.css">
   </head>
   ```

3. **Start styling** in `style.css`. For example, change the color of the heading:
   ```css
   h1 {
     color: green;
   }

   p {
     color: coral;
   }
   ```

---

## 📝 CSS Syntax Cheat Sheet

| Rule                          | Example                              | Tip                                       |
|-------------------------------|--------------------------------------|-------------------------------------------|
| Selector + Curly Brackets     | `h1 { color: green; }`               | Use curly brackets `{}` after the selector |
| Property: Value;              | `color: green;`                      | **Colon `:`** after property, **semicolon `;`** after value |
| Quotes                        | `rel="stylesheet"`                   | Use **double quotes** around HTML attributes |
| File Naming                   | `style.css`                          | File names must match exactly (case-sensitive) |
| Spelling                      | `color`, not `colour`                | CSS uses **American spelling** |

---

## 🖋️ CSS Fonts: How to Change Fonts on My Website

1. **Set the font family** using the `font-family` property. For example:
   ```css
   h1 {
     font-family: sans-serif;
   }

   p {
     font-family: fantasy;
   }
   ```

2. **Other important tips:**
   - **Hyphenated Properties**: Use dashes like `font-size` or `font-weight`.
   - **Font Size Units**: Don’t forget to add units like `px` (e.g., `font-size: 14px;`).

---

## ✨ Quick Reminders:

- HTML = **structure** (content), CSS = **style** (appearance)
- Always **link `style.css`** properly in the `<head>`
- **Use curly brackets, semicolons, and proper spelling** in CSS
- Don’t forget to check **font sizes** and **use correct units** like `px`

---

✨ **CSS is the magic wand** that turns my web pages from plain to professional. As I add styles, I can see my websites become more vibrant and functional. Every little tweak is a step closer to a polished project!
