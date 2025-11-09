# DeepBlue

Interactive real estate property tour mapping with glassmorphism UI design.

## Projects

### Willow Ridge Property Tour
Interactive map showcasing 8 properties in the Willow Ridge area (Bedford, TX).
- **View:** [Willow Ridge](https://yezhanggg.github.io/deepblue/willow-ridge/)
- **Date:** November 6, 2025
- **Features:**
  - Interactive property markers with photo/video indicators
  - Google Drive integrated photo galleries
  - Roadmap and Satellite layer switching
  - Property search with autocomplete
  - Glassmorphism UI with hover animations

### Summercrest Village Property Tour
Interactive map showcasing 4 duplex properties in Summercrest Village (Burleson, TX).
- **View:** [Summercrest](https://yezhanggg.github.io/deepblue/summercrest/)
- **Date:** November 6, 2025
- **Features:**
  - Interactive property markers with photo/video indicators
  - Google Drive integrated photo galleries
  - Roadmap and Satellite layer switching
  - Property search with autocomplete
  - Glassmorphism UI with hover animations

## Repository Structure

```
deepblue/
├── index.html              # Landing page
├── willow-ridge/           # Willow Ridge project (8 properties)
│   └── index.html          # Interactive map application
├── summercrest/            # Summercrest Village project (4 properties)
│   └── index.html          # Interactive map application
└── README.md
```

## Key Features

### Interactive Map Controls
- **Layer Switching:** Toggle between Roadmap and Satellite (hybrid) views
- **Property Markers:** Color-coded markers indicating content type:
  - 🔵 Blue: Photos only
  - 🟠 Orange: Videos only
  - 🟣 Purple: Photos + Videos
- **Search Functionality:** Location search with Google Maps autocomplete
- **Responsive Popups:** Property details with interactive hover effects

### UI/UX Design
- **Glassmorphism Design:** Frosted glass effect with backdrop blur
- **Interactive Animations:** Smooth hover effects on all UI elements
- **Property List Dropdown:** Expandable property navigation
- **Google Drive Integration:** Direct gallery viewing and folder access

### Technical Stack
- **Leaflet.js:** Primary mapping library
- **Google Maps API:** Satellite imagery and geocoding
- **Google Mutant Plugin:** Seamless Google Maps integration with Leaflet
- **Inter Font:** Modern, clean typography
- **CSS Transitions:** Smooth animations with cubic-bezier easing

## Adding New Projects

To add a new property tour:
1. Create a new folder: `mkdir project-name`
2. Add your files to the folder with `index.html` as the entry point
3. Update the landing page (`index.html`) to link to your new project
4. Configure property markers and Google Drive folder IDs

## Local Development

Simply open `index.html` in your browser, or use a local server:
```bash
python3 -m http.server 8000
# Visit http://localhost:8000
```

## Deployment

This site is deployed using GitHub Pages at: https://yezhanggg.github.io/deepblue/

## Credits

**Deepblue Capital Partners** - Real Estate Investment