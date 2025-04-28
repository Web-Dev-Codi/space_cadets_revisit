# Space Cadets - Interactive Solar System Explorer

## Overview
Space Cadets is an interactive web application that allows users to explore the planets in our solar system. The site features a modern, visually appealing interface with animated space particles in the background, creating an immersive cosmic experience.

## Features

### Home Page
- Engaging hero section with a call-to-action to explore planets
- Testimonials section highlighting user experiences
- Animated space particle background creating an immersive experience

### Planet Explorer
- Interactive planet browser with detailed information about each planet in our solar system
- Intuitive navigation system to browse between planets
- Detailed view showing key planetary statistics:
  - Mass
  - Radius
  - Gravity
  - Number of moons
  - Orbital period
  - Rotation period
- High-quality images and descriptions for each planet

### Planet Details
- Dedicated page for each planet with comprehensive information
- Multiple images for each planet
- Detailed scientific data fetched from the Solar System API
- Extended descriptions about each planet's unique characteristics

### Space News
- Latest articles about space exploration and astronomy
- Integration with the Spaceflight News API
- Direct links to original news sources

### Team Section
- Profiles of the Space Cadets team members
- Creative descriptions for each team member
- Visual showcase of the technologies used in the project

### Contact Page
- Contact form for user inquiries and feedback

## Technologies Used

### Frontend
- React 18.3.1
- React Router 6.28.0 for navigation
- Tailwind CSS 3.4.14 for styling
- Vite 5.4.10 as the build tool

### Animations & Visual Effects
- tsParticles 3.5.0 for the space particle background

### APIs
- Solar System API (le-systeme-solaire.net) for planetary data
- Spaceflight News API for the latest space-related articles

## Project Structure
- `src/components`: React components for different sections of the site
- `src/assets`: Images and other static assets
- `src/App.jsx`: Main application component with routing configuration
- `src/components/planetData.js`: Data and API integration for planetary information

## Getting Started

### Prerequisites
- Node.js (latest LTS version recommended)
- npm or yarn

### Installation
```bash
# Clone the repository
git clone https://github.com/Web-Dev-Codi/space_cadets_revisit

# Navigate to the project directory
cd space_cadets_revisit

# Install dependencies
npm install

# Start the development server
npm run dev
```

### Building for Production
```bash
npm run build
```

## Credits
- Planet data provided by [The Solar System OpenData](https://api.le-systeme-solaire.net/)
- Space news provided by [Spaceflight News API](https://spaceflightnewsapi.net/)
- Developed by the Space Cadets team
