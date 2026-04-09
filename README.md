# AI Ready School — Homepage Redesign

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

A full UX audit and homepage redesign of the AI Ready School website, submitted as a design and frontend development assessment.

---

## What This Project Is

AI Ready School is India's first complete AI ecosystem for K-12 schools. Their homepage had good content but a UX layer that was working against it — too many navigation links, no warm-up path for first-time visitors, and a broken stats section that looked like the company wasn't real.

This project audits those problems, explains the thinking behind the fixes, and delivers a fully coded responsive homepage that solves them.

---

## How to Run It

No setup needed. No installs. No commands.

Just download the files, open the folder, and double-click `index.html`. It opens directly in any browser.

---

## File Structure

```
aireadyschool-redesign/
│
├── index.html    — All page sections and content
├── styles.css    — Layout, colours, typography, responsive rules
├── script.js     — Mobile menu, FAQ accordion, scroll animations
└── README.md     — This file
```

Each file does one job. Nothing is mixed together.

---

## The Audit — 6 Problems Found

I spent time on the live website across desktop and mobile before touching any code. These are the specific problems I identified and what I did about each one.

---

### Problem 1 — The navigation has too many links

The original nav had over 15 clickable items visible at once — 5 products, 3 philosophy pages, Programs, Use Cases, Resources with sub-links, Sign In, and a CTA button. A school principal landing on the site for the first time has no idea where to start. When everything is highlighted, nothing is.

**Fix:** Cut it down to 4 top-level items — Products, Why AI Ready, Stories, and FAQ — with two action buttons on the right. On mobile it collapses into a hamburger menu. Every link now has a clear purpose.

---

### Problem 2 — The hero only asks for a call with no warm-up

The hero section had one action: "Schedule a Call." That is a high-commitment ask for someone who just arrived and knows nothing about the product yet. Most visitors aren't ready to talk to a salesperson on their first visit — they want to understand the product first.

**Fix:** Added two CTAs. The primary button says "Book a Free Demo" and the secondary says "Explore Products" which scrolls down the page. Cold visitors now have a way to learn before committing.

---

### Problem 3 — Five products shown as a long scroll with no overview

Each product had its own full-height section with alternating images and text. To understand all five products, a visitor had to scroll through the entire page. Most people don't. There was also no signal for who each product is meant for — students, teachers, or the school as a whole.

**Fix:** Replaced it with a card grid where all five products are visible at once. Each card has a role tag (For Students, For Teachers, etc.), a one-line description, the key features, and a link to the original product page. Visitors understand the full ecosystem in under ten seconds.

---

### Problem 4 — The stats section showed 0% and 0+

The social proof section used a JavaScript counter animation to count up to real numbers. The animation wasn't firing, so the page was showing "Projects completed: 0+" and "Client Satisfaction: 0%." Any prospect who saw this would question whether the company was legitimate.

**Fix:** Removed the animation entirely. Hardcoded the actual numbers — 10,000+ students, 30+ tools, K–12 coverage — directly into the hero section as static text. Static numbers never break.

---

### Problem 5 — Almost all testimonials were from the same school

Eight testimonials were shown on the homepage. Six of them were from NH Goel World School in Raipur. While they were genuine, showing this pattern makes the platform look like it has one major client rather than a broad base of schools. A school admin from a different city or school type would feel unrepresented.

**Fix:** Kept three testimonials — from different roles and different schools — in a clean card layout with star ratings and initials avatars. Fewer, more diverse, more credible.

---

### Problem 6 — Mobile layout breaks in the products section

The alternating image-text layout used on desktop collapses poorly on smaller screens. Product screenshots push the actual product name and description far below the fold, so a mobile visitor sees a large image with no context of what they're even looking at.

**Fix:** On mobile, all product cards stack into a single column. The product name, tag, and description always appear first — the visual never blocks the content.

---

## Design Decisions

**Fonts:** Syne for all headings — geometric, bold, and distinctive. DM Sans for body text — clean and easy to read at small sizes. Both are free Google Fonts with no licensing issues.

**Colours:** Dark navy background on the nav and CTA sections communicates authority. An off-white background on the main content feels warmer than clinical white. A lime green accent on dark surfaces adds energy without making it look like a children's app.

**Section structure:** Every section follows the same pattern — a small uppercase label, a bold title, a one-line subtitle, then the content. This gives the page a consistent rhythm so readers always know where they are.

**No animations that could break:** Every visual element on the page works without JavaScript. The JS file only handles the mobile menu, FAQ accordion, and a subtle fade-in effect on scroll. Nothing critical depends on it.

---

## What Would Come Next

Given more time, the next priorities would be:

- An animated orbit diagram in the hero showing how the five products connect
- An interactive "which product is right for your school?" quiz
- A strip of school logos for visual social proof
- Individual product pages using the same design system
- A contact form embedded directly on the page instead of linking out

---

## Summary

The original site had a strong product and a clear vision. The UX just needed to get out of the way. This redesign does not change the message — it removes the friction so the right people can actually receive it.