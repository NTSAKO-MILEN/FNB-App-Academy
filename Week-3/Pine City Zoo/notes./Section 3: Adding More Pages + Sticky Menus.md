
🧠 My Notes – Section 3: Adding More Pages + Sticky Menus

📄 Lesson 12: Creating the Elephant Page (HTML)
1. I created a new HTML file for the Elephant Page.
2. Linked the style.css file in the <head>.
3. Inside the <body>:
   - I added a top logo using the #header div.
   - Created top menu links inside #tabs-top. (Still had # placeholders for now.)
   - Used #main > #content > #info-box-full to insert:
     - An elephant image.
     - Heading: “ELEPHANT”.
     - Multiple <p> tags explaining facts about elephants.
     - A bold heading for WHERE WILL YOU FIND THEM followed by its location.
   - Added bottom menu links inside #tabs-bottom.

🛠 Reminder to myself (from the tips):
- Watch my spelling for img, src, and folder names.
- Always double check quotes: src="images/elephant.jpg"
- Match uppercase/lowercase exactly — Image.jpg ≠ image.jpg
- Use / not \
- Close all tags like <div>, <a>

🎨 Lesson 13: Styling the Elephant Page (CSS)
1. In my style.css file, I styled #info-box-full:
   - Background is slightly see-through white using rgba(255, 255, 255, .8).
   - Width is 90%, centered with margin: auto.
   - Added top margin and padding for spacing.
2. Made the image inside #info-box-full stretch full width using:
   #info-box-full img {
       width: 100%;
   }
3. Centered the heading (h3) using:
   #info-box-full h3 {
       text-align: center;
   }

🛠 CSS Tips I kept in mind:
- Confirm file name is style.css and properly linked.
- Don’t forget curly braces {} after the selector.
- Colon : after property, semicolon ; after value.

🌍 Lesson 14: Creating the Places Page
1. Created a new HTML file called places.html.
2. Copied the standard layout:
   - Logo in #header
   - Top nav in #tabs-top
   - Bottom nav in #tabs-bottom
3. In #main > #content, I added multiple a tags with class info-box:
   - Each one has:
     - An arrow image (next-arrow.png)
     - A thumbnail image (e.g., amphitheatre-tn.png, elephant-tn.png)
     - A heading with the place/animal name
     - A short description

🛠 Places Page Notes:
- Double check if all image file names and paths are correct.
- Close all tags — I had to fix a few <a> and <div> tags.
- Use / instead of \ for file paths.

🧷 Lesson 15: Fixing Menus
1. I replaced all href="#" with actual filenames:
   - animals.html
   - index.html
   - places.html

2. This made sure my top and bottom menus actually navigate.

🛠 Tips to remember:
- No typos in filenames (animals.html, not animal.html)
- Still need to wrap all links correctly with " and close all tags.

🏛 Lesson 16: Creating the Amphitheatre Page
1. Created a new HTML file (e.g., amphitheatre.html)
2. Used the standard structure:
   - Logo (#header)
   - Top menu with real links
   - Bottom section with full info inside #info-box-full
3. Added:
   - A main image (garden-amphitheatre.jpg)
   - Heading: “AMPHITHEATRE”
   - Description of events and what to expect
   - <ul> list with today's schedule
   - “Where will you find it?” with location info
4. Finally, I added a Back link to index.html.

🛠 Things I had to fix:
- Some image links were missing quotes → src="images/garden-amphitheatre.jpg"
- Missed closing some tags like <img>, <ul>, and <li> — fixed that.

