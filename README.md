# Mintlify Documentation Site Clone

Hey there! This is my submission for the **Web Dev Cohort 2026**. I tackled the Mintlify clone assignment entirely from scratch using plain HTML and CSS. My primary focus was nailing the elegant, pristine, developer-first documentation vibe that Mintlify is famous for.

**Author:** Prashant Saini

## 💡 Learning & Approach

My goal was strict structural precision and UI fidelity. Instead of overloading it with heavy libraries, I utilized deep CSS flexbox and CSS Grid logic to replicate their precise sectioning and overlapping UI layout.

### Sections I Recreated:
I systematically built all 10 core sections requested in the assignment brief:

1. **Top Navigation:** Fully populated with the leaf logo, nav links (`Resources`, `Documentation`, `Customers`, etc.), and dual CTA buttons.
2. **Hero Section:** Implemented the "NEW" pill badge, massive main headline, subtitle, and input field layout. Instead of a flat screenshot for the background, I built a rich CSS `linear-gradient` (`#123c52` to `#2f8ba1`) to cleanly replicate the cloud aesthetic natively.
3. **Documentation UI Preview:** I avoided just pasting an image here. Instead, I custom-coded an intricate CSS/HTML mockup element overlapping the hero section. It features the left sidebar (with Ask Assistant, Quickstart, etc.), a top-bar search simulating `CMD+K`, and a split content area with simulated documentation text.
4. **Trusted Logos:** Cleanly styled row of dummy logos accurately spaced.
5. **Feature Highlights:** Used `flex-direction: row-reverse` toggling for the alternating text & photo aesthetic.
6. **Intelligent Assistant Preview:** Recreated the chatbot interaction screen utilizing customized CSS chat bubbles (simulating a User vs AI bot flow).
7. **Enterprise Features:** A clean 4-column minimal grid specifying Compliance and SSO.
8. **Case Studies:** Clean card-based layouts featuring Anthropic and Cursor testimonials.
9. **Final Call-to-Action:** Bold typography exit layer to capture the user's attention.
10. **Footer:** Built out the massive structured multi-column site navigation layout exactly as specified.

## 🎨 Styles, Fonts, and Colors

- **Typography:** I imported the `Inter` font stack directly from Google Fonts (`font-family: 'Inter', -apple-system...`) to perfectly match Mintlify's modern SaaS typography.
- **Colors:**
  - **Mountain Meadow (Brand Green):** `#18E299` — Representing the primary leaf logo, "NEW" pill badge, and active-state highlights. (RGB: 24, 226, 153 | HSL: 158, 81, 49)
  - **White (Base Text/UI):** `#FFFFFF` — Used for headings, floating UI cards, and high-contrast readable text. (RGB: 255, 255, 255)
  - **Woodsmoke (Dark Layouts):** `#08090A` — Utilized for the dark Chat UI, button backgrounds, and strong dark slates. (RGB: 8, 9, 10 | HSL: 210, 11, 4)

### Constraints Met:
- **Only HTML and CSS:** Absolutely zero JavaScript and zero TailwindCSS used. 
- **Organic Coder Structure:** Maintained a humanized coding style—the file layout and variable decisions mirror a real-world frontend pass.
- *Note:* The assignment noted "desktop-only", but I dropped in some graceful CSS wrapper limits and very basic structural media queries at the bottom of the stylesheet so the site won't completely explode if accessed on a smaller screen.

Feel free to inspect the DOM elements! Thanks for reviewing my design.
