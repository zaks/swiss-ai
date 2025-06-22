# Swiss AI Presentation 🇨🇭

An interactive, visually engaging presentation about AI and the future of work in Switzerland, designed for high school students.

## Features

- **Interactive Reveal.js presentation** with smooth transitions
- **P5.js animations** with floating particles and Swiss-themed visuals
- **Auto-reload functionality** for development
- **Responsive design** that works on all devices
- **Swiss-themed styling** with national colors and symbols
- **Interactive elements** including polls and animations

## Quick Start

### Option 1: Using Node.js (Recommended)
```bash
npm install
npm start
```

### Option 2: Using Python
```bash
python3 -m http.server 8000
# Then open http://localhost:8000
```

### Option 3: Direct Browser
Simply open `index.html` in your browser (some features may be limited)

## Development

- The presentation automatically reloads when files change
- Use the control buttons in the bottom-right corner:
  - 🎨 Toggle Background: Enable/disable p5.js animations
  - 🔄 Reset: Reset slide animations

## Presentation Structure

1. **Opening** - Interactive poll to engage students
2. **Plot Twist** - Surprising statistics about job creation
3. **Swiss Innovation** - Switzerland's leadership in AI
4. **Learning Paradox** - How education is changing
5. **Job Evolution** - Transformation vs. elimination
6. **Success Stories** - Swiss companies using AI
7. **Human Superpowers** - What makes humans irreplaceable
8. **Skill Building** - RPG-style character development
9. **Career Paths** - Multiple future scenarios
10. **Swiss Advantages** - Unique benefits for Swiss students
11. **Addressing Fears** - Honest discussion of concerns
12. **Action Plan** - Concrete next steps
13. **Inspiration** - Young Swiss innovators
14. **Learning Journey** - Immediate actions to take
15. **Grand Finale** - Motivational conclusion

## Key Features

### Animations
- Smooth CSS transitions and transforms
- P5.js particle system with Swiss colors
- Floating Swiss cross patterns
- Interactive mouse effects
- Slide-triggered reveal animations

### Interactivity
- Clickable poll options with visual feedback
- Progress indicator
- Keyboard navigation
- Touch/swipe support
- Responsive hover effects

### Swiss Theming
- Swiss flag colors (red, white, blue)
- Custom Swiss flag CSS elements
- Mountain silhouette backgrounds
- Cultural references and statistics
- Multilingual considerations

## Technical Details

- **Framework**: Reveal.js 4.3.1
- **Animations**: P5.js 1.4.0
- **Styling**: Custom CSS with CSS Grid and Flexbox
- **Fonts**: Helvetica Neue (Swiss typography)
- **Auto-reload**: Built-in development server watching

## Customization

### Colors
Edit the CSS variables in the `<style>` section:
```css
:root {
    --swiss-red: #DC143C;
    --swiss-blue: #003875;
    --swiss-gray: #6C7B7F;
    --accent-gold: #FFD700;
}
```

### Content
- Modify slide content directly in the HTML
- Add new slides by copying the `<section>` structure
- Update statistics and facts in the data sections

### Animations
- Adjust p5.js parameters in the script section
- Modify CSS animations in the style section
- Change transition types in Reveal.js configuration

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Tablets and desktop computers
- Minimum resolution: 1024x768

## Deployment

The presentation is a static HTML file and can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Any web server
- Local presentation setups

## License

MIT License - Feel free to adapt and use for educational purposes.

---

*Built with ❤️ for Swiss students exploring their AI future*