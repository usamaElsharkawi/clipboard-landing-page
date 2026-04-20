# Clipboard Landing Page - Tailwind CSS v4 Oxide

A professional, high-performance landing page built as part of the **"Tailwind CSS From Scratch"** curriculum by Brad Traversy. 

### 🎓 Pedagogical Goal
While the original course uses **Tailwind v3**, this project serves as a "Translation Lab" where we implement all concepts using **Tailwind CSS v4 (Oxide Engine)**, mastering the architectural shift toward a CSS-First, variable-driven future.

## 🚀 Tailwind v4 Learnings (The Oxide Shift)

### 1. Unified Environment
- **Single Entry Point:** Transitioned from multi-line `@tailwind` directives to the unified `@import "tailwindcss";`.
- **CSS-First Config:** Abandoned the `tailwind.config.js` approach. All project tokens (colors, breakpoints, fonts) are now managed directly in the CSS file using the `@theme` block.

### 2. Native Registry Mapping
- **Background Image Magic:** Mastered the v4 naming convention where naming a variable `--background-image-xxxx` automatically generates the `bg-xxxx` utility class.
- **Variable-Driven Media Queries:** Learned that while standard CSS media queries cannot use variables, Tailwind v4 handles the translation perfectly when using responsive prefixes (`md:`, `lg:`) in the HTML.

### 3. Progressive Extraction Strategy
- **Utility-First Supremacy:** Prioritized HTML-based utilities for flexible styling.
- **Hybrid Component Extraction:** Leveraged Native CSS combined with **Theme Variables** (`var(--breakpoint-lg)`) for core layout containers, moving away from the "Legacy" `@apply` pattern.

---

## ⚡ Architectural Deep Dive: Outside-In Construction

In this project, we implement the **Architect's Mental Model** for building interfaces:

1.  **The Invisible Cage (The Wrapper):** Using `section-container` to enforce readabilty limits and horizontal centering across all viewports.
2.  **The Rhythm (Spacial Balance):** Prioritizing "Oxygenated" design with significant vertical margins (`mb-40`) to separate distinct psychological phases of the user journey.
3.  **The SEO Anchor:** Ensuring proper document hierarchy by utilizing a single `<h1>` for the Hero headline, anchoring the search engine's understanding of the site's primary purpose.
4.  **The Micro-Interaction Loop:** Adding feedback layers like `active:scale-95` to buttons to transform "links" into "interactive objects."

---

## 🎨 Design Tokens

- **Strong Cyan:** `hsl(171, 66%, 44%)` (Primary Action)
- **Light Blue:** `hsl(233, 100%, 69%)` (Secondary Action)
- **Primary Font:** Bai Jamjuree (Modern Sans-Serif)

---


