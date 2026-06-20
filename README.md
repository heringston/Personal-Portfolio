# Personal Portfolio Website

A clean, modern, and fully responsive personal portfolio website designed for an Aspiring Backend Developer. Built without frameworks, this portfolio highlights technical skills, features prominent projects, and provides contact information—all wrapped in a sleek, professional dark theme with smooth micro-animations.

## Features

- **Fully Responsive**: Adapts seamlessly to all screen sizes (mobile, tablet, desktop).
- **Modern Aesthetics**: Premium dark theme featuring glassmorphism and subtle CSS transitions.
- **Interactive UI**:
  - Smooth scrolling navigation.
  - Mobile-friendly hamburger menu.
  - Active section highlighting based on scroll position.
  - Scroll-to-top floating button.
  - Reveal-on-scroll animations using `IntersectionObserver`.
- **Card-based Layout**: Clean organization of skills and projects.
- **No Dependencies**: Built entirely with Vanilla HTML, CSS, and JavaScript.

## Technologies Used

- **HTML5**: Semantic markup.
- **CSS3**: CSS Grid, Flexbox, custom properties (variables), media queries, and animations.
- **Vanilla JavaScript (ES6)**: DOM manipulation, event listeners, Intersection Observer API.

## Local Setup Instructions

Since this is a static website, you do not need Node.js or any build tools to run it locally.

1. **Clone the repository** (if applicable) or download the files.
2. Open the project folder on your computer.
3. Simply double-click the `index.html` file to open it in your default web browser.
   - *Alternatively, use an extension like VS Code Live Server for hot reloading during development.*

## Updating Placeholders

Before deploying, ensure you have updated all the placeholder text and links throughout the `index.html` file.

Look for the following placeholders in `index.html` and replace them with your actual details:
- `[REPLACE WITH MY FULL NAME]`
- `[REPLACE WITH MY EMAIL ADDRESS]`
- `[REPLACE WITH MY GITHUB PROFILE]`
- `[REPLACE WITH MY LINKEDIN PROFILE]`
- `[PLACEHOLDER_TECH_STACK]` (Under the Certificate Tampering project)
- `PASSWORD_GUARDIAN_LIVE_URL`
- `PASSWORD_GUARDIAN_GITHUB_URL`
- `CERTIFICATE_PROJECT_GITHUB_URL`
- `BLOG_LIVE_URL`
- `BLOG_GITHUB_URL`
- `OPTIONAL` (For live demo links you don't have, you can either remove the anchor tag entirely or replace it with `#`)

## Vercel Deployment Instructions

Deploying this static website to Vercel Hobby is completely free and straightforward.

### Method 1: Using GitHub (Recommended)
1. Push your code to a new GitHub repository.
2. Go to [Vercel](https://vercel.com/) and log in (or sign up using GitHub).
3. Click on **Add New...** > **Project**.
4. Import your newly created GitHub repository.
5. Vercel will automatically detect that it's a static site. Leave all default settings as they are.
6. Click **Deploy**.
7. Once deployed, you will get a live URL (e.g., `your-portfolio.vercel.app`).

### Method 2: Using Vercel CLI
If you have Node.js installed, you can use the Vercel CLI:
1. Open your terminal in the project directory.
2. Run `npm i -g vercel` to install the CLI.
3. Run `vercel`.
4. Follow the prompts (log in, link to project, set up and deploy).

## License

This project is open-source and available under the [MIT License](LICENSE).
