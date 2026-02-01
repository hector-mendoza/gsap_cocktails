# 🍹 Mojito Cocktails

A modern, animated cocktail landing page built with React, GSAP, and Tailwind CSS. Features smooth scroll animations, video scrubbing effects, and an interactive cocktail menu carousel.

## ✨ Features

- **Smooth GSAP Animations**: Text reveals, parallax effects, and scroll-triggered animations
- **Video Scroll Scrubbing**: Video playback synced with scroll position
- **Responsive Design**: Mobile-friendly with custom hooks for responsive behavior
- **Interactive Menu**: Navigate through cocktails with tab buttons and arrow controls
- **Modern Stack**: React 19, Vite, Tailwind CSS 4, and GSAP 3

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- pnpm (or npm/yarn)

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd gsap_cocktails
```

2. Install dependencies:
```bash
pnpm install
```

3. Start the development server:
```bash
pnpm dev
```

4. Open your browser and visit `http://localhost:5173`

## 📦 Available Scripts

- `pnpm dev` - Start the development server
- `pnpm build` - Build for production
- `pnpm preview` - Preview the production build locally
- `pnpm lint` - Run ESLint to check code quality

## 🛠️ Tech Stack

- **React 19** - UI library
- **Vite** - Build tool and dev server
- **GSAP 3** - Animation library with ScrollTrigger and SplitText plugins
- **Tailwind CSS 4** - Utility-first CSS framework
- **react-responsive** - Media query hooks for React

## 📁 Project Structure

```
gsap_cocktails/
├── src/
│   ├── components/
│   │   ├── Hero.jsx        # Hero section with animated text
│   │   ├── Navbar.jsx      # Navigation bar
│   │   ├── Cocktails.jsx   # Cocktails grid section
│   │   ├── Menu.jsx        # Interactive menu carousel
│   │   ├── About.jsx       # About section
│   │   └── Art.jsx         # Art gallery section
│   ├── hooks/
│   │   └── hooks.jsx       # Custom React hooks
│   ├── App.jsx             # Main app component
│   ├── main.jsx            # App entry point
│   └── index.css           # Global styles
├── constants/
│   └── index.js            # App constants and data
├── public/
│   ├── fonts/              # Font files
│   ├── images/             # Image assets
│   └── videos/             # Video files
└── index.html              # HTML template
```

## 🎨 Key Components

### Hero Section
Features animated title text with gradient effects, parallax leaf images, and scroll-triggered video scrubbing that syncs video playback with scroll position.

### Menu Component
Interactive cocktail carousel with navigation tabs and arrow controls. Uses modular arithmetic to create infinite loop navigation.

### Custom Hooks
- `useIsMobile()` - Detects mobile viewport (max-width: 767px)

## 🎯 GSAP Animations

The project uses several GSAP animation techniques:
- **SplitText** - Character and word-level text animations
- **ScrollTrigger** - Scroll-based animation triggers
- **Timeline** - Sequenced and synchronized animations
- **Video Scrubbing** - Frame-accurate video control based on scroll

## 📝 License

This project is for educational and portfolio purposes.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
