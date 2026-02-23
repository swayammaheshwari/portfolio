# Swayam Maheshwari | Portfolio

This is a beautiful, AI-themed portfolio website for a Fullstack Developer built with pure HTML and [Tailwind CSS](https://tailwindcss.com/). It is designed to be easily deployed on GitHub Pages.

## Features
- **Responsive Design**: Mobile-first architecture ensuring perfect display on all devices.
- **Glassmorphism UI**: Modern aesthetic with translucent backgrounds and ambient blurs.
- **Tailwind CSS**: Utility-first styling with custom configurations.
- **Optimized**: Fast loading speeds and semantic HTML structure.

## Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/swayammaheshwari/swayammaheshwari.github.io.git portfolio
   cd portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run for Development**
   This command starts the Tailwind CSS JIT compiler to watch for changes in HTML files:
   ```bash
   npm run dev
   ```
   Open `index.html` in your browser.

4. **Build for Production**
   This command minifies the CSS output for deployment:
   ```bash
   npm run build
   ```

## Customization

- **Profile Picture**: Replace `assets/profile.jpg` with your own image.
- **Colors & Fonts**: Modify the `tailwind.config.js` to change the primary, secondary, and accent colors.
- **Content**: Update the `index.html` carefully to modify text, links, and project descriptions.

## Deployment to GitHub Pages

Since this is a static website, deploying to GitHub Pages is straightforward:
1. Ensure the generated `./css/output.css` is built (`npm run build`). Note: Usually we ignore build files, but for a simple GitHub pages deploy without actions, removing `css/output.css` from `.gitignore` allows you to push the built CSS directly. 
2. Push all the files to your GitHub repository (e.g., `swayammaheshwari/swayammaheshwari.github.io`).
3. Go to Repository Settings -> Pages.
4. Set the source to deploy from a branch (e.g., `main`), and hit Save.

---
Built by Swayam Maheshwari.
