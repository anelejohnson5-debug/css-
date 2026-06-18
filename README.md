# SOS Children's Villages – NGO Website

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)

A multi-page informational website built for **SOS Children's Villages**, a non-governmental organisation (NGO) dedicated to supporting children without parental care. This project was developed as part of a web development assessment and showcases front-end development skills using HTML5 and CSS3.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Pages](#pages)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [File Structure](#file-structure)
- [Changelog](#changelog)
- [References](#references)

---

## About the Project

SOS Children's Villages is an international non-governmental social development organisation that supports children who have lost parental care or who are at risk of losing it. This website was designed to represent the organisation online, providing visitors with information about the cause, ways to get involved, and how to make contact.

The website was designed with a consistent colour palette, typography, and layout across all pages, following a shared external stylesheet (`style.css`).

---

## Pages

| Page | Filename | Description |
|---|---|---|
| Home | `index.html` | Landing page with hero section, stats bar, and calls to action |
| About | `about.html` | Information about SOS Children's Villages and its mission |
| Programs | `programs.html` | Overview of programmes and services offered |
| Gallery | `gallery.html` | Photo gallery showcasing the organisation's work |
| Donate | `donate.html` | Donation options and how to contribute |
| Contact | `contact.html` | Contact form and location details |

---

## Features

- **Sticky navigation header** — Remains visible as the user scrolls for easy navigation.
- **Hero section** — A full-width banner with a gradient background, headline, and call-to-action buttons.
- **Stats bar** — Displays key impact statistics (e.g. children helped, countries active) in a highlighted bar.
- **Call-to-action buttons** — Prominent Donate, Volunteer, and Sponsor buttons with hover effects.
- **Responsive design** — Layout adjusts for desktop, tablet, and mobile screen sizes using CSS media queries.
- **Consistent styling** — All pages share a single external CSS file for a unified look and feel.
- **Image gallery** — A grid-based photo gallery with hover zoom effects.
- **Contact form** — A styled form with text, email, and textarea inputs plus submit/reset buttons.
- **Embedded map** — An iframe embedding a Google Maps location.
- **Data table** — A styled HTML table used for structured content (e.g. programme details or schedules).

---

## Technologies Used

- **HTML5** — Page structure and semantic markup
- **CSS3** — Styling, layout (Flexbox), animations, and responsive design
- **Google Fonts** — `Montserrat` (headings) and `Nunito` (body text)
- **GitHub** — Version control and project hosting

---

## Getting Started

No installations or dependencies are required. To run the project locally:

1. Clone or download the repository to your computer.
2. Open the project folder.
3. Open `index.html` in any modern web browser (e.g. Chrome, Firefox, Edge).
4. Navigate between pages using the top navigation bar.

> **Note:** An internet connection is needed to load Google Fonts and the embedded map iframe.

---

## File Structure

```
sos-childrens-villages/
│
├── index.html          # Home page
├── about.html          # About page
├── programs.html       # Programs page
├── gallery.html        # Gallery page
├── donate.html         # Donate page
├── contact.html        # Contact page
│
├── style.css           # Shared stylesheet for all pages
│
├── IMAGES/             # All images used across the site
│   ├── logo.png
│   └── ...
│
└── README.md           # Project documentation (this file)
```

---

## Changelog

All notable changes to this project are recorded here. Entries are listed in reverse chronological order (most recent first).

---

### Part 3 – Feedback Implementation

**Date:** June 2026

#### Changes Made Based on Part 2 Feedback:

- **Added References section to README** — The README was previously missing a references section. A full list of correctly formatted references has now been added, covering all external sources used across the project.
- **Improved commit message detail** — Previous commits lacked descriptive messages. All new commits now include clear descriptions of what was changed and why (e.g. `"Fix: Added orange hover state to nav links per style guide"` instead of `"updated nav"`).
- **Expanded Changelog entries** — The changelog previously had minimal entries. All edits have now been documented with dates, descriptions, and reasons for the changes.
- **Improved README structure** — Added a Table of Contents, Pages table, File Structure section, and Getting Started instructions for completeness and clarity.
- **Reviewed and updated all page content** — Minor content corrections and layout improvements were made across HTML pages following Part 2 review.

---

### Part 2 – Styling & Layout

**Date:** May 2026

#### Changes Made:

- **Created and linked `style.css`** — A single external stylesheet was created and linked to all HTML pages to ensure consistent styling.
- **Designed hero section** — Implemented a gradient hero banner with a headline, subheading, and three call-to-action buttons (Donate, Volunteer, Sponsor).
- **Added sticky navigation header** — The `<header>` was given `position: sticky` so it remains visible on scroll.
- **Implemented responsive design** — Added CSS media queries for screen widths below 768px and 480px to support mobile and tablet layouts.
- **Styled data table** — Applied alternating row colours, hover effects, and a blue header row to improve readability.
- **Styled contact form** — Applied rounded inputs, focus states, and custom submit/reset button styles.
- **Added stats bar** — Implemented a blue statistics bar with yellow highlighted figures to showcase impact numbers.
- **Styled gallery images** — Added `border-radius`, `box-shadow`, and hover zoom transitions to all gallery images.

---

### Part 1 – Structure & Content

**Date:** April 2026

#### Changes Made:

- **Created all HTML pages** — Built six HTML pages: `index.html`, `about.html`, `programs.html`, `gallery.html`, `donate.html`, and `contact.html`.
- **Added navigation bar** — Implemented a consistent `<nav>` element across all pages with links to each section of the site.
- **Added content to each page** — Populated pages with text, images, and lists relevant to SOS Children's Villages.
- **Embedded Google Map** — Added an `<iframe>` on the contact page showing the organisation's location.
- **Added HTML table** — Created a structured table for programme or schedule information.
- **Added logo to header** — Inserted the SOS Children's Villages logo image in the `<header>` element.

---

## References

The following sources were consulted and used during the development of this project:

- SOS Children's Villages International. (2024). *About us*. Retrieved from https://www.sos-childrensvillages.org/about-us

- SOS Children's Villages South Africa. (2024). *Our work*. Retrieved from https://www.sos.org.za

- Mozilla Developer Network (MDN). (2024). *HTML elements reference*. Retrieved from https://developer.mozilla.org/en-US/docs/Web/HTML/Element

- Mozilla Developer Network (MDN). (2024). *CSS reference*. Retrieved from https://developer.mozilla.org/en-US/docs/Web/CSS/Reference

- Google Fonts. (2024). *Montserrat*. Retrieved from https://fonts.google.com/specimen/Montserrat

- Google Fonts. (2024). *Nunito*. Retrieved from https://fonts.google.com/specimen/Nunito

- W3Schools. (2024). *HTML tutorial*. Retrieved from https://www.w3schools.com/html/

- W3Schools. (2024). *CSS tutorial*. Retrieved from https://www.w3schools.com/css/

- GitHub Docs. (2024). *About READMEs*. Retrieved from https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes

- Shields.io. (2024). *Badges for GitHub README files*. Retrieved from https://shields.io
