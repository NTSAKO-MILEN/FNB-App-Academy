
# 📎My Notes on Hyperlinks in HTML

## 🌐 What Are Hyperlinks and Why They Matter to Me

As I learn to build websites and apps, I’ve discovered that **hyperlinks** are like the bridges of the internet. They allow users to **jump from one page to another**, whether it's on the same site or somewhere else on the web.

They’re important because:
- They **guide users** through my content (like going from the homepage to a contact page).
- They help **search engines understand** the structure of my site.
- They allow me to **reference useful external resources**.
- They make my site feel **connected, organized, and professional**.

---

## 🌍 How I Link to External Pages on the Web

When I want to link to a website that’s not part of mine (like Google or an article I like), I use this:

```html
<a href="https://www.google.com" target="_blank">Search on Google</a>
```

**Note to myself:**
- Always use `target="_blank"` when linking externally so the user stays on my site while opening the new one in a **new tab**.
- Double-check that external links are safe and relevant.

---

## 🏠 How I Link to Pages Within My Own Website

When I build multiple pages in a project (like `home.html`, `about.html`, `contact.html`), I use **internal links** to connect them:

```html
<a href="about.html">Learn more about me</a>
```

Other examples:
- Linking to a file in a subfolder:
  ```html
  <a href="projects/aws-project.html">My AWS Project</a>
  ```

- Linking to a homepage from anywhere:
  ```html
  <a href="/index.html">Go to Homepage</a>
  ```

This is super helpful for organizing my portfolio or app pages in a clean way.

---

## 🖼️ Making an Image Clickable (Image as a Link)

Sometimes, I want an image (like my logo or a banner) to be clickable. Here’s how I do that:

```html
<a href="https://linkedin.com/in/ntsakomabunda">
  <img src="my-logo.png" alt="Ntsako's Logo" width="150">
</a>
```

**Why I love this:**
- It makes my site **more visual and interactive**.
- Great for linking to **social profiles**, **projects**, or **external articles** using logos or badges.

---

✨ These notes help me keep track of what I’m learning while building real projects. Every link I add is a small step toward creating something meaningful and connected.

