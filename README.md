# Apple iPhone 15 Pro – 3D Website Clone

This project is an interactive clone of the Apple iPhone 15 Pro website, built with React, Vite, Three.js, and TailwindCSS. It features advanced animations, 3D models, videos, and a modern, immersive user experience.

## Features

- **Interactive 3D Model:** View the iPhone 15 Pro in 3D, change its color and size.
- **GSAP Animations:** Smooth transitions and scroll-based effects.
- **Video Carousel:** Highlight product features with animated video slides.
- **Thematic Sections:** Showcase design, performance, and features.
- **Responsive Design:** Works on mobile, tablet, and desktop.
- **Modern UI:** Styled with TailwindCSS for a clean look.

## Project Structure

```
apple/
├── public/
│   ├── assets/
│   │   ├── images/
│   │   ├── videos/
│   └── models/
│       └── scene.glb
├── src/
│   ├── components/
│   ├── constants/
│   ├── utils/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md
```

## Getting Started

1. **Clone the repository**

```sh
git clone https://github.com/JanssensMaxime/apple_website.git
cd apple
```

2. **Install dependencies**

```sh
npm install
```

3. **Start the development server**

```sh
npm run dev
```

## Technologies Used

- **React 19** – UI and logic.
- **Vite** – Fast bundler.
- **Three.js & @react-three/fiber/drei** – 3D rendering.
- **GSAP** – Advanced animations.
- **TailwindCSS** – Styling and responsive design.

## Customization

- 3D models are in `public/models/scene.glb`.
- Images and videos are in `public/assets/images` and `public/assets/videos`.
- Colors and texts are configurable in [`src/constants/index.js`](src/constants/index.js).

## Credits

- 3D Model: [Polyman on Sketchfab](https://sketchfab.com/Polyman_3D) – CC-BY-4.0 License
- Technologies: React, Vite, Three.js, GSAP, TailwindCSS
