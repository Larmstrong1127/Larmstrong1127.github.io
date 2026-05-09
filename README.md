# Landon Armstrong — Developer Portfolio

Personal developer portfolio built with vanilla HTML, CSS, and JavaScript. No frameworks required — just open `index.html` in a browser.

**Developer:** Landon Armstrong
**GitHub:** [Larmstrong1127](https://github.com/Larmstrong1127)
**Email:** Landon.Armstrong@stmartin.edu

---

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and semantic markup |
| CSS3 | Styling, animations, and responsive layout |
| JavaScript (ES6+) | Interactivity, filtering, and scroll effects |
| Google Fonts (Inter) | Typography |

---

## Features

- **Animated hero section** — Blob background animation and typewriter effect cycling through roles
- **Filterable project grid** — Filter projects by category (All / Web Dev / Game Dev)
- **Skills grid** — Visual display of technical skills with core-skill highlighting
- **Timeline experience section** — Education and work experience in a readable timeline layout
- **Contact section** — Direct links to email and GitHub
- **Scroll-triggered animations** — Cards and sections fade in as you scroll
- **Mobile responsive** — Hamburger navigation menu for small screens

---

## How to View

### Option 1: Open Directly

Simply open `index.html` in any modern browser — no build step, no server required.

### Option 2: Live Server (VS Code)

1. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code
2. Right-click `index.html` and select **Open with Live Server**

---

## How to Add a New Project

Open `index.html` and find the `PROJECTS` array near the top of the `<script>` section. Add a new object following this format:

```javascript
{
  title: "My New Project",
  description: "A short description of what this project does.",
  tech: ["React", "Node.js", "MongoDB"],
  category: "webdev",       // "webdev" or "gamedev"
  github: "https://github.com/Larmstrong1127/my-new-project",
  demo: ""                  // leave empty if no live demo
}
```

Save the file and refresh your browser — the card will appear automatically.

---

## Customization

| What to Change | Where to Find It |
|---|---|
| Your name and tagline | Hero section in `index.html` |
| Profile photo | Replace `assets/profile.jpg` with your own photo |
| Typewriter roles | Edit the `roles` array in the script section |
| Skills list | Update the skills grid in the HTML |
| Color scheme | Edit the CSS variables at the top of the `<style>` block |
| Social links | Update href values in the contact section |

> **Note:** Add your own profile photo as `assets/profile.jpg` to display it in the hero section.

---

## Project Structure

```
portfolio-website/
├── index.html       # Main file — all HTML, CSS, and JS in one place
└── assets/
    └── profile.jpg  # Add your own photo here
```

---

## License

This project is for personal and portfolio use.
