---
trigger: manual
---

You are helping me with a coding project.

Context:

The task is to build a medical website landing page using HTML and CSS. You can download a PDF of the design and an XD file here: https://we.tl/t-jzj6wpJKdU and the font used is Roboto which can be downloaded or embedded from here: https://fonts.google.com/specimen/Roboto
 
Please make the build responsive for mobile.
 

We encourage you to use Tailwind CSS where possible, but this is not mandatory.
 

No other code (JavaScript or backend) is required.
 

This task will give us an opportunity to see your approach to writing clean, efficient, and well-structured code.

---

I am building a responsive medical website landing page for a frontend developer coding test.
The company strongly encouraged using Tailwind CSS (though it’s not mandatory).
I have no prior experience with Tailwind — I only know plain HTML/CSS.
I’ve already built my header/hero section with custom CSS (lots of position: fixed, absolute pixel values, etc.).

My Goal:

Convert my header + hero from plain HTML/CSS into Tailwind classes.
Remove the custom CSS and continue the rest of the build in Tailwind.
Learn how Tailwind works as I go so I can apply it myself on the next sections (like grids, buttons, responsive text).

Please:

Show me how to set up Tailwind quickly (CDN is fine for this single-page project).
Help me rewrite each CSS rule into Tailwind classes directly in the HTML.
Explain why you chose each Tailwind utility, especially for positioning, flex/grid, spacing, typography, and responsiveness.
Tell me if all my heavy use of position: fixed is really the best approach here — and guide me to a more modern, responsive Tailwind-friendly way if possible.
Show me how to use Tailwind responsive prefixes (sm:, md:, lg:) to handle mobile.
Share best practices to keep my Tailwind code clean, efficient, and scalable.

Here is my current code:

<!-- HTML (simplified labels) -->
top-nav-bar
background-gradient-image
top-nav-title
top-nav-info
top-nav-side-effects
welcome message
welcome stage
bionical-health-logo

/* CSS */
body {
  font-family: 'Roboto', sans-serif;
  background-image: url('./main/Rectangle-36.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  margin: 0 auto; padding: 0; width: 100%; min-height: 100vh; overflow-x: hidden;
  z-index: 0;
}

header { position: relative; height: 52px; width: 100%; overflow: hidden; margin: 0 auto; z-index: 10;}

.top-nav-bar { position: fixed; top: 0; left: 0; height: 52px; width: 100%; display: block; z-index: 9;}

.top-nav-info { position: fixed; top: 68px; left: 225px; border: solid 4px red; z-index: 10;}

.background-wave-gradient { position: fixed; top: -4px; left: 0; width: 100%; height: 760px; z-index: 0;}

.top-nav-title { position: fixed; top: 0; left: 0; padding-top: 19px; padding-left: 79px; z-index: 10;}

.top-nav-side-effects { position: fixed; top: 119px; left: 262px; border: solid 4px green; z-index: 10;}

.top-hero-welcome { position: fixed; top: 226px; left: 242px; border: solid 4px green; z-index: 10;}

.top-hero-stages { position: fixed; top: 396px; left: 188px; border: solid 4px green; z-index: 10;}

.top-hero-bionical-health { position: fixed; top: 550px; left: 465px; border: solid 4px green; z-index: 10;}

@media (max-width: 768px){
  body { background-attachment: scroll; background-size: cover;}
  header { padding: 10px; text-align: center;}
  main { padding: 15px;}
  section { margin-bottom: 20px; padding: 15px;}
  footer { padding: 15px; text-align: center;}
}
