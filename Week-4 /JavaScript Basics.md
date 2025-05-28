# 📒 JavaScript Notes

Welcome to my JavaScript journey. These are my personal notes as I learn JavaScript from scratch—keeping it simple, clear, and in my own words.

---

## 🧠 Lesson 1: What is JavaScript?

- JavaScript = makes websites **interactive**.
- It's the **brain** of a webpage.
- HTML gives **structure**, CSS gives **style**, JavaScript gives **behavior**.
- Used for websites, apps, games, automation, etc.

🧃 **Real-Life Analogy**:  
A webpage is like a robot:
- HTML = skeleton  
- CSS = clothes  
- JavaScript = brain that moves and reacts

---

## ✍️ Lesson 2: My First JavaScript Code

```html
<!DOCTYPE html>
<html>
  <head><title>Hello JavaScript</title></head>
  <body>
    <h1>Check the Console</h1>
    <script>
      console.log("Hello, world!");
    </script>
  </body>
</html>
```

✅ Open this in a browser → right-click → **Inspect → Console**

---

## 📦 Lesson 3: Variables (Storing Stuff)

```javascript
let name = "Ntsako";
let age = 25;
console.log(name);
console.log(age);
```

🧃 **Analogy**:  
Variables are like **labeled boxes** that hold values.

---

## 🧩 Lesson 4: Data Types

```javascript
let text = "Hello";       // String
let number = 123;         // Number
let isHappy = true;       // Boolean
let nothing = null;       // Null
let unknown;              // Undefined
```

Different types = different kinds of info I can store.

---

## ➕ Lesson 5: Operators (Doing Things)

```javascript
let a = 10;
let b = 5;
console.log(a + b);   // 15
console.log(a > b);   // true
```

- Math: `+`, `-`, `*`, `/`, `%`
- Compare: `>`, `<`, `==`, `===`, `!=`

---

## 🔁 Lesson 6: Functions (Reusable Actions)

```javascript
function greet(name) {
  console.log("Hello, " + name + "!");
}

greet("Ntsako");
```

🧃 **Analogy**:  
A function is like a **coffee machine** → press the button, get the same result.

---

## 🚦 Lesson 7: Conditionals (Decisions)

```javascript
let age = 18;

if (age >= 18) {
  console.log("You're an adult.");
} else {
  console.log("You're a minor.");
}
```

🧃 **Analogy**:  
Like a **fork in the road**—choose one path based on a condition.

---

## 🔂 Lesson 8: Loops (Repeating Things)

```javascript
for (let i = 1; i <= 5; i++) {
  console.log("Count: " + i);
}
```

🧃 **Analogy**:  
Like pressing repeat on a playlist.

---

## 🍎 Lesson 9: Arrays (Lists)

```javascript
let fruits = ["apple", "banana", "mango"];
console.log(fruits[0]);        // apple
console.log(fruits.length);    // 3
```

Arrays = boxes that hold **ordered lists** of stuff.

---

## 🗂️ Lesson 10: Objects (Grouped Info)

```javascript
let person = {
  name: "Ntsako",
  age: 25,
  isStudent: true
};

console.log(person.name);  // Ntsako
```

🧃 **Analogy**:  
An object = like a **contact card**: name, number, email all together.

---

📘 **Next Steps**  
I'll move on to DOM manipulation, events, and maybe build a tiny project soon!
