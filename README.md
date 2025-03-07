# ComicWala

## Overview
ComicWala is a visually engaging and responsive website that integrates **Gradio** for an interactive AI-powered comic generation system. The website leverages **LLMs (Large Language Models)** to generate comic scripts based on user prompts and **Stable Diffusion** to create comic-style images based on the generated stories.

Additionally, ComicWala uses LocomotiveJS, GSAP for animations across the website and it can be used on **mobile phones** as well.

## Features
- **Smooth Scrolling** with Locomotive Scroll
- **GSAP Animations** for fade-ins, parallax effects, and button interactions
- **Dynamic Page Transitions** with ScrollTrigger
- **AI-Powered Comic Generation** using Gradio
- **Stable Diffusion for Image Creation** based on LLM-generated stories
- **Responsive and Interactive Elements**

## Technologies Used
- **HTML5**
- **CSS3**
- **JavaScript (GSAP + Locomotive Scroll)**
- **Gradio** (UI for using LLM models)
- Tinyllama and Phi2 (LLM models)
- **Stable Diffusion** (for AI-generated comic images)

## Dependencies
Make sure to include the following in your HTML file:
```html
<!-- Locomotive Scroll -->
<script src="https://cdn.jsdelivr.net/npm/locomotive-scroll@3.5.4/dist/locomotive-scroll.js"></script>

<!-- GSAP & ScrollTrigger -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.11.5/gsap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.11.5/ScrollTrigger.min.js"></script>
```

## Usage
1. Open the website and scroll to experience smooth animations.
2. Click on **Phi2** or **Tinyllama** and hence enter a prompt to generate an AI-powered comic.
3. Choose the number of panels to be generated as well as the type of images you want. Eg.: Anime, Classic, Noir etc.
4. The **LLM** will generate a comic script, and **Stable Diffusion** will create corresponding images.
5. Enjoy the AI-powered comic generation feature!

## License
This project is licensed under the MIT License.

---
Made with ❤️ by **ChaiFi** - 2025
