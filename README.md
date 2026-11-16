# CSS Button Animation

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/css-button-animation-lab/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

Standalone responsive project reconstructed from the supplied screen recording.

## Five hover effects
1. Fill Slide — color slides across the button
2. Pulse Glow — continuous purple neon glow
3. Border Draw — animated double border
4. 3D Pop — raised button with press depth
5. Rotate Loop — play triangle rotates continuously

Each effect has its own preview button and CSS snippet panel. Hover or tap the buttons to preview the effects.

## Run
Open `index.html` in a modern browser, or run:
```bash
python3 -m http.server 8000
```
Visit http://localhost:8000.

## Source-derived details
The video identifies the five effects as Fill Slide, Pulse Glow, Border Draw, 3D Pop and Rotate Loop. Readable declarations include:
- Fill: `background: #00d9ff`, `transform: translateX(-105%)`, `transition: transform .45s ease`
- Pulse: `animation: pulseGlow 1s infinite`, purple `rgba(192,132,252,...)` glow
- Border: `border: 2px solid #fb7185`, `clip-path: inset(...)`, `.5s ease`
- 3D Pop: dark linear gradient and layered box shadows; hover `translateY(-5px) scale(1.04)`
- Rotate: `animation: rotateTriangle .8s linear infinite`, keyframe `rotate(360deg)`

The recording is a screen capture of the UI/code panels, not the original project repository. This runnable version preserves visible labels and readable code values and reconstructs any obscured or incomplete declarations needed for working effects. No external libraries are required.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
