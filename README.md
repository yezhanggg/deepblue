# DeepBlue

Interactive mapping and data visualization projects.

## Projects

### Willow Ridge Comps
Real estate comparable properties analysis with interactive map visualization.
- **View:** [Willow Ridge](https://yezhanggg.github.io/deepblue/willow-ridge/)

## Repository Structure

```
deepblue/
├── index.html              # Landing page
├── willow-ridge/           # Willow Ridge project
│   └── index.html          # Main map application
└── README.md
```

## Adding New Projects

To add a new project:
1. Create a new folder: `mkdir project-name`
2. Add your files to the folder with `index.html` as the entry point
3. Update the landing page (`index.html`) to link to your new project

## Local Development

Simply open `index.html` in your browser, or use a local server:
```bash
python3 -m http.server 8000
# Visit http://localhost:8000
```

## Deployment

This site is deployed using GitHub Pages at: https://yezhanggg.github.io/deepblue/