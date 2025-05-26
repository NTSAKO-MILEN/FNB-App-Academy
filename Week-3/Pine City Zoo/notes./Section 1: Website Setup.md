
# 🐾 Pine City Zoo App – Step-by-Step Development Notes

This guide documents how I built the **Pine City Zoo** tour guide web app.

---

## 📁 Section 1: Initial Setup and Home Page Styling

### ✅ Lesson 1: Setting up the Development Environment

**Steps I followed:**
1. Created a folder called `Pine City Zoo` inside my `Documents/Websites` directory.
2. Inside that folder, I created a subfolder named `images` for storing all image files.

**💡Tips I kept in mind:**
- Always saved files in the correct folder.
- Used `.html` as the correct extension when creating HTML files.
- Avoided saving files like `index.txt.html`.
- Made a habit of saving my work regularly.

---

### ✅ Lesson 2: Making the Home Page

**Steps I followed:**
1. Created an `index.html` file.
2. Added the following HTML structure:

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <div id="header">
      <img src="images/logo.png"/>
    </div>
    <div id="tabs-top">
      <a href="#">ANIMALS</a>
      <a href="#">MAP</a>
      <a href="#">PLACES</a>
    </div>
    <div id="main-home">
      <img src="images/map.png" width="100">
    </div>
    <div id="tabs-bottom">
      <a href="#">WEATHER</a>
      <a href="#">FEEDBACK</a>
    </div>
  </body>
</html>
```

**💡Tips I kept in mind:**
- Spelled `img` and `src` properly.
- Used double quotes for attributes.
- Used the correct path to images: `images/logo.png`.
- Matched letter case in file names.
- Used forward slashes `/`, not backslashes `\`.

---

### ✅ Lesson 3: Styling the Header Section

**Steps I followed:**
1. Created a `style.css` file in the main project folder.
2. Added these styles for the `body` and `#header`:

```css
body {
  padding: 0;
  margin: 0;
  font-family: Helvetica;
}

#header {
  position: fixed;
  top: 0;
  left: 0;
  z-index: 500;
  width: 100%;
  height: 80px;
  background-image: url('images/wood-bg.png');
  background-repeat: repeat-x;
}

#header img {
  display: block;
  margin: auto;
  height: 70%;
  padding-top: 15px;
}
```

**💡Tips I kept in mind:**
- Used correct CSS syntax with curly braces `{}`.
- Ended each property with a `;`.

---

### ✅ Lesson 4: Home Page Styles – Top Tabs

**Steps I followed:**
1. Styled the top navigation tabs with this CSS:

```css
#tabs-top {
  position: fixed;
  top: 80px;
  left: 0;
  z-index: 500;
  width: 100%;
  height: 40px;
  background-color: darkgreen;
}

#tabs-top a {
  float: left;
  display: block;
  width: 33%;
  height: 35px;
  font-weight: 700;
  color: white;
  text-align: center;
  text-decoration: none;
  padding-top: 12px;
}
```

**💡Tips I kept in mind:**
- Checked for correct file names and links to `style.css`.
- Used `color` instead of `colour`.

---

### ✅ Lesson 5: Home Page Styles – Main Section

**Steps I followed:**
1. Styled the main content section:

```css
#main-home {
  margin-top: 120px;
}
```

**💡Tips I kept in mind:**
- Always ensured consistent linking to `style.css`.
- Used correct CSS syntax and punctuation.

---

### ✅ Lesson 6: Home Page Styles – Bottom Tabs

**Steps I followed:**
1. Styled the bottom (footer) navigation tabs:

```css
#tabs-bottom {
  position: fixed;
  bottom: 0;
  left: 0;
  z-index: 500;
  width: 100%;
  height: 40px;
  background-color: forestgreen;
}

#tabs-bottom a {
  float: left;
  display: block;
  width: 50%;
  height: 35px;
  font-weight: 700;
  color: white;
  text-align: center;
  text-decoration: none;
  padding-top: 12px;
}
```

**💡Tips I kept in mind:**
- Validated every selector and bracket.
- Checked the link to `style.css`.

---

*⏳ More sections coming... These notes are not yet complete.*

