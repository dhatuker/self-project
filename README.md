# Self-Project

A modern minimalist portfolio website and Express.js server inspired by https://www.irajune.com/

## Design Inspiration

This portfolio takes design cues from [irajune.com](https://www.irajune.com/) featuring:
- Clean, minimalist aesthetic with generous whitespace
- Elegant typography pairing
- Subtle hover interactions
- Smooth section transitions
- Responsive layout
- Focus on content hierarchy and readability

## Project Structure

```
self-project/
├── index.js           # Express.js server
├── package.json       # Project configuration
├── package-lock.json  # Dependency lock file
├── .gitignore         # Node.js exclusions
├── README.md          # Documentation
�└── public/
    └── index.html     # Portfolio website
```

## Features

### Design Elements
- **Minimalist Layout**: Clean whitespace, focused typography
- **Elegant Typography**: System font stack with thoughtful hierarchy
- **Subtle Interactions**: Hover states, smooth transitions
- **Section Animations**: Fade-in/slide-up as sections enter viewport
- **Responsive Design**: Optimized for mobile, tablet, and desktop
- **Generous Whitespace**: Inspired by irajune.com's spacious layout

### Sections
1. **Summary** - Personal introduction with skills tags
2. **Experience** - Professional timeline with company details
3. **Projects** - Showcase of work with project cards
4. **Contact** - Contact information and social links

### Technical Features
- Express.js server serving static files
- API endpoints: `/api` and `/health`
- Smooth scrolling navigation
- Active section highlighting
- IntersectionObserver-based animations
- Mobile-responsive navigation
- Optimized for performance

## Installation

```bash
cd self-project
npm install
```

## Available Scripts

- `npm start` - Start the server
- Visit `http://localhost:3000` to view the portfolio

## API Endpoints

- `GET /` - Serves the portfolio website
- `GET /api` - Returns API information
- `GET /health` - Health check endpoint

## Design Notes

The portfolio follows these principles from irajune.com:
- **Content First**: Ample whitespace lets content breathe
- **Typography Hierarchy**: Clear visual weight differences
- **Subtle Details**: Thin borders, delicate hover effects
- **Consistent Spacing**: Rhythm and alignment throughout
- **Minimal Color**: Black and white with occasional gray accents
- **Focus on Readability**: Optimized line lengths and spacing

## Customization

To personalize the portfolio:
1. Edit the content in `public/index.html`
2. Update skills, experience, projects, and contact information
3. Modify colors in the CSS variables if desired
4. Add your own projects and experiences

## Deployment

The Express.js server can be deployed to any Node.js hosting platform:
- Heroku
- Vercel (with Node.js server)
- AWS Elastic Beanstalk
- DigitalOcean App Platform
- Traditional VPS with Node.js

Simply run `npm start` to serve the portfolio on port 3000 (or PORT environment variable).