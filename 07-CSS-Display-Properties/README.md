# 🌐 CSS Display Properties

## 🎥 [🔗 View Demo on LinkedIn](https://www.linkedin.com/posts/venkata-vasu-nallamekala_post7-cssdisplay-webdevelopment-activity-7389639881108447232-JIVY?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEqsHQsBBlOiEiJbGFjSZmYH4ot5V-GtPXo)

---

## 🧾 Project Overview

This project demonstrates the **fundamental usage of CSS Display Properties** through multiple real-world UI examples.  
Each section showcases how HTML elements can be structured and styled using CSS display techniques such as `block`, `inline`, and `inline-block`.

From simple form layouts to UI mockups of Google Search and Uber Request interfaces, this project focuses on how different display values influence the layout, alignment, and interaction of elements on a webpage.

---

## 💡 Key Concepts Covered

### 1️⃣ Display: `block`
Elements with `display: block` start on a **new line** and take up the **full width** available.  
Commonly used for structural elements such as:
```css
display: block;
````

**Examples in this project:**

* Input fields in the signup form.
* Google logo and search input box.
* Text boxes in the “Text Boxes in Separate Lines” section.

---

### 2️⃣ Display: `inline`

Elements with `display: inline` stay **on the same line** as adjacent elements.
They only occupy as much width as their content requires.

```css
display: inline;
```

**Examples in this project:**

* The "Yes" and "No" buttons next to the survey text.

---

### 3️⃣ Display: `inline-block`

This combines features of both block and inline elements —
elements remain inline but can have height, width, and margin applied.

```css
display: inline-block;
```

**Examples in this project:**

* The paragraph with `class="second-para"` used for the survey text layout.

---

### 4️⃣ Combining Display with Other CSS Properties

The project also applies other important CSS techniques to enhance visual appearance:

* **Box shadows** to create depth.
* **Rounded corners** using `border-radius`.
* **Hover effects** with smooth transitions.
* **Alignment and spacing** using `margin` and `padding`.

---

## 🧠 What You’ll Learn

* How the **CSS display property** affects element positioning.
* When to use `block`, `inline`, or `inline-block`.
* How to build **form layouts** and **UI components** using only HTML and CSS.
* How to create realistic UI examples like:

  * Google Search Box
  * Sign-Up Form
  * Uber Request Ride Form
  * Simple Customer Survey Interface

---

## 🧩 Section-wise Breakdown

### 🪄 1. Text Boxes in Separate Lines

Demonstrates the use of **block display** to make input fields appear one below the other.

```html
<input class="name-input" type="text" placeholder="Name" />
<input class="email-input" type="email" placeholder="Email" />
```

---

### 💬 2. Text with Two Buttons Next to Each Other

Uses `inline-block` for the text and `inline` for the buttons to align them on the same line.

```html
<p class="second-para">Would you like to take our quick survey?</p>
<button>Yes</button>
<button>No</button>
```

---

### 🔍 3. Google Search Section

Mimics Google’s search interface using `block` elements for vertical alignment, and a **shadow input box** to simulate depth.

```html
<img class="google-logo" src="./image.png" alt="Google Logo" />
<input class="shadow-input" type="text" placeholder="Search Google or type a URL" />
```

Key style:

```css
.shadow-input {
  display: block;
  box-shadow: 1px 1px 5px rgba(0, 0, 0, 0.5);
  border-radius: 20px;
}
```

---

### 🧾 4. Sign-Up Form

Shows a combination of inline and block elements.
The first and last name fields appear side by side, followed by email and a button below.

```html
<input class="first-name" type="text" placeholder="First name" />
<input class="last-name" type="text" placeholder="Last name" />
<input class="sign-up-email" type="email" placeholder="Email" />
<button class="sign-up-button">Sign Up</button>
```

Features:

* `border-radius` for smooth corners
* `transition` for hover color change
* Simple layout for real-world form design

---

### 🚖 5. Uber Request a Ride Form

This section recreates a **mini Uber-style form**, featuring:

* Input fields for pickup and destination
* Two action buttons (“Request now” and “Schedule for later”)

```html
<p class="uber-p">Request a ride now</p>
<input class="uber-input" type="text" placeholder="Enter pickup location" />
<input class="uber-input destination" type="text" placeholder="Enter destination" />
<button class="uber-request">Request now</button>
<button class="uber-schedule">Schedule for later</button>
```

Styling highlights:

* `background-color` to differentiate actions
* `opacity` change on hover
* Clean and minimal form layout

---

## 🎨 Styling Summary

| Property                 | Description                           | Used In                 |
| ------------------------ | ------------------------------------- | ----------------------- |
| `display: block;`        | Makes elements take full width        | Input fields, logos     |
| `display: inline;`       | Keeps elements in the same line       | Buttons                 |
| `display: inline-block;` | Allows spacing while remaining inline | Paragraphs with buttons |
| `box-shadow`             | Adds subtle depth                     | Search input box        |
| `border-radius`          | Rounds corners                        | Buttons and inputs      |
| `transition`             | Smooth hover animation                | Signup button           |
| `opacity`                | Hover effect                          | Uber buttons            |

---

## 🧰 Technologies Used

* **HTML5** – For structuring the webpage
* **CSS3** – For styling, layout control, and responsive design behavior

No JavaScript or frameworks were used — this project is purely HTML and CSS focused.

---

## 📚 Concepts Demonstrated

* **Form layouts** using different display properties
* **Inline alignment** of text and buttons
* **Block structure** for stacking content vertically
* **Hover effects** for better UI interactivity
* **Practical UI recreation** (Google, Uber, Sign-Up, etc.)

---

## 📎 Connect With Me

👋 **Venkata Vasu Nallamekala**
Passionate about web development and front-end design.
Always eager to explore how HTML, CSS, and JavaScript can be combined to create engaging web experiences.

🔗 **LinkedIn:** [Venkata Vasu Nallamekala](https://www.linkedin.com/in/venkata-vasu-nallamekala/)

---

## 🏁 Conclusion

This project provides a clear, hands-on way to understand how the `display` property in CSS controls element behavior on a webpage.
By experimenting with `block`, `inline`, and `inline-block`, developers can effectively design flexible and responsive layouts.
