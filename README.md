# Jatin Kumar - Portfolio Website

A portfolio website built with Quarto and Markdown for my MBA program at University Canada West.

## What's Included

This portfolio includes:
- Home/About page
- Resume
- Projects showcase
- Skills overview
- Contact information

## Project Structure

```
portfolio/
├── _quarto.yml          # Quarto configuration
├── index.qmd            # Home page
├── resume.qmd           # Resume
├── projects.qmd         # Projects
├── skills.qmd           # Skills
├── contact.qmd          # Contact
├── styles.css           # Styling
├── reflection.md        # Reflection on using AI tools
├── appendix.md          # AI drafts and revisions
└── README.md            # This file
```

## Getting Started

You'll need:
- Quarto (download from https://quarto.org)
- Git
- GitHub account

### Preview Locally

```bash
git clone https://github.com/yourusername/portfolio.git
cd portfolio
quarto preview
```

### Build the Site

```bash
quarto render
```

This creates the site in the `docs/` folder.

## Deploying to GitHub Pages

### 1. Set up Git

```bash
cd portfolio
git init
git add .
git commit -m "Initial commit"
```

### 2. Create GitHub Repository

- Go to GitHub and create a new repository
- Name it something like `portfolio`
- Don't initialize with README or .gitignore

### 3. Connect to GitHub

```bash
git remote add origin https://github.com/yourusername/portfolio.git
git branch -M main
git push -u origin main
```

### 4. Render and Push

```bash
quarto render
git add docs/
git commit -m "Add rendered site"
git push origin main
```

### 5. Enable GitHub Pages

- Go to your repo settings
- Find "Pages" in the sidebar
- Set source to: Branch `main`, folder `/docs`
- Save

Your site will be live at `https://yourusername.github.io/portfolio/`

## Updating the Site

```bash
quarto render
git add .
git commit -m "Update content"
git push origin main
```

## Customization

Edit `styles.css` to change colors and styling.
Edit `_quarto.yml` to modify navigation or add pages.

## Technologies

- Quarto
- Markdown
- HTML/CSS
- GitHub Pages

## Assignment Requirements

This project includes:
- Well-structured content
- Custom CSS styling
- Reflection document (reflection.md)
- Appendix with AI drafts (appendix.md)

## Troubleshooting

If the site isn't rendering: `quarto render --no-cache`

If GitHub Pages isn't updating, wait 5-10 minutes and check that you pushed to `main` with the `/docs` folder.

## Contact

Jatin Kumar  
Email: dhimanjatin191@gmail.com  
Phone: 778-122-6646

## Notes

This project was created for an MBA assignment at University Canada West. The reflection and appendix documents show how I used AI tools to help build the site.
