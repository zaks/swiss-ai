# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an interactive HTML presentation about AI and the future of work in Switzerland, designed for high school students. The project creates an engaging, visually rich presentation using Reveal.js with custom animations and Swiss-themed styling.

## Development Commands

### Starting the Development Server
```bash
npm start           # Primary development command - starts live-server on port 3000
npm run dev         # Alternative development command with file watching
```

### Alternative Serving Methods
```bash
npm run serve       # Python-based server on port 8000
python3 -m http.server 8000  # Direct Python server command
```

### Build and Deploy
```bash
npm run build       # No build step - outputs confirmation message
npm run deploy      # Outputs deployment readiness message
```

## Architecture and Structure

### Core Technologies
- **Reveal.js 4.3.1**: Primary presentation framework providing slide transitions and navigation
- **P5.js 1.4.0**: Animation library creating floating particles and interactive Swiss-themed visuals
- **Custom CSS**: Extensive styling with Swiss color scheme and responsive design
- **Vanilla JavaScript**: Custom interactivity and animation control

### File Structure
- `index.html` - Single-file application containing all presentation content, styles, and scripts
- `package.json` - Development dependencies and scripts configuration
- `imgs/` - Image assets including Swiss-themed graphics
- `README.md` - Comprehensive project documentation

### Key Design Patterns

#### Swiss Visual Identity
- Color scheme uses Swiss national colors (`--swiss-red: #DC143C`, `--swiss-blue: #003875`, `--accent-gold: #FFD700`)
- Custom CSS Swiss flag elements created with pseudo-elements
- Mountain silhouette backgrounds using SVG data URIs
- Typography follows Swiss design principles (Helvetica Neue)

#### Animation System
- CSS-based transitions with staggered reveal animations
- P5.js particle system with Swiss color palette
- Interactive poll elements with hover and click effects
- Progress indicator and slide counter components

#### Responsive Design
- CSS Grid and Flexbox layouts for complex slide arrangements
- Mobile-first approach with breakpoint adjustments
- Touch and swipe navigation support through Reveal.js

### Content Structure
The presentation follows a 16-slide narrative arc:
1. Interactive opening with audience polls
2. Statistical revelations about AI job creation
3. Switzerland's AI leadership position
4. Educational paradigm shifts
5. Career evolution examples
6. Swiss corporate AI success stories
7. Human vs AI capabilities comparison
8. Future skills development framework
9. Career pathway options
10. Swiss educational advantages
11. Addressing common AI fears
12. Actionable development steps
13. Young Swiss innovator examples
14. Concrete learning resources
15. Motivational conclusion
16. Q&A discussion prompts

### Interactive Features
- Clickable poll options with visual feedback animations
- Manual reload and animation reset controls
- Background animation toggle functionality
- Mouse interaction effects in P5.js canvas
- Progressive content revelation system

## Development Workflow

### Making Content Changes
- All content is embedded in `index.html` within `<section>` elements
- Slides use CSS classes for consistent styling (`skill-card`, `stat-box`, `future-path`, etc.)
- Interactive elements require corresponding JavaScript event handlers

### Adding New Slides
- Copy existing `<section>` structure
- Follow established CSS class patterns for consistency
- Add reveal animations using `hidden-reveal` class
- Update slide counter logic if needed

### Customizing Animations
- P5.js parameters can be adjusted in the script section (particle count, colors, movement)
- CSS animation timing is controlled through `animation-delay` properties
- Reveal.js transition settings in the initialization object

### Testing and Deployment
- Use `npm start` for development with live reload
- Test across different devices and browsers
- Static HTML file can be deployed to any web server
- No build process required - direct file serving

## Browser and Device Support
- Modern browsers with CSS Grid and ES6 support
- Mobile devices through responsive design
- Keyboard and touch navigation
- Minimum resolution: 1024x768

## Educational Context
This presentation addresses Swiss high school students' concerns about AI's impact on future careers, emphasizing Switzerland's unique advantages in the AI economy while providing practical guidance for skill development.