# System Patterns: X-mas Shop

## 1. System Architecture
The project follows a simple static site architecture. All content is served from a single `index.html` file, which will likely link to CSS and JavaScript files. There is no backend or server-side logic.

## 2. Key Technical Decisions
- **Single-Page Application (SPA):** All content is on one page to keep the user experience simple and focused.
- **Static Assets:** Images for products are stored locally (`.jpg`, `.png` files).

## 3. Design Patterns
- **Component-Based Structure (Conceptual):** Although not using a framework, the HTML can be structured into logical components like a header, product grid, and footer.
- **Separation of Concerns:** HTML for structure, CSS for presentation, and JavaScript for behavior will be kept in separate files (or at least separate sections in the HTML) for maintainability.
