# 🏋️‍♂️ Pratham Fitness Hub

A modern, high-performance gym landing page for **Pratham Fitness**. This project features a clean user interface, custom typography via Google Fonts, and built-in JavaScript form validation.

---

## 🚀 Step-by-Step Implementation

### Step 1: Project Setup & Assets
To run this project, ensure your folder structure looks like this:
* `index.html` (The main code)
* `1.jpg` (Background Image)
* `1.png` (Logo Image)

> **Note:** The images must be named exactly `1.jpg` and `1.png` for the CSS to load them automatically.

### Step 2: Google Fonts API Integration
The "athletic" look of the site is achieved using the Google Fonts API in two parts:
1. **The Link:** We import 'Baloo 2' and 'Baloo Bhai 2' in the `<head>` section.
2. **The CSS:** We apply `font-family: 'Baloo 2', cursive;` to the body, buttons, and form inputs for a consistent brand feel.

### Step 3: Interactive Form Validation
The "Join Now" form includes custom JavaScript functions to ensure data quality:
* **Email Validation:** Uses Regex (`/^\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+$/`) to check for a valid email format.
* **Phone Validation:** Specifically formatted for Indian numbers, checking for a 10-digit number starting with 6-9.

---

## 🛠️ Tech Stack
* **HTML5:** Semantic layout.
* **CSS3:** Custom positioning, hover effects, and transparency filters.
* **JavaScript:** Client-side form logic and alerts.
* **Google Fonts API:** Professional typography.

## 💻 Installation
1. Clone this repository.
2. Ensure your images are in the root directory.
3. Open `index.html` in any modern web browser.

---

## 📝 Future Enhancements
* [ ] Make the layout fully responsive for mobile devices using Media Queries.
* [ ] Move internal CSS and JS to external `.css` and `.js` files.
* [ ] Add a "Dark Mode" toggle.
