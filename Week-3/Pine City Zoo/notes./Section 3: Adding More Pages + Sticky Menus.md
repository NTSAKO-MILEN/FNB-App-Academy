
# My Notes – Section 3: Adding More Pages + Sticky Menus

## 📄 Lesson 12: Creating the Elephant Page (HTML)

### 🗂️ Steps Taken:

- 📝 Created a new HTML file for the Elephant Page.
- 🧷 Linked the `style.css` file in the `<head>`.
- 🧱 Inside the `<body>`:
  - 🔝 Added a top logo inside `#header`.
  - 📌 Created top menu links in `#tabs-top` (still using `#` placeholders).
  - 🐘 Inside `#main > #content > #info-box-full`:
    - 📸 Added an elephant image.
    - 🧾 Heading: **ELEPHANT**
    - 📚 Multiple `<p>` tags with fun elephant facts.
    - 📍 A bold **WHERE WILL YOU FIND THEM** heading followed by the location.
  - 🔚 Bottom menu links added inside `#tabs-bottom`.

### 🛠️ Reminders to Myself:

- ✏️ Double-check spelling for `img`, `src`, and folder names.
- 🧩 Quotes matter → `src="images/elephant.jpg"`
- 🔡 File names are case-sensitive → `Image.jpg` ≠ `image.jpg`
- 🔁 Use `/` not `\` for paths.
- ✅ Close all tags like `<div>`, `<a>`, `<img>` properly.

---

## 🎨 Lesson 13: Styling the Elephant Page (CSS)

### 🖌️ Style Tweaks:

- 💠 Styled `#info-box-full`:
  - Semi-transparent white background: `rgba(255, 255, 255, 0.8)`
  - width: 90%, centered with `margin: auto`
  - Added padding and `margin-top` for spacing
- 🔄 Made image inside `#info-box-full` stretch full width:

```css
#info-box-full img {
    width: 100%;
}
```

- 📍 Centered heading:

```css
#info-box-full h3 {
    text-align: center;
}
```

### 🛠️ CSS Tips to Remember:

- 🗂️ Make sure the file is named `style.css` and linked correctly.
- 📏 Use `{}` after selectors.
- 📌 Use `:` after properties, `;` after values.

---

## 🌍 Lesson 14: Creating the Places Page

### 🏞️ What I Did:

- 📝 Created a new file: `places.html`
- 🧱 Copied standard layout:
  - 🔝 Logo in `#header`
  - 📌 Top menu in `#tabs-top`
  - 📍 Bottom menu in `#tabs-bottom`
- 🔗 Inside `#main > #content`:
  - Added multiple `<a>` tags with class `info-box`:
    - ➡️ Arrow image: `next-arrow.png`
    - 🖼️ Thumbnail image (e.g., `amphitheatre-tn.png`)
    - 🧾 Heading for place/animal
    - 🧠 Short description

### 🛠️ Things to Check:

- 🧷 Image file names and paths must be exact.
- 🧹 All tags must be properly closed: `<a>`, `<div>`, etc.
- 🚫 Never use `\` in paths – only `/`.

---

## 📎 Lesson 15: Fixing Menus

### 🔧 Changes Made:

- 📝 Replaced all `href="#"` with real links:
  - ✅ `animals.html`
  - ✅ `index.html`
  - ✅ `places.html`
- 🧭 Menus now actually navigate to the right pages.

### 🛠️ Reminders:

- ✅ No typos in filenames → `animals.html` (not `animal.html`)
- 🔗 Wrap link values in `" "` and close all anchor tags.

---

## 🏛 Lesson 16: Creating the Amphitheatre Page

### 📄 What I Built:

- 📝 New HTML file: `amphitheatre.html`
- 📐 Used standard structure:
  - 🔝 Logo in `#header`
  - 📌 Top nav with real links
  - 📍 Bottom nav with full info inside `#info-box-full`
- 📸 Content added:
  - 🌄 Main image: `garden-amphitheatre.jpg`
  - 🧾 Heading: **AMPHITHEATRE**
  - 📜 Description of events
  - 🗓️ `<ul>` list with today's schedule
  - 📍 "Where will you find it?" location info
  - 🔙 Added a Back link → `index.html`

### 🛠️ Things I Fixed:

- 🧷 Some `src` values were missing quotes → `src="images/garden-amphitheatre.jpg"`
- ❌ Missed closing tags: `<img>`, `<ul>`, `<li>` — all fixed now.
