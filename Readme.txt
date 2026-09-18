# Green Future Initiative Website - Part 2

## Changelog

### Part 2 Updates (Current)
*   **Implemented External CSS:** Created `style.css` to separate styling from HTML structure.
*   **Desktop Styling:** Applied a card-based layout using CSS Grid and Flexbox for the homepage stats and project sections.
*   **Typography:** Integrated Google Fonts 'Montserrat' for headings and 'Open Sans' for body text as per the design proposal.
*   **Color Scheme:** Applied the defined color palette (Forest Green, Light Green, Cream White, Amber Gold) using CSS Variables.
*   **Responsive Design:** Added media queries to ensure the website is fully functional on mobile devices (stacking navigation and grid items).
*   **Navigation:** Created a sticky navigation bar that persists across all 6 pages.

### Part 1 Feedback Edits
*(Note: Since I cannot see your specific Part 1 feedback, here is a placeholder. You must edit this based on your actual marks. If you received no feedback, state "No changes required based on Part 1 feedback.")*
*   **Feedback:** "Ensure all images have alt text."
*   **Action:** Added descriptive `alt` attributes to all image tags.
*   **Feedback:** "Reference list formatting was inconsistent."
*   **Action:** Corrected the reference list in the proposal to strictly follow IIE Harvard style.

## References
Green Future Initiative. 2023. Annual Report 2023. [Online]. Available at: https://www.greenfuture.org.za/report2023 [Accessed 10 August 2026].
Siewierski, C. 2015. An Introduction to Scholarship: Building Academic Skills for Tertiary Study. Cape Town: Oxford University Press Southern Africa.
The Independent Institute of Education. 2024. IIE Harvard Style Reference Guide – Adapted for The IIE 2024. [Online]. Available at: https://www.iie.ac.za [Accessed 10 August 2026].
UN Environment Programme. 2023. Urban Greening Guidelines. Nairobi: UNEP.
Navigation Fixes
Fixed broken navigation links across all pages. Every navigation item (Home, About, Projects, Get Involved, Donate, Contact) now correctly points to its corresponding .html file.

Standardised the header on every page so the navigation menu is identical throughout the site, allowing users to switch seamlessly between pages.

Corrected inconsistent file references — previously, some links pointed to non-existent or misnamed files, causing 404 errors. All links now resolve properly.

Styling & Design Overhaul
Introduced a unified, professional design system using CSS custom properties (variables) for colours, fonts, spacing, and shadows. This makes the site consistent and easy to maintain.

Applied a cohesive green colour palette (--primary-green, --secondary-green, --accent-lime) that reflects the environmental mission of the organisation.

Added Google Fonts (Montserrat for headings, Open Sans for body text) to give the site a modern, polished look.

Created reusable UI components, including:

Card-style .stat-item blocks with hover lift effects

Rounded .cta-button elements with smooth hover transitions

A sticky header that stays visible while scrolling

Improved the hero section on the Home page with a soft gradient background and centred call-to-action buttons.

Responsive Design
Made every page fully responsive using CSS Grid, Flexbox, and media queries.

Layouts adapt cleanly across desktop, tablet, and mobile screen sizes.

Navigation wraps gracefully on smaller screens, and font sizes scale down for readability.

Page-Specific Improvements
Home — Refined hero section, impact statistics grid, and side-by-side CTA buttons (Donate Now + Volunteer).

About — Clean three-pillar layout (Urban Greening, Environmental Education, Sustainable Living).

Projects — Card grid showcasing Community Gardens, Education Programs, and Recycling Initiatives.

Get Involved — Styled volunteer CTA and a clean, icon-enhanced upcoming events list.

Donate — Centred donation card with a prominent call-to-action button.

Contact — Professional contact info cards plus a fully styled contact form with focus states.

Accessibility & UX
Added required attributes to form fields on the Contact page.

Improved colour contrast between text and backgrounds.

Ensured interactive elements (buttons, links) have clear hover and focus states.

Used semantic HTML structure (<header>, <main>, <footer>, <nav>, <section>).

Code Quality
Removed duplicate and conflicting inline styles.

Consolidated all styling into each page's <style> block using consistent rules.

Added clear section comments in the HTML for easier future editing.
Added a professional environmental image on my home/index page.