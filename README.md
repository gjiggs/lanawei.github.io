# Lenawei Safaris – Africa’s Premier Safari & Travel Company

[![Website Status](https://img.shields.io/badge/Live%20Site-Online-brightgreen)](https://www.lenawei-safaris.com)
[![Theme: Architect](https://img.shields.io/badge/Theme-Architect-blue)](https://github.com/pages-themes/architect)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> **Lenawei Safaris** offers unforgettable African tours, wildlife adventures, and cultural journeys across Kenya, Tanzania, Botswana, and beyond. Our local team delivers award-winning, responsible travel.

---

## Table of Contents

- [Live Preview](#-live-preview)
- [About Lenawei Safaris](#-about-lenawei-safaris)
- [Meet the Team](#-meet-the-lenawei-safaris-team)
- [Project Structure](#-project-structure)
- [Setup Instructions](#-how-to-set-up-lenawei-safaris-website-with-architect-theme)
- [How to Reference Assets](#-how-to-reference-assets)
- [Features](#-features)
- [Contact & Support](#-contact--support)
- [License](#-license)
- [Contributing](#-contributing)
- [Credits](#-credits)
- [Useful Links](#-useful-links)
---

## 🚀 Live Preview

Visit our site: [www.lenawei-safaris.com](https://www.lenawei-safaris.com)

---

## 🏞️ About Lenawei Safaris

Lenawei Safaris is Africa’s premier travel company. We offer ethical, immersive safari experiences led by certified local experts. Our mission is to connect travelers with nature, support communities, and champion conservation.

---

## 👥 Meet the Lenawei Safaris Team

### 🦁 Lucy Kago – Master of Impressions (Marketing & Brand Visionary)
Crafts unforgettable first impressions and shapes the Lenawei Safaris brand. From eye-catching campaigns to creative storytelling, Lucy ensures our message is as adventurous as our safaris.

- Build and maintain a powerful online and offline brand presence.
- Create exciting campaigns that target schools, churches, and corporate groups.
- Design captivating brochures and digital content that tell our story.
- Collaborate with team members to deliver consistent and compelling messaging.
- Form strong partnerships with organizations for exclusive safari experiences.

Instagram: [@lucy_kagoh](https://instagram.com/lucy_kagoh)

---

### 🦒 Pauline Tamara – Guest Happiness & Hospitality Negotiator
The voice behind our exceptional service—Pauline handles customer care with warmth and grace. She also negotiates the best accommodations to guarantee a comfortable and memorable experience.

- Be the friendly face and voice for all client interactions—before, during, and after safaris.
- Secure top-tier accommodations and facilities for every safari experience.
- Develop tailored safari packages for schools, church groups, and corporate retreats.
- Manage a smooth and efficient booking and inquiry system.
- Collect guest feedback to refine and elevate future safari experiences.

Instagram: [@ptama_rah](https://instagram.com/ptama_rah)

---

### 🦓 Titus Gitonga – Journey Captain (Transport & Tour Operations)
From the moment the wheels start turning, Titus is in command. He ensures smooth transportation and oversees every tour with precision, ensuring our guests enjoy a safe and seamless adventure.

- Organize and oversee safe, reliable transportation for every safari.
- Craft a detailed tour checklist to guarantee smooth operations.
- Lead and supervise all safari activities, ensuring a flawless guest experience.
- Perform dry runs for new safari routes to ensure safety and excitement.
- Ensure every tour blends adventure, learning, and unforgettable memories.

Instagram: [@to.sh342](https://instagram.com/to.sh342)

---

### 🐘 Jackson Wachiuri – Adventure Architect (Itinerary Design & Costing)
Jackson is the mastermind behind our exciting itineraries. With an eye for detail and value, he crafts well-planned journeys that deliver both adventure and affordability.

- Design exciting, customizable itineraries for schools, church groups, and corporate clients.
- Research and develop fresh, innovative routes and unique adventure experiences.
- Ensure all safari packages balance affordability and premium value.
- Adapt itineraries to fit client needs—whether it’s a spiritual retreat or a fun team-building day.
- Work closely with the team to ensure smooth execution of every adventure.

Instagram: [@jacksonescapes](https://instagram.com/jacksonescapes)

---

### 🦏 Lucas Bell – Innovation & Numbers Maestro (Technology & Finance)
Lucas blends tech-savvy brilliance with financial expertise. From managing digital platforms to balancing the books, he ensures our operations run smoothly and sustainably.

- Manage and enhance the company’s digital platforms for bookings and inquiries.
- Implement smooth and secure digital payment systems.
- Keep Lenawei’s finances in check with clear and transparent reporting.
- Use technology to improve customer experiences (virtual previews, live updates).
- Analyze financial and customer data to improve efficiency and profitability.

Instagram: [@belllucas34](https://instagram.com/belllucas34)

---

Follow our company: [@lenawei_safaris](https://instagram.com/lenawei_safaris)

---

## 📦 Project Structure

```
lenaweisafaris.github.io/
├── _config.yml
├── index.html              # Main landing page
├── css/
│   └── style.css           # Custom styles
├── js/
│   └── scripts.js          # Custom JavaScript
├── images/
│   ├── logo.png
│   ├── favicon.ico
│   ├── og-preview.jpg
│   ├── [gallery images...]
│   ├── [team images...]
│   ├── [blog images...]
│   ├── [award, partner images...]
├── README.md               # This file
├── LICENSE                 # MIT License
└── [additional assets/]
```

---

## 🛠️ How to Set Up Lenawei Safaris Website with Architect Theme

1. **Create `_config.yml`** in the root directory:

    ```yml
    title: Lenawei Safaris
    description: Africa’s Premier Safari & Travel Company
    show_downloads: true
    remote_theme: pages-themes/architect@v0.2.0
    plugins:
      - jekyll-remote-theme
    google_analytics: # [Your Google Analytics Tracking ID, if available]
    ```

2. **Custom CSS**  
   - Save your styles as `css/style.css`
   - Link them in `index.html` (inside `<head>`):

    ```html
    <link rel="stylesheet" href="css/style.css">
    ```

3. **Custom JavaScript**  
   - Save your scripts as `js/scripts.js`
   - Link them in `index.html` (inside `<head>`):

    ```html
    <script src="js/scripts.js" defer></script>
    ```

4. **Images**  
   - Place all images in the `images/` folder  
   - Reference them with relative paths in your HTML (e.g., `images/logo.png`)

5. **Homepage**  
   - Save your main HTML as `index.html` in the root

6. **README**  
   - Save this file as `README.md` in the root

7. **License**  
   - Include an MIT `LICENSE` file for open source compliance

8. **Contributing**  
   - (Optional) Add a `CONTRIBUTING.md` for contribution guidelines

---

## 📝 How to Reference Assets

- **CSS:**  
  `<link rel="stylesheet" href="css/style.css">`
- **JavaScript:**  
  `<script src="js/scripts.js" defer></script>`
- **Images (logo, gallery, team, etc):**  
  `<img src="images/filename.jpg" alt="Description">`
- **Favicon:**  
  `<link rel="icon" href="images/favicon.ico" type="image/x-icon">`

All asset links are **relative** to the root, making it easy to add or update files.

---

## 🌍 Features

- Responsive, modern landing page
- Architect theme (for GitHub Pages)
- SEO, Open Graph, Twitter Cards, Schema support
- Interactive navigation, hero, tours, gallery, blog, resources
- Sustainability, partners, awards, newsletter signup
- Contact & booking forms (use Gmail for contact)
- Custom JS for navigation, sliders, FAQ

---

## ✉️ Contact & Support

- **Gmail:** lenaweisafaris@gmail.com
- **Phone:** +254 792 164619
- **Instagram:** [@lenawei_safaris](https://instagram.com/lenawei_safaris)
- **Facebook:** [Lenawei Safaris](https://facebook.com/lenaweisafaris)

---

## 📜 License

Licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing

Issues and pull requests are welcome! See [CONTRIBUTING.md](docs/CONTRIBUTING.md).

---

## 🏗️ Credits

- [Architect Theme](https://github.com/pages-themes/architect) for Jekyll & GitHub Pages
- All Lenawei Safaris photography & content © Lenawei Safaris

---

## 🔗 Useful Links

- Instagram: [@lenawei_safaris](https://instagram.com/lenawei_safaris)

---
**Designed by Lenawei Safaris | All rights reserved.**

