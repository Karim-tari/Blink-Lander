# Blink Landing Page

A modern, animated landing page for Blink - AI Shopping platform.

## Features

- 🎬 Beautiful Lottie preloader animation
- ✨ Coordinated intro animations (navigation, headlines, text, forms)
- 🎵 Interactive audio description with text highlighting
- 📱 Fully responsive design
- 🖼️ Cycling product images with mask reveal effects
- 📊 Live waitlist counter animation

## Fonts

This project uses custom fonts that are included in the repository:
- **FBS-Machro-Regular.otf** - Custom headline font
- **Noto Sans** family - Body text fonts (Regular, Medium, SemiBold, Bold)

All fonts are properly configured with fallbacks for maximum compatibility.

## Deployment

### GitHub Pages Setup

1. Go to your repository settings
2. Navigate to "Pages" section
3. Select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Your site will be available at: `https://karim-tari.github.io/Blink-Lander/`

### Files Structure

```
├── index.html              # Main HTML file
├── styles.css              # All styles and animations
├── FBS-Machro-Regular.otf   # Custom headline font
├── noto/                   # Noto Sans font family
│   ├── NotoSans-Regular.ttf
│   ├── NotoSans-Medium.ttf
│   ├── NotoSans-SemiBold.ttf
│   └── NotoSans-Bold.ttf
├── supporting image.png     # Product images
├── supporting image-2.png
├── supporting image-3.png
├── video-bg.mp4            # Background video
├── logo.svg                # Logo files
├── logo-icon.svg
└── ElevenLabs_*.mp3        # Audio description
```

## Browser Compatibility

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- Mobile browsers: Optimized responsive design

## Performance

- Fonts load with `font-display: swap` for better performance
- Preloader ensures smooth animation timing
- Optimized asset loading
