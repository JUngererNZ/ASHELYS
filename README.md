# Ashlys Bakes - Portfolio Website

Welcome to the official repository for **Ashlys Bakes**, a custom, lightweight, and responsive portfolio website designed to showcase artisanal baked goods. This project was built to provide a clean, static, and easily maintainable digital presence.

---

## 1. Project Design & Vision

### Design Philosophy
The website follows a "handmade, not overbuilt" philosophy. It focuses on:
- **Visual Impact**: High-fidelity product photography in a clean, white-heavy gallery layout.
- **User Experience**: A one-page, scroll-friendly navigation that keeps focus on the baked goods.
- **Performance**: Static HTML/CSS architecture ensures lightning-fast loading speeds, crucial for image-heavy pages.
- **Branding**: A warm, inviting aesthetic using a refined palette (inspired by artisanal bakery trends) to convey trust and craftsmanship.

### Visual Identity
The brand "Ashlys Bakes" uses a curated color scheme and typography to establish a professional yet personal connection with customers. The site features:
- **Typography**: Elegant serif headings for authority, balanced with clean, readable sans-serif body text.
- **Colors**: A muted, warm palette (cream, soft earth tones) that mimics the cozy, rustic feel of a local bakery.
- **Layout**: A responsive gallery grid that adapts seamlessly to desktop, tablet, and mobile viewing.

---

## 2. Implementation & Technical Architecture

### Tech Stack
- **Framework**: Static HTML5 & CSS3.
- **Hosting**: GitHub Pages (free, high-uptime, and integrated).
- **Automation**: Formspree integration for enquiry forms (no backend required).
- **Structure**: Modular directory organization for weekly/monthly content scaling.

### Directory Structure
To maintain order as the business grows, the project uses a chronological folder system. This allows Ashlys to drop photos weekly and reference them instantly in the portfolio.
```
/
├── index.html            # Gateway landing page
├── baker-portfolio.html  # Main gallery & enquiry page
└── 2026/
    ├── jan/ (week1, week2, week3, week4)
    ├── feb/ ...
    └── [up to June]
```

### Key Functionality
- **Form Integration**: Integrated Formspree endpoint in the `#contact` section, enabling direct order enquiries via email.
- **Responsive Navigation**: Smooth scrolling between sections (`#portfolio`, `#about`, `#contact`).
- **Dynamic Themes**: Built-in support for light and dark modes, detected automatically via user system preferences.
- **Easy Maintenance**: A redirection landing page (`index.html`) ensures that the portfolio can be rebuilt or moved without ever breaking the main site link.

---

## 3. Deployment & Workflow

### Getting Started
1. **Clone the Repo**: `git clone https://github.com/JUngererNZ/ASHELYS`
2. **Form Setup**: Sign up at [Formspree](https://formspree.io), create a form, and replace the `YOUR_FORM_ID` in `baker-portfolio.html`.
3. **Add Content**: Organize images into the `2026/` structure.
4. **Update**: Link new images in the gallery grid and commit changes.

### Publishing to GitHub Pages
1. Push changes to the `main` branch.
2. Go to **Settings > Pages** in your GitHub repository.
3. Select **Deploy from a branch** (root folder).
4. Save and wait 1–5 minutes. Your site will be live at:
   `https://juungerernz.github.io/ASHELYS`

### Future Scaling
This site is built as a placeholder, but designed to scale. As the business grows, this structure can easily transition to a full headless CMS or a dynamic e-commerce integration without changing the underlying host or domain.
