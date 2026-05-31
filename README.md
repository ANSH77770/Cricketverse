# Cricketverse

Cricketverse is an animated IPL-themed React website built with Vite. It presents a cinematic IPL 2026 experience with a video hero, scroll-based storytelling, IPL champion history, final result details, team showcase sections, and animated cricket visuals.

## Features

- Cinematic landing page for TATA IPL 2026
- Video-based hero section
- Smooth scroll animations using GSAP
- Interactive IPL trophy history section
- IPL final prediction/result panel
- GT vs RCB team showcase
- Head-to-head stats section
- Responsive React frontend powered by Vite

## Tech Stack

- React
- Vite
- GSAP
- JavaScript
- CSS

## Project Structure

```text
Cricketverse/
└── ipl_project/
    ├── public/
    │   ├── favicon.svg
    │   ├── icons.svg
    │   └── video/
    │       └── one.mp4
    ├── src/
    │   ├── assets/
    │   ├── components/
    │   │   ├── Hero.jsx
    │   │   └── Hero.css
    │   ├── App.jsx
    │   └── main.jsx
    ├── package.json
    └── vite.config.js
```

## Getting Started

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/ANSH77770/Cricketverse.git
```

### 2. Open the Project Folder

```bash
cd Cricketverse/ipl_project
```

Important: `package.json` is inside the `ipl_project` folder, so npm commands must be run from there.

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Development Server

```bash
npm run dev
```

Then open the local URL shown in the terminal, usually:

```text
http://localhost:5173
```

## Available Scripts

```bash
npm run dev
```

Starts the development server.

```bash
npm run build
```

Creates a production build.

```bash
npm run preview
```

Previews the production build locally.

```bash
npm run lint
```

Runs ESLint checks.

## How to Run in VS Code

1. Open VS Code.
2. Go to **File > Open Folder**.
3. Select:

```text
Cricketverse/ipl_project
```

4. Open the VS Code terminal.
5. Run:

```bash
npm install
npm run dev
```

## Deployment

You can deploy this Vite project on platforms like Vercel, Netlify, or GitHub Pages.

Before deploying, create a production build:

```bash
npm run build
```

The build output will be generated in the `dist` folder.

## Author

Created by [ANSH77770](https://github.com/ANSH77770)

## License

This project is open source and available for learning and portfolio use.
