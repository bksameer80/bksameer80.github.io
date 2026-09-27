# Nexis Digital - Agency Landing Page

A responsive landing page built completely from scratch using pure HTML5 and CSS3 for my internship task.

## What I Built
I created an 11-section agency landing page called **Nexis Digital**. It includes:
1. **Header & Navbar:** Fixed top navigation with smooth scroll links and a CTA button.
2. **Hero Section:** Introduction with headlines, two action buttons, and an image.
3. **About Us:** Short company story along with 4 key company stats (years, projects, clients, team).
4. **Services:** 4 service cards with custom icons, descriptions, and read more links.
5. **Why Choose Us:** 4 clear reasons why clients should work with the agency.
6. **Portfolio:** 3 project cards showcasing past work with categories and images.
7. **Pricing:** 3 pricing plans (Basic, Professional, Enterprise) using clean lists for features.
8. **Testimonials:** 3 customer reviews with client photos, job titles, and star ratings.
9. **FAQ:** 5 frequently asked questions that users can click to open and close.
10. **Contact Form:** Full form with validation (name, email, phone, dropdown service select, message, consent checkbox) plus company contact details.
11. **Footer:** Quick links, services list, social links, and copyright info.

## Technologies Used
- **HTML5:** Semantic tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<blockquote>`, `<details>`, `<footer>`) and accessible form inputs.
- **CSS3:** Flexbox, CSS Grid, CSS variables, and media queries for responsiveness. No external CSS frameworks were used.
- **Git & GitHub:** For version control and tracking my progress with commits.

## Assumptions I Made
- Used Unsplash images for placeholders (team, projects, and client avatars).
- The contact form uses standard HTML5 client-side validation (`required`, `type="email"`, etc.) and is ready to connect to a backend handler or form service.
- The design targets modern web browsers that support CSS Grid and Flexbox.

## Additional Features Added
- **No-JS FAQ Accordion:** Used native HTML5 `<details>` and `<summary>` tags so questions expand and collapse without needing JavaScript.
- **Smooth Scrolling:** Added `scroll-behavior: smooth` so clicking navbar links smoothly glides to the section instead of jumping instantly.
- **Card Hover Effects:** Added slight lift animations (`translateY`) and shadows on hover to make cards feel interactive.
- **Accessibility Details:** Added descriptive `alt` texts for images, explicit `for` attributes linking form labels to inputs, and `aria-label` for star ratings so screen readers can read them properly.