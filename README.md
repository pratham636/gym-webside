# 🏋️‍♂️ Pratham Fitness Hub

A modern, high-performance gym landing page for **Pratham Fitness**. This project features a clean user interface, custom typography via Google Fonts, and built-in JavaScript form validation.

---

## 🚀 Step-by-Step Implementation

### Step 1: Project Setup & Assets
To run this project, ensure your folder structure looks like this:
* `index.html` (The main code)
* `1.jpg` (Background Image)
* `1.png` (Logo Image)

> **Note:** The images must be named exactly `1.jpg` and `1.png` for the CSS to load them correctly.

### Step 2: Google Fonts API Integration
The "athletic" look of the site is achieved using the **Google Fonts API**:
* **The Link:** We import 'Baloo 2' and 'Baloo Bhai 2' in the `<head>` section via the Google CDN.
* **The CSS:** `font-family` rules are applied to the body, buttons, and form inputs to ensure a consistent, bold brand feel across the entire site.

### Step 3: Interactive Form Validation
The "Join Now" form uses JavaScript to validate user data in real-time using the `onfocusout` event:
* **Email Validation:** Uses a specific Regex pattern to ensure the email follows the `username@domain.com` format.
* **Phone Validation:** Custom logic optimized for Indian phone numbers (supporting +91, 0, or standard 10 digits starting with 6-9).

---

## 🛠️ Tech Stack
* **HTML5:** Semantic layout for SEO and structure.
* **CSS3:** Absolute positioning, hover transitions, and image filters (invert).
* **JavaScript:** Logic for form validation and user alerts.
* **Google Fonts API:** Enhanced typography for a modern UI.

## 💻 Installation & Usage
1. Clone this repository to your local machine.
2. Ensure your images (`1.jpg` and `1.png`) are in the same folder as `index.html`.
3. Open `index.html` in any modern web browser to view the site.
