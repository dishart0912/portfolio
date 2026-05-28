=================================================
  DISHA TAKAWALE — PORTFOLIO
  File Structure & How To Use
=================================================

FOLDER STRUCTURE:
─────────────────
my-portfolio/
│
├── index.html                  ← Main portfolio page
│
├── projects/
│   ├── nivara.html             ← Nivara case study
│   ├── trendsphere.html        ← TrendSphere case study
│   ├── payment.html            ← Payment Flow case study
│   ├── fokus.html              ← Fokus Landing Page case study
│   ├── donut.html              ← Donut Animation case study
│   └── food.html               ← Food App case study
│
└── assets/
    ├── images/
    │   ├── nivara-cover.jpg        ← Cover image for Nivara card & case study
    │   ├── nivara-screen-1.jpg     ← Screenshot 1
    │   ├── nivara-screen-2.jpg     ← Screenshot 2
    │   ├── nivara-screen-3.jpg     ← Screenshot 3
    │   │
    │   ├── trendsphere-cover.jpg
    │   ├── trendsphere-screen-1.jpg
    │   ├── trendsphere-screen-2.jpg
    │   ├── trendsphere-screen-3.jpg
    │   │
    │   ├── payment-cover.jpg
    │   ├── payment-screen-1.jpg
    │   ├── payment-screen-2.jpg
    │   ├── payment-screen-3.jpg
    │   │
    │   ├── fokus-cover.jpg         ← (or use fokus-cover.mp4 in /videos)
    │   ├── fokus-screen-1.jpg
    │   ├── fokus-screen-2.jpg
    │   │
    │   ├── donut-cover.jpg         ← (or use donut-cover.mp4 in /videos)
    │   ├── donut-screen-1.jpg
    │   ├── donut-screen-2.jpg
    │   │
    │   ├── food-cover.jpg
    │   ├── food-screen-1.jpg
    │   ├── food-screen-2.jpg
    │   └── food-screen-3.jpg
    │
    ├── videos/
    │   ├── trendsphere-demo.mp4    ← Prototype video
    │   ├── payment-demo.mp4
    │   ├── fokus-cover.mp4         ← Cover video
    │   ├── fokus-demo.mp4
    │   ├── donut-cover.mp4
    │   └── donut-demo.mp4
    │
    └── resume/
        └── disha-takawale-resume.pdf

HOW TO ADD YOUR IMAGES:
────────────────────────
In each projects/*.html file, find the placeholder-box divs and 
replace them with your actual <img> or <video> tags.

The comments inside each file tell you exactly what to do:

  <!-- TO ADD YOUR IMAGE: replace the placeholder-box div above with:
  <img src="../assets/images/nivara-screen-1.jpg" alt="Nivara screen 1"> -->

HOW TO ADD YOUR VIDEOS:
────────────────────────
  <!-- TO ADD YOUR VIDEO: replace the placeholder-box div above with:
  <video controls autoplay muted loop>
    <source src="../assets/videos/donut-demo.mp4" type="video/mp4">
  </video> -->

HOW TO UPDATE COVER IMAGES ON INDEX.HTML:
──────────────────────────────────────────
In index.html, each project card has a comment:
  <!-- REPLACE src with: assets/images/nivara-cover.jpg -->
Just swap the src attribute of that <img> tag.

HOSTING:
─────────
Open index.html in any browser to preview locally.
For hosting: upload everything to GitHub Pages or drag folder to Netlify.
