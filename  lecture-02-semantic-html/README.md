# Lecture 02 – Semantic HTML & Structure

## 1. What I implemented this lecture
- Built a personal portfolio page using semantic HTML, including `<header>`, `<nav>`, `<main>`, and `<footer>`.
- Created separate sections for About, Works, and Interests to organize my content clearly.
- Added a contact area in the footer with email, GitHub, LinkedIn, and Instagram links using icon images.

## 2. Semantic decisions I made (REQUIRED)

Explain at least **three semantic choices** you made in your HTML.

### Decision 1
- Element(s) used: `<header>`, `<nav>`, and `<main>`
- Where in the page: At the top of the HTML document, wrapping the site title, navigation, and main content.
- Why this element is semantically correct: `<header>` groups the page title and intro text, `<nav>` holds the main navigation links, and `<main>` marks where the main content of the page begins.

### Decision 2
- Element(s) used: `<section>` with `<h2>` headings
- Where in the page: Around the About, Works, and Interests parts inside `<main>`.
- Why this element is semantically correct: Each `<section>` represents a clear topic on the page. Using `<h2>` for the section titles creates a simple outline that is easy to read.

### Decision 3
- Element(s) used: `<article>`, `<figure>`, and `<figcaption>`
- Where in the page: Inside the Works section, wrapping each individual project and its image.
- Why this element is semantically correct: Each `<article>` is one complete project. `<figure>` keeps the project image together with its description, and `<figcaption>` gives a short text explanation of the image.

*(Example: Why `<section>` instead of `<div>`, why `<article>` here, why this heading level, etc.)*

---

## 3. Accessibility considerations
- What accessibility features did you include?
  - I added `alt` text to images and icons.
  - I used a short, clear title on the embedded YouTube video.
  - I kept a simple and logical heading order.
- How do they improve usability?
  - `alt` text helps people who cannot see the images understand what they show.
  - The video title makes it clear what the video is about.
  - A clear heading structure makes the page easier to scan and read.

---

## 4. What I learned
- How to structure a page with semantic elements instead of only using `<div>`.
- How to group related content into sections and articles so the page feels organized.
- How simple accessibility features like `alt` text and headings can help more people use the page.

## 5. What I still need to improve
- I need to practice making the layout responsive with CSS so it looks good on all screen sizes.
- I want to learn more about designing with color contrast in mind.
- I should test my pages more with only the keyboard to make sure everything is easy to reach.

## 6. Notes about AI usage (if any)
- Tool used: GitHub Copilot (GPT-5.1)
- What I accepted as-is: I accepted help generating some of the semantic HTML structure (like sections, nav, and footer links) and refine the English I use in this README text.
- What I modified manually: I added some of the HTML structure, adjusted the content (text, links, and interests) so it matches my own background and preferences, and I checked that the final HTML meets the lecture requirements.