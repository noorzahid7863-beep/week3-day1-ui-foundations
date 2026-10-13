# Week 3 - Day 1: UI Foundations & Responsive Layout

## Overview
This repository contains the hands-on implementation for Week 3 - Day 1 of the Full-Stack Engineering Roadmap. It focuses on core semantic HTML structure, web accessibility best practices (a11y), CSS Grid/Flexbox layout mechanics, and mobile-first responsive breakpoints.

## Participant Details
* **Participant:** Noor Zahid
* **Mentor / Reviewer:** Muhammad Zeeshan
* **Module:** Week 3 – Day 1 (UI Foundations & Responsive Layout)

## Implemented Features & Technical Updates
* **Semantic HTML Structure:** Built a logical document outline using `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`.
* **Correct Heading Hierarchy:** Maintained proper heading order (`h1` -> `h2` -> `h3` -> `h4`) without skipping levels to preserve document accessibility.
* **Accessible Image Integration:** Added illustrative media with explicit, descriptive `alt` text.
* **Anchor & Button Semantics:** Removed invalid `role="button"` attributes from anchor tags (`<a>`) to distinguish navigation links from actionable buttons.
* **Focus States & Accessibility:** Implemented CSS `:focus-visible` outline styling across interactive elements for improved keyboard navigation.
* **Contact Section:** Created a dedicated `#contact` section integrated into the main document layout.
* **CSS Layout Engines:** Combined CSS Grid for multi-column feature cards and Flexbox for component alignment with mobile-first media queries (`600px` and `900px`).

## Daily Reflection & Challenges
Today's implementation highlighted two primary technical takeaways and challenges:
1. Understanding why applying `role="button"` to standard anchor tags (`<a>`) causes accessibility conflicts, as links serve navigation purposes while buttons handle inline page actions.
2. Carefully structuring the document heading levels (`h3` followed directly by `h4`) and configuring CSS `:focus-visible` pseudo-classes to ensure full keyboard navigation compliance.

## How to Run Locally
* Clone this repository:
  `git clone https://github.com/noorzahid7863-beep/week3-day1-ui-foundations.git`
* Open `index.html` in your browser or run via VS Code Live Server.