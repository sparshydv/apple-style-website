# MacBook Landing Page (GSAP + React + Three.js)

An interactive MacBook-style product landing page built with React, GSAP, and React Three Fiber.  
It combines cinematic scroll animation, 3D model rendering, feature videos, and responsive layouts.

## Features

- Interactive 3D MacBook viewer with model variants
- Scroll-driven section transitions powered by GSAP + ScrollTrigger
- Video-led storytelling for hero and feature highlights
- Responsive UI for mobile and desktop
- Zustand-based state management for model/view interactions

## Tech Stack

- React 19
- Vite 7
- GSAP + @gsap/react
- Three.js + @react-three/fiber + @react-three/drei
- Tailwind CSS 4
- Zustand
- ESLint 9

## Prerequisites

- Node.js 18+
- npm 9+

## Local Development

1. Install dependencies:

```bash
npm install
```

2. Start development server:

```bash
npm run dev
```

3. Open the local URL printed by Vite (usually http://localhost:5173).

## Available Scripts

```bash
npm run dev      # Start Vite dev server
npm run build    # Create production build
npm run preview  # Preview production build locally
npm run lint     # Run ESLint
```

## Project Structure

```text
.
|- public/
|  |- fonts/
|  |- models/
|  |- videos/
|- src/
|  |- components/
|  |  |- models/
|  |  |- three/
|  |- constants/
|  |- store/
|  |- App.jsx
|  |- index.css
|  |- main.jsx
|- index.html
|- package.json
|- vite.config.js
```

## Customization Notes

- Update section content and labels in `src/constants/index.js`.
- Main page composition is defined in `src/App.jsx`.
- Replace media in `public/videos` and `public/models` to reskin the experience.
- Adjust global styling and utility layers in `src/index.css`.

## Build for Production

```bash
npm run build
```

The optimized output is generated in the `dist` folder.

## Credits

Inspired by Apple-style product storytelling and modern 3D web interfaces.
