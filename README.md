# Gourmet au Catering - Service Interface Implementation

A technical frontend implementation for a professional catering service website. This project focuses on high-precision layout alignment, fixed navigation systems, and optimized form structures for desktop and mobile environments.

##  Technical Specifications

* **Architecture:** Component-based single-page architecture with localized anchor navigation.
* **Layout Engine:** Implementation of the `display: flex` model for precise distribution of content in the Menu, About, and Contact sections.
* **Typography:** Multi-stack font integration via Google Fonts, utilizing **Playfair Display** for serif headings and **Montserrat/Raleway** for functional interface text.
* **Navigation System:** A fixed top-level navigation bar (`position: fixed`) with a depth-layering strategy (`box-shadow`) for visual hierarchy during scroll events.
* **Responsive Logic:** Adaptive image handling using `object-fit: cover` and automated margin adjustments for mobile viewports.

##  Project Structure

```text
├── css/
│   ├── reset.css       # Meyer-based CSS reset to normalize cross-browser default styles
│   └── style.css       # Core stylesheet managing layout, typography, and section spacing
├── img/                # Asset directory containing optimized high-resolution food photography
└── index.htm           # Main entry point with semantic HTML5 markup

```
## Implementation Details
CSS Strategy & Layout
Global Reset: Systematic removal of browser-default padding and margins via reset.css to ensure consistent rendering across different rendering engines.

Visual Overlays: Use of large-scale background hero sections (100vh) with centralized positioning for high-impact visual entry.

Form Architecture: A clean, border-minimalist approach to the contact form, utilizing border-bottom transitions and flex-column stacking.

Fixed Positioning: The navigation bar is detached from the document flow to maintain accessibility throughout the user session.

Technical Components
Menu Grid: Structured as a balanced flex-container for menu items, ensuring consistent spacing between item descriptions and pricing.

Smooth Scrolling: Native CSS implementation (scroll-behavior: smooth) for seamless transition between internal document IDs.

Footer Logic: A standardized global footer with a distinct background layer for site-wide consistency.

## Execution & Deployment
Local Setup:

## Bash
git clone [https://github.com/FatimaGuseynova/responsive-task.git](https://github.com/FatimaGuseynova/responsive-task.git)
Launch:
Open index.htm in a modern browser. The project requires no external dependencies or pre-processors.

Internal Links:
Verify anchor functionality by interacting with the About, Menu, and Contact links in the header.

Technical frontend exercise focused on clean markup and precise CSS positioning.
