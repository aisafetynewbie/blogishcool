# AI Safety Blog

A simple, clean blog about AI safety topics, designed to be easily deployed to GitHub Pages.

## Features

- 🎨 Clean, modern design
- 📱 Responsive layout
- 🚀 Easy GitHub Pages deployment
- 📝 Simple HTML structure (no build step required)
- 🔄 GitHub Actions workflow for automatic deployment

## Getting Started

### Local Development

1. Clone the repository:
```bash
git clone <your-repo-url>
cd blogishcool
```

2. Open `index.html` in your browser or use a simple HTTP server:
```bash
python3 -m http.server 8000
# Then visit http://localhost:8000
```

### Adding New Posts

1. Create a new HTML file in the `posts/` directory
2. Use the existing post files as templates
3. Add a link to your new post in `index.html`

### Deployment to GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings → Pages in your GitHub repository
3. Under "Source", select "GitHub Actions"
4. The workflow will automatically deploy your site when you push to `main`

Alternatively, you can manually trigger the deployment workflow from the Actions tab.

## Project Structure

```
blogishcool/
├── index.html          # Homepage
├── about.html          # About page
├── styles.css          # Main stylesheet
├── posts/              # Blog post directory
│   ├── why-ai-safety-matters.html
│   ├── understanding-alignment.html
│   └── robustness-challenges.html
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Actions deployment workflow
└── README.md           # This file
```

## Customization

- Edit `styles.css` to change colors, fonts, and layout
- Modify `index.html` to update the homepage
- Update the navigation links in each HTML file's header
- Change the footer text in each HTML file

## License

Feel free to use this as a starting point for your own blog!
