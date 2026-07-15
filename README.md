# 🚰 JD Plumbers - Professional Plumbing Services Website

This is a multi-page responsive website built for **JD Plumbers**, a local trade business. The main goals of the site are to give the business a professional online presence, showcase their plumbing services, display clear pricing, and make it as easy as possible for customers to get a quote or call for an emergency repair.

👉 **[Click Here to View the Live Public Deployment](https://jaibe-444.github.io/jd-plumbers/)**

---

## 🎯 Project Goals & Target Audience

### 💼 Business Goals
* **Online Presence:** Establish an easy-to-find website for a traditional plumbing business to show off their expertise and look professional.
* **Lead Generation:** Make it incredibly simple for users to request emergency callouts or standard quotes, turning visitors into real customers.

### 👤 User Goals & Target Audience
* **User Goals:** Quickly find a trusted plumber, check if they handle specific problems, and find emergency contact numbers instantly during a household pipe crisis.
* **Target Audience:** Regular homeowners, landlords looking after rental properties, and local commercial property managers who need fast, trustworthy plumbing work.

---

### How These User Stories Were Met

To ensure a user-friendly experience, I designed and coded specific solutions for each of these goals:

* **Addressing Story 1 (Finding services instantly):** I structured the Home Page layout with a clear, prominent services section featuring categorized service cards (including the newly added cards for Boiler Repairs, Emergency Jetting, and Fixture Installations). This allows users to confirm within seconds of landing that JD Plumbers can resolve their exact plumbing issue.
* **Addressing Story 2 (Immediate emergency access):** I integrated a bright, high-visibility Emergency Hotline Link (`+44 99 88 77 66 99`) directly into the global header. Positioned right at the top of every page, mobile users can simply tap this link to trigger an immediate phone call during an active household emergency.
* **Addressing Story 3 (Booking without calling):** I built a fully functional, structured contact form on the dedicated Contact Page (`contact.html`). Complete with client-side input validation, it allows busy property owners to send a detailed inquiry and request a quote at any time of day without needing to make a phone call.

## 🎨 User Experience (UX) & Design

### User Stories
* **Story 1 (First-time visitor):** *As a first-time visitor, I want to instantly see if this business handles my specific issue (e.g., burst pipes, boiler repair) right on the home page.*
* **Story 2 (Emergency customer):** *As an emergency customer, I want to find a phone number immediately upon landing on the homepage.*
* **Story 3 (Busy homeowner):** *As a busy homeowner, I want a clear online contact form so I can request a booking or quote without waiting on a phone call.*

---

## 🛠️ UI/UX Optimization: Emergency Hotline Integration

### 📋 Feature Overview
To better serve users looking for urgent plumbing assistance and to help the business get more calls, an **Emergency Hotline Link (`+44 99 88 77 66 99`)** was added directly into the main website header. Positioned between the brand logo and the navigation menu, it gives immediate visual importance to emergency phone inquiries.

### ⚙️ Technical Implementation & Architecture

#### 1. Accessible HTML Markup Structure
The anchor tag was placed right inside the `.nav-container` wrapper. It uses the standard `tel:` protocol configuration so that users on mobile phones can simply tap the link to call immediately:


<a href="tel:+449988776699" class="header-hotline">
    <span>📞 Hotline:</span> +44 99 88 77 66 99
</a>

### 2. Layout Distribution & Typography Hierarchy

 * ** Desktop Alignment Layout: The website uses CSS Flexbox properties (display: flex; and justify-content: space-between;) on the .nav-container to automatically push the logo to the left, center the emergency hotline link so it stands out, and align the navigation buttons neatly on the right. **

 * **Typography Choices:**

   * ** Headers: 'Montserrat', sans-serif – Chosen because it is bold, modern, and looks highly professional for headings.

   * ** Body Text: 'Roboto', sans-serif – Used for clean readability across all service descriptions, ensuring a comfortable reading experience on both mobiles and desktop screens.

👉 <strong><a href="https://drive.google.com/file/d/1RWfXH4cNdOwVa5_hIhoZ_yhYMYF9l8jt/view?usp=drive_link" target="_blank">Click Here to View the wireframe</a></strong><br><br>

🖥️ Cross-Browser & Device Testing

To make sure the layout looks correct and functions properly across different web browsers, I tested the pages manually. You can check the proof screenshots in the Google Drive folders below:

👉 <strong><a href="https://drive.google.com/drive/folders/15VhQP9L-hiVZGncj-TdWdylykJf2Yjqi?usp=drive_link" target="_blank">Click Here to View the screenshot on Opera</a></strong><br>
👉 <strong><a href="https://drive.google.com/drive/folders/15VhQP9L-hiVZGncj-TdWdylykJf2Yjqi?usp=drive_link" target="_blank">Click Here to View the screenshot on Chrome</a></strong><br>

👉 <strong><a href="https://drive.google.com/drive/folders/1cAH_d--VtlieFx4mtI-tgfBqRoLB7K8H?usp=drive_link" target="_blank">Click Here to View the screenshot on Firefox</a></strong><br>
👉 <strong><a href="https://drive.google.com/drive/folders/1M-gz3KN4zUrxIIEHOqIo7gFsOff8PTKy?usp=drive_link" target="_blank">Click Here to View the screenshot on Edge </a></strong><br>


🎨 Color Palette & Styling

* **Primary Color (Deep Navy Blue - `#1B365D`):** Used to represent trust, reliability, and corporate professionalism, which are vital for a dependable emergency trade business.
* **Secondary/Accent Color (Water Cyan - `#00A3E0`):** Provides a bright contrast that fits the water/plumbing theme and highlights call-to-action buttons.
* **Neutral Backgrounds (Crisp White - `#FFFFFF` & Light Gray - `#F8F9FA`):** Used to maintain high readability, clean spacing, and an uncluttered look.
  **
⚡ Core Features Implemented

    Multi-Page Architecture: Clean navigation across three separate pages: Home (index.html), Services (services.html), and Contact (contact.html).

    Fully Responsive Flexbox Grids: Built using custom CSS and media queries. The layout changes smoothly from a wide multi-column layout on desktops down to a 2-column layout on tablets (max-width: 992px) before stacking vertically into a single column on mobile screens.

    Interactive Contact Form: A fully validated web form with input checks that ensure users format their emails correctly, fill out their names, and leave a proper message.

    Custom Assets: Added custom themed iconography and an embedded favicon so the company logo shows up nicely in the web browser tab.

🛠️ Technologies Used

  **  HTML5 - For semantic page structuring (<header, <nav, <main, <section, <footer).

   ** CSS3 - For custom layouts, typography styling, colors, and responsive media breakpoint design.

   * Git & GitHub - For version control management and pushing code updates.

   * GitHub Pages - For hosting the live public website.

   * W3Schools - Used as a helpful reference tool for looking up syntax examples.

  *  Replit.com - Used as an online workspace for writing, running, and testing out bits of code.

📊 Quality & Performance Validation

  *  Google Lighthouse Testing:

        Performance Core Audit Score: 95%

        Tested using the Google Chrome extension to make sure the pages load fast, image sizes are optimized, and everything passes accessibility checks.
---

## 🛠️ Code Validation (HTML/CSS)
To make sure the website's code is clean, standards-compliant, and error-free, I ran the files through official validation tools. You can view the verification screenshots here:

* 👉 **HTML Validation:** <strong><a href="https://www.awesomescreenshot.com/image/61884392?key=4a7be2b5e4ef44a30a7c680b91b79199" target="_blank">View Nu HTML Checker Validation Result</a></strong>
* 👉 **CSS Validation:** <strong><a href="https://www.awesomescreenshot.com/image/61884392?key=4a7be2b5e4ef44a30a7c680b91b79199" target="_blank">View W3C CSS Validation Result</a></strong>

---
🚀 Deployment & Local Setup
Live Deployment Steps

This project was deployed directly using GitHub Pages by following these standard steps:

   * Organized the files to ensure index.html sits at the absolute root level folder.

  *  Configured the GitHub Repository settings to build the live page from the main branch.

  *  The site updates automatically whenever new code changes are committed and pushed to GitHub.

How to Run Locally

To run this project on your own computer:

   * Clone the repository using Git:
    Bash

* 🖥️ View the <strong><a href="https://github.com/jaibe-444/jd-plumbers.git" target="_blank">git clone</a></strong>

    Open the project folder in your preferred text editor (like Visual Studio Code).

    Open the index.html file directly in any modern web browser to view the site locally.

📝 Credits & Acknowledgments

  *  Images: All placeholder imagery sourced from high-quality, royalty-free photography websites like Unsplash, Pexels, and Pixabay.

   * Icons: Visual icon vectors provided by FontAwesome and Flaticon.

 *   * 🛠️ <strong><a href="https://www.w3schools.com" target="_blank">W3Schools</a></strong> & <strong><a href="https://replit.com" target="_blank">Replit</a></strong>: Helpful tools used during development for syntax references and quick code compiling.
    
  *  **Educational Context:** Created as part of Milestone Project 1 for [Web Application Development / Code Institute].
