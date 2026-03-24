# ABYSS — A Descent into the Deep
### Frontend Odyssey: The Interactive Web Experience Challenge
**Theme: Ocean Depths** | IIT Patna

🌊 **[Live Demo](https://frontend-odyssey-two.vercel.app)**

---

## Project Description

ABYSS is an immersive, scroll-driven storytelling experience that takes the user
on a first-person descent through all five layers of the ocean — from the sunlit
surface to the crushing silence of the Hadal Trench, 11 kilometres below.

The core design philosophy was simple: **scroll direction is the story**. As the
user scrolls down, they literally sink deeper. The depth meter ticks in real time,
the cursor transforms into a submarine torch in dark zones, and the Three.js
particle field shifts colour to reflect each zone's atmosphere — warm blues at
the surface, bioluminescent cyan in the Midnight Zone, deep violet at the Hadal.

Every section is written in second-person narrative — "You take a breath. You
dive." — placing the user inside the experience rather than reading about it.
Creature cards reveal themselves on hover with zone-accurate glow colours.
Clicking anywhere fires a sonar ping, echoing the technology real submarines use
to map the dark. A bioluminescent particle canvas fills the Midnight Zone, and
pressure distortion cracks appear as the user reaches the Hadal Trench.

Technically, the project uses vanilla HTML, CSS, and JavaScript with GSAP
ScrollTrigger for scrubbed parallax animations and Three.js WebGL for the
reactive particle field. The entire experience ships as a single optimised HTML
file with no build step required.

The ocean covers 71% of our planet. We have explored less than 5% of it.
ABYSS is an invitation to wonder what lies in the rest.

---

## Tech Stack
- HTML5, CSS3, Vanilla JavaScript
- Three.js (WebGL particle system)
- GSAP + ScrollTrigger (scroll animations)
- Deployed on Vercel

## Features
- ✅ 5 cohesive narrative sections
- ✅ GSAP scrub parallax + scroll-triggered reveals
- ✅ Sonar ping click interaction + submarine torch cursor
- ✅ Three.js bioluminescent particle field
- ✅ Live depth meter HUD
- ✅ Fully responsive (mobile, tablet, desktop)
