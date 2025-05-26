

# 🚀 Deployment (My Notes)

In this lesson, I finally got to turn my HTML code into a real mobile app – yup, like an actual app I can run on my Android phone. Super exciting!

## 🧠 What I Learned
- **Deployment** is the process of packaging my project into a mobile app format.
- We’re using **Adobe PhoneGap Build** for this part.

## 💡 Why PhoneGap?
- It’s the **simplest and fastest** way to deploy HTML, CSS, and JS as a mobile app.
- Completely **free**.
- No need to install anything – it’s all **browser-based** and done **online**.

## 🔧 Tools & Links I Used
- [PhoneGap Build homepage](https://build.phonegap.com/) – where I upload and compile my project.
- `config.xml` – helps set the app’s name, version, permissions, etc. (like a blueprint for the app).
- [WinRAR](https://www.win-rar.com/) – used this to zip my project folder before uploading to PhoneGap.

---

## 📝 Reminder to Myself
Before uploading to PhoneGap Build, I need to:

1. Make sure all my project files (HTML, CSS, JS, images) are in **one folder**.
2. Add a proper **`config.xml`** file.
3. **Zip the entire folder** using WinRAR or any archiving tool.
4. Upload the ZIP file to PhoneGap Build and wait for it to compile.

Once done, I get an **APK file** that I can install on my phone.

---

## 🧾 Sample `config.xml` File

Here's the template I used for `config.xml`:

```xml
<?xml version="1.0" encoding="UTF-8" ?>
<widget xmlns = "http://www.w3.org/ns/widgets"
    xmlns:gap = "http://phonegap.com/ns/1.0"
    id = "com.example.myapp"
    version = "1.0.0">

  <name>MyApp</name>
  <description>
    My first mobile app created with PhoneGap!
  </description>
  <author email="me@example.com" href="http://example.com">
    Ntsako Mabunda
  </author>

  <content src="index.html" />
  <preference name="fullscreen" value="true" />
  <preference name="webviewbounce" value="false" />
  <preference name="orientation" value="portrait" />

  <platform name="android">
    <icon src="icon.png" />
    <splash src="splash.png" />
  </platform>
</widget>
```

Make sure to:
- Update the `id`, `name`, and `author` sections.
- Place your `icon.png` and `splash.png` images in the same folder as your other files.

---

## 🖼 Screenshot (PhoneGap Build)

Here’s what PhoneGap Build looks like when I upload the ZIP file and it compiles successfully:

> _🖼 To add your screenshot here, use this format once your image is ready:_
```
![PhoneGap Build Screenshot](path-to-your-image.png)
```
_Example:_
```
![PhoneGap Build Screenshot](./images/phonegap-success.png)
```

---
