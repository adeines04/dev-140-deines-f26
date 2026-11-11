## Milestone 3: Accessibility & Visual Design

### Accessibility Fixes
1. Added `aria-label="Main Navigation"` to the `<nav>` element on all three pages (`index.html`, `projects.html`, and `about.html`) to help screen readers identify the main navigation.
2. Checked the text and background color contrast using the WebAIM Contrast Checker. The color combination `#f0e6ff` on `#3c004d` has a contrast ratio of 13.44:1, which meets both WCAG AA and AAA requirements.
3. Added a contact form to `about.html` with properly connected `<label>` elements and input fields using matching `for` and `id` attributes.
4. Used `<fieldset>` and `<legend>` to group related form fields together and make the form easier for assistive technologies to understand.
5. Added accessibility attributes such as `aria-required="true"` and `aria-describedby` to help identify required fields and connect them to their error messages.
6. Improved keyboard navigation by adding a bright yellow focus outline (`:focus`) to interactive links and form inputs so it is easier to see which element is selected.

### Visual Design & Gestalt Principles
1. **Similarity:** Kept the project cards on `projects.html` consistent by using the same background colors, purple accent borders, padding, and typography. This helps make the cards look like they belong together.
2. **Proximity:** Kept related content grouped together within each project card and used CSS Grid with a `gap` of 16px to create space between the individual cards.
3. **Color Palette:** Used a consistent purple color theme throughout all three pages. The main colors include deep purple (`#3c004d`), darker purple for cards (`#2a0036`), lavender text (`#f0e6ff`), bright purple accents (`#a855f7`), and gold for keyboard focus (`#ffd700`).
