# Assignment 2 – Portfolio Website

## Project Description
This project is a responsive **single-page portfolio website** built with **HTML, CSS, and JavaScript**.  
It includes the required sections:

- **About Me** (short intro + profile image + tagline)
- **Projects** (at least 2 projects with descriptions and images/placeholders)
- **Achievements**
- **Hobbies**
- **Contact** (form with Name, Email, Message — no backend)

The layout is designed to display well on **desktop, tablet, and mobile** using **CSS Grid/Flexbox**. The site also includes small interactive enhancements such as **smooth scrolling**, a **dark/light theme toggle**, and a **time-based greeting**.

---
### Additional features added
The website was further enhanced with:
- **Expandable/collapsible project cards** so each project can be opened and closed individually
- **Only one project open at a time** behavior for a cleaner layout
- A **Fun Fact** section that fetches and displays data from a **public API**
- **Loading, failure, and empty-state feedback** for the API section
- **Client-side contact form validation** for empty or invalid inputs
- **Animated success and error messages** for form feedback
- **Hover and transition effects** on buttons, cards, and navigation links for a more polished UI

---

## Setup Instructions (Run Locally)

### Option 1: Open directly in a browser
1. Download or clone this repository.
2. Open `index.html` in your browser.

### Option 2: Run using a local server (recommended)
**VS Code (Live Server):**
1. Open the project folder in VS Code.
2. Install the **Live Server** extension (if needed).
3. Right-click `index.html` → **Open with Live Server**.

**Python HTTP Server:**
```bash
cd assignment-1
python3 -m http.server 8000
```
Then open:
http://localhost:8000

## Performance
This site is lightweight (plain HTML/CSS/JS) and optimized for fast loading:
- Images use native lazy loading (`loading="lazy"`) to reduce initial page load work.
- No heavy frameworks or large libraries are used, keeping file sizes and runtime overhead low.


## AI Use Summary
AI was used as a support tool during development (planning, responsive layout guidance, and implementing specific JavaScript features).
It also helped with:

improving UI interactivity and transitions,
implementing animated form feedback,
adding API-based dynamic content and its user feedback states,
and debugging API integration issues.



A full and detailed report (tools used, benefits/challenges, learning outcomes, and how AI suggestions were reviewed and modified) is available here: docs/ai-usage-report.md