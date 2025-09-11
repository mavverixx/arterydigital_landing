---
trigger: manual
---

# Refactor Instructions for Frontend Project

You are helping me refactor my frontend project for a **job application**.

---

## Context

- I initially built this landing page by inserting **text screenshots from the Adobe XD design file** as `<img>` tags.  
- I now understand that in real-world development, text should be written as actual HTML (`<h1>`, `<h2>`, `<p>`, `<span>`, etc.), **not images**.  
- The hiring team said they value **clean, efficient, and well-structured code**, so I need to improve:
  - Accessibility (so screen readers can read it).  
  - SEO (so search engines can index it).  
  - Maintainability (so text can be easily updated in code).  

**Fonts:** Roboto (already imported)  
**Styling:** Tailwind CSS (already included via CDN)  

---

## What I Need From You

1. Go through my HTML and identify all `<img>` tags that currently contain **text that should instead be HTML text** (headings, subheadings, disclaimers, body text).  
2. Replace them with the appropriate **semantic HTML element** (`<h1>`, `<h2>`, `<p>`, etc.).  
3. Apply **Tailwind utility classes** to match the original design’s:
   - Font size  
   - Font weight  
   - Color  
   - Alignment  
   - Spacing / margins  
   - Responsiveness (using `sm:`, `md:`, `lg:` prefixes)  
4. Leave non-text images (logos, decorative illustrations, photos) as `<img>`, but make sure they have **descriptive alt text**.  
5. Explain your reasoning for each change.  
   - Example: “Changed this image into `<h1>` with Tailwind classes for size and weight because it is the page’s main heading.”  
6. At the end, give me a **general set of Tailwind best practices for typography** so I can continue applying them to the rest of the project on my own.  

---

## Expected Outcome

👉 With this prompt, the IDE will:

- Understand **why I’m doing this refactor**.  
- Step through my **HTML image-by-image**.  
- Convert each text-image into **semantic HTML with Tailwind styling**.  
- Teach me **how to continue the process on my own**.