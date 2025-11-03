# 🎨 CSS Basics — Button Styling Project

![HTML Badge](https://img.shields.io/badge/Language-HTML5-orange?logo=html5)
![CSS Badge](https://img.shields.io/badge/Language-CSS3-blue?logo=css3)
![Project Badge](https://img.shields.io/badge/Level-Beginner-brightgreen)
![License Badge](https://img.shields.io/badge/License-MIT-blue)

This project demonstrates the **basics of CSS styling** by recreating buttons and layouts similar to real-world websites like **YouTube, Amazon, GitHub, LinkedIn, and Uber**.  
It’s a great hands-on exercise to understand how **CSS properties** modify the look and behavior of HTML elements.

---

## 🧠 Project Overview

This project includes:
- Multiple styled buttons using **CSS classes**
- Basic HTML structure with headings and sections
- Realistic examples from well-known platforms
- Practice in **color schemes, spacing, borders, and font styling**

---

## 🏗️ HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
  <head> ... </head>
  <body>
    <!-- Buttons -->
    <button class="subscribe-button">SUBSCRIBE</button>
    <button class="join-button">JOIN</button>
    <button class="tweet-button">Tweet</button>
    
    <!-- Practice Exercises -->
    <h3>Practice Exercises</h3>
    <h4>1. Uber</h4>
    <button class="request-button">Request Now</button>
    ...
  </body>
</html>
````

* The `<body>` contains headings and multiple button elements.
* Each button is assigned a **CSS class** for custom styling.
* `<div>` and `<a>` tags are used for grouping and linking.

---

## 🎨 CSS Styling Concepts

The internal `<style>` tag defines all button classes.
Here are some examples:

### 🔴 YouTube Subscribe Button

```css
.subscribe-button {
  padding: 10px;
  background-color: rgb(179, 9, 9);
  color: white;
  border: none;
  border-radius: 2px;
  cursor: pointer;
}
```

* Uses **background color**, **padding**, and **rounded corners** for a clean look.
* `cursor: pointer;` changes the cursor on hover.

---

### 🟦 LinkedIn Buttons

```css
.linkedin-apply-button {
  background-color: rgb(10, 102, 194);
  color: white;
  border-radius: 20px;
  font-weight: bold;
}
.save-button {
  color: rgb(10, 102, 194);
  background-color: white;
  border: 1px solid rgb(10, 102, 194);
}
```

* Rounded edges and consistent color scheme to mimic LinkedIn design.
* Demonstrates **button pairs** — filled and outlined styles.

---

### 🛍️ Amazon Buttons

```css
.amazon-button {
  background-color: rgb(255, 216, 20);
  border-radius: 20px;
  font-weight: bold;
}
.buyNow-button {
  background-color: rgb(255, 164, 28);
  border-radius: 20px;
  font-weight: bold;
  margin-left: 15px;
}
```

* Bright, bold buttons with yellow and orange tones.
* Focus on **call-to-action design**.

---

### ⚫ Uber & GitHub Buttons

* **Uber:** Minimalistic with black background and white text.
* **GitHub:** Green signup button showing success state.

---

## 📘 Theory Concepts Covered

| Concept                          | Description                                          |
| -------------------------------- | ---------------------------------------------------- |
| **CSS (Cascading Style Sheets)** | Defines the visual presentation of web pages.        |
| **Selectors & Classes**          | Target specific HTML elements for styling.           |
| **Box Model**                    | Controls spacing using margin, padding, and borders. |
| **Colors & Fonts**               | Use RGB and font properties to create visual appeal. |
| **Buttons & Hover Effects**      | Apply interactivity and clickable styles.            |
| **Reusable Styles**              | Write modular CSS for consistency.                   |

---

## 🖼️ Output Preview

![CSS Buttons Preview](./screenshot.png)


---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/css-basics.git
   ```
2. Open the folder in your code editor.
3. Run the `index.html` file in your browser.

---

## 🧑‍💻 Author

**Venkata Vasu Nallamekala**
💡 Exploring Frontend Development and CSS styling fundamentals.
📍 Based in Hyderabad, India

> “CSS is not just about colors — it’s about communication through design.”

---

## 🧡 Made With

Made with ❤️ using **HTML5 & CSS3**
![HTML5 Logo](https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg)
![CSS3 Logo](https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg)

---

## 📄 License

This project is open-source and available under the **[MIT License](LICENSE)**.

