🧭 Section 2: Adding More Pages and Information Cards
-----------------------------------------------------

✅ Lesson 7: Animal Page HTML

Steps I followed:
1. I created a file called `animals.html`.
2. I copied the same layout from `index.html` for consistency.
3. I added an info card block that links to an animal (elephant):

```html
<div id="main">
  <div id="content">
    <a class="info-box" href="#">
      <img class="right" src="images/next-arrow.png"/>
      <img src="images/elephant-tn.png"/>
      <h3>ELEPHANT</h3>
      <p>Gentle giants of the jungle</p>
    </a>
  </div>
</div>
```

🛠️ Tips I kept in mind:
- Carefully checked `src="images/elephant-tn.png"` → folder and file spelling must be exact.
- Made sure `img`, `href`, and double quotes were all typed properly.
- Watched out for case sensitivity and forward slashes (`/` not `\`).


✅ Lesson 8: Animal Page CSS

Steps I followed:
1. Styled the background and spacing for the Animals page in `style.css`:

```css
#main {
  margin-top: 119px;
  background: url('images/map-blur.png');
  background-repeat: repeat-y;
}

#content {
  padding-top: 1px;
  padding-bottom: 50px;
}
```

🛠️ Tips I kept in mind:
- Confirmed stylesheet is linked correctly: `rel="stylesheet"` and `href="style.css"`.
- Double-checked all brackets `{}`, colons `:`, and semicolons `;`.


✅ Lesson 9: Animals Page Link Styling

Steps I followed:
1. Styled the info card blocks with a bright background and centered layout:

```css
a.info-box {
  text-decoration: none;
  background: rgba(255, 225, 55, 0.8);
  width: 90%;
  height: 90px;
  display: block;
  margin: auto;
  margin-top: 12px;
  padding: 1px;
}
```

🛠️ Tips I kept in mind:
- Checked CSS syntax and curly brackets.
- Verified property-value pairs are followed by colons and semicolons.

✅ Lesson 11: Animal Page More Links

Steps I followed:
1. I added more `a.info-box` sections for different animals (GEMSBOK and GIRAFFE):

```html
<a class="info-box" href="#">
  <img class="right" src="images/next-arrow.png"/>
  <img src="images/gemsbok.png"/>
  <h3>GEMSBOK</h3>
  <p>Come and see the majestic gemsbok</p>
</a>

<a class="info-box" href="#">
  <img class="right" src="images/next-arrow.png"/>
  <img src="images/giraffe-tn.png"/>
  <h3>GIRAFFE</h3>
  <p>Our giraffe loves company</p>
</a>
```

🛠️ Tips I kept in mind:
- Used the exact same layout and structure for all cards.
- Double-checked that each image path (like `images/giraffe-tn.png`) exists and is spelled correctly.
- Ensured that all tags were properly opened and closed (e.g. `<a>`, `<div>`).


⏳ We’re still not done. Another section is coming up!




