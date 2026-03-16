# JobHub — Interactive Job Portal Dashboard

A fully functional job search and application tracking dashboard built with **vanilla HTML, CSS, and JavaScript** — no frameworks, no libraries.

> Built by Heeba Khan · CSE 2025 · [LinkedIn](https://linkedin.com/in/heeba-khan-b08910285) · [GitHub](https://github.com/heeba008)

---

## Live Demo
🔗 **[View Live on GitHub Pages](https://heeba008.github.io/job-portal-dashboard)**

---

## Screenshots

### Login Screen
![Login Screen](screenshots/login.png)

### Dashboard — Job Listings
![Dashboard](screenshots/dashboard.png)

### Job Cards with Apply & Bookmark
![Job Cards](screenshots/job-cards.png)

### Dark Mode
![Dark Mode](screenshots/dark-mode.png)

---

## What It Does

JobHub simulates a real-world job portal with complete user interaction — login, search, apply, bookmark, and track applications — all in a single HTML file with zero dependencies.

---

## Features

| Feature | Description |
|---|---|
| User Login | Username-based login with session management |
| Job Listings | 6 pre-loaded job cards with company, location, type, skills |
| Real-time Search | Live filter by title, company, location, or skill tags |
| Apply Tracking | One-click apply with status update and counter |
| Bookmarks | Save/unsave jobs, view in sidebar, click to navigate |
| Add New Job | Form to dynamically post new job listings |
| Dashboard Stats | Live counters — total jobs, applications sent, saved jobs |
| Dark / Light Mode | Toggle with smooth transitions, saved to localStorage |
| Toast Notifications | Success / error feedback for every user action |
| Fully Responsive | Works on mobile, tablet, and desktop |

---

## Tech Stack

```
HTML5       — Semantic markup, single-page structure
CSS3        — Flexbox, Grid, CSS Variables, animations, dark mode
JavaScript  — Vanilla ES6+, DOM manipulation, localStorage, state management
```

**No React. No jQuery. No Bootstrap. No npm.** Just clean, hand-written code.

---

## Key JavaScript Concepts Used

- **State management** — object-based app state tracking all jobs, applications, bookmarks
- **DOM manipulation** — dynamic card rendering, live search filtering
- **Event handling** — delegation pattern for dynamically added elements
- **localStorage API** — persisting dark mode preference across sessions
- **Set data structure** — tracking applied and bookmarked jobs efficiently
- **Template literals** — dynamic HTML generation for job cards
- **Form validation** — required field checks before job submission

---

## How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/heeba008/job-portal-dashboard.git

# 2. Open the file in your browser
# No server needed — just double-click job-portal.html
```

Or simply open `job-portal.html` in any modern browser. Works completely offline.

---

## Project Structure

```
job-portal-dashboard/
│
├── job-portal.html        # Complete app — HTML + CSS + JS in one file
├── screenshots/           # UI screenshots for README
│   ├── login.png
│   ├── dashboard.png
│   ├── job-cards.png
│   └── dark-mode.png
└── README.md
```

---

## What I Learned Building This

- How to manage **application state in vanilla JS** without any framework — tracking which jobs are applied or bookmarked using JavaScript `Set` objects
- Building a **real-time search** that filters across multiple fields simultaneously without any library
- Implementing **dark mode** properly using CSS custom properties (`--variables`) so every component switches cleanly with one class toggle
- Writing **modular, readable JavaScript** even in a single-file project by organizing functions clearly
- The importance of **empty states and user feedback** — what the app shows when there are no results or no saved jobs is just as important as the happy path

---

## Future Improvements

- [ ] Category and salary range filters
- [ ] Job detail modal with full description
- [ ] Application status tracking (Applied → Interview → Offer)
- [ ] Pagination for large job lists
- [ ] Sort by date, relevance, or salary
- [ ] Export saved jobs to PDF

---

## Author

**Heeba Khan**
- B.Tech CSE, IPS Academy Indore (2025)
- AWS Certified — Machine Learning & Cloud Foundations
- Full Stack Intern @ PrepInsta Technologies
- 📧 khanheeba284@gmail.com
- 🔗 [LinkedIn](https://linkedin.com/in/heeba-khan-b08910285)
- 💻 [GitHub](https://github.com/heeba008)

---

*This project is part of my frontend development portfolio. Open to frontend developer and graduate trainee opportunities. *
