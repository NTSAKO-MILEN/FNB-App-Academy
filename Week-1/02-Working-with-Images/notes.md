# 📘 My Web Development Notes

## 🖼️ Working with Images in HTML

This document contains my personal notes as I learn how to add and manage images in HTML. These lessons help me build visually rich web pages while keeping everything organized and professional.

---

## 📁 Lesson 1: Creating an Images Folder

To keep my projects clean, I always start by creating a folder named `images`. This isn't required by HTML, but it's good practice to store all image assets there for easier file management.

---

## 🌄 Lesson 2: Adding an Image to a Web Page

To add an image, I use the `<img>` tag. It doesn’t need a closing tag and uses the `src` attribute to reference the file.

### ✅ Example:
```html
<img src="images/boat.jpg" />
```

### 🚨 Key Reminders:
- File names are **case-sensitive**
- Use **double quotes** around the `src` value
- Always use a **forward slash** (`/`) for folder paths
- Correct file extension is crucial (`.jpg` ≠ `.JPG`)

---

## 🖼️ Lesson 3: Image File Types

Here’s a summary of the image formats I should use based on the situation:

| Format | Best Use         | Characteristics |
|--------|------------------|------------------|
| GIF    | Icons/animations | Small size, supports transparency and animation |
| JPEG   | Photos           | Millions of colors, compressed |
| PNG    | Graphics/logos   | Lossless, supports alpha transparency |

🧠 **Resolution tip:** Web images are usually **72 dpi** for faster loading.

---

## 📐 Lesson 4: Resizing Images

To control how big or small my images appear, I use `width` and `height` attributes (in pixels).

### ✅ Example:
```html
<img src="images/boat.jpg" width="150" />
<img src="images/boat.jpg" height="100" />
```

### Common Mistakes to Avoid:
- Always use **double quotes**
- Spelling matters: `width`, `height`

---

## 🖼️ Lesson 5: Adding Multiple Images

Now I can add multiple images to a page using the same `<img>` tag structure.

### ✅ Example:
```html
<img src="images/cablecar.jpg" height="150" />
<img src="images/city.jpg" height="150" />
<img src="images/plane.jpg" height="150" />
```

### ✅ Checklist for Image Errors:
- File exists in the correct folder
- Spelling and capitalization are correct
- File extension matches
- Double quotes are used
- Forward slash (`/`) is used in paths

---

## 🧾 Final Notes

This guide is part of my personal documentation as I learn HTML. Keeping track of these details helps me become a more confident and capable web developer.

- 👨‍💻 Author: Ntsako-M Mabunda
- 🎯 Goal: To build responsive and visually appealing web pages
- 💡 Tip: Always test your image paths in a browser to verify everything is working!

---

Happy coding! 🌐
