# MindSpace - Mental Health Awareness

**Live Demo:** [Insert Cloud Link Here]

## Project Overview

MindSpace is a responsive, accessible, single-page web application designed to raise awareness about mental health. It provides users with easy-to-digest information on recognizing stress, simple coping strategies, and immediate access to support resources. 

The application is designed with a "Calming Nature" theme, utilizing Sage Green and Slate Blue to promote a sense of tranquility (Strategy/Surface Plane).

## 5 Planes of UX Design Implementation

1.  **Strategy:** 
    *   **User Goal:** Access quick, non-judgmental information and emergency contacts.
    *   **Feature:** A "Quick Exit" button was implemented for users in sensitive situations who need to leave the site instantly.
2.  **Scope:** 
    *   Content includes signs of stress, interactive coping mechanisms, and a dedicated resource directory.
3.  **Structure:** 
    *   Information is organized logically: Hero (Reassurance) -> Signs (Identification) -> Affirmations (Support) -> Strategies (Action) -> Resources (Help).
4.  **Skeleton:** 
    *   Standard top navigation with sticky positioning allows easy movement between sections.
5.  **Surface:** 
    *   Glassmorphism (frosted glass effects) and smooth animations provide a polished, modern feel without overwhelming the user.

## Features & Accessibility (LO1 & LO2)

*   **Responsive Design:** Utilizes Bootstrap 5 Grid and Flexbox to ensure perfect rendering on mobile, tablet, and desktop.
*   **Art Direction:** Uses the HTML `<picture>` element to serve optimized images for different screen widths.
*   **Accessibility (a11y):** 
    *   Color contrast passes WCAG AA standards.
    *   Hidden "Skip to Content" link for keyboard users.
    *   Focus states are clearly visible.
    *   Semantic HTML (`<main>`, `<section>`, `<article>`) used throughout.
*   **Interactive Elements:** Native HTML `<details>` and `<summary>` elements create an accordion effect without heavy JavaScript.

## Deployment Guide (LO3)

To deploy this project:

1.  **Clone the Repo:** `git clone [repo_url]`
2.  **Verify:** Open `index.html` locally to ensure assets load.
3.  **Deploy to Netlify/Vercel/GitHub Pages:**
    *   Upload the root folder.
    *   Ensure `assets/` folder is included.
    *   The site is static, so no build command is required.

## AI Reflection (LO5)

### 5.1 & 5.2 Code Creation & Debugging
AI tools were used to generate the base structure of the Bootstrap grid system to save time on boilerplate code. Specifically, the "Signs of Stress" card layout was generated via AI prompts.
*   *Outcome:* Accelerated development time allowed for more focus on Accessibility features.
*   *Debugging:* AI was used to identify why sticky headers often obscure section titles. The AI suggested the `scroll-margin-top` CSS property, which resolved the navigation usability issue instantly.

### 5.3 Optimization & UX
AI suggested the implementation of "Glassmorphism" (`backdrop-filter`) to elevate the visual design from a standard Bootstrap template to a modern aesthetic. It also suggested the "Quick Exit" button pattern common in domestic safety web design.

### 5.4 Workflow Impact
Leveraging AI allowed the project to move from "concept" to "polished prototype" rapidly. It acted as a "Pair Programmer," handling syntax lookups (e.g., specific FontAwesome classes) and offering structural advice, which ensured the code remained clean and semantic.

## Credits
*   **Framework:** Bootstrap 5.3
*   **Icons:** FontAwesome 6
*   **Fonts:** Google Fonts (Lato & Open Sans)
*   **Images:** Unsplash (Placeholders)