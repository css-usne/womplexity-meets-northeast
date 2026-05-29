# Womplexity Meets Northeast

A satellite session connecting the international Womplexity community with the US Northeast Chapter of the Complex Systems Society.

## Website

This repository contains the website for the "Womplexity Meets Northeast: Connecting Communities" satellite session.

- **Website**: https://css-usne.github.io/womplexity-meets-northeast/
- **Event Format**: Half-day morning satellite session
- **Focus**: Women researchers in complex systems across diverse disciplines and career stages

## Event Overview

This satellite session brings together two complementary community-building efforts:

- **Womplexity**: Women in Complexity - an international network
- **CSS/US-NE**: Complex Systems Society U.S. Northeast Chapter - a regional chapter

### Program Structure

- **14:45-15:00**: Invited Speaker 1 (keynote)
- **15:05-15:48**: Three contributed talks (computer science/physics, social science, earth science/ecology)
- **15:50-16:00**: Northeast CSS Chapter spotlight
- **16:00-16:10**: Coffee break
- **16:10-16:30**: Invited Speaker 2 (keynote)
- **16:30-17:20**: Panel discussion (4-5 panelists + moderator)
- **17:20-17:30**: Closing remarks & networking

## Website Structure

```
├── index.html          # Main website page
├── styles.css          # Stylesheet (red/maroon theme)
└── README.md           # This file
```

## Features

- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Clean, simple structure (static HTML/CSS)
- ✅ Easy to update speaker information
- ✅ Themed with red/maroon colors (matching Northeast CSS Chapter branding)
- ✅ GitHub Pages ready

## Setup

The website is automatically deployed via GitHub Pages. Simply push changes to the `main` branch and the site will update at:
```
https://css-usne.github.io/womplexity-meets-northeast/
```

## Updating Content

### Add Speaker Information

Edit the speakers section in `index.html`. Replace `TBA` placeholders with:
- Speaker name
- Speaker role
- Speaker bio (can add to speaker-role class)
- Speaker image (replace speaker-placeholder div with an img tag)

### Update Contact Information

Edit the contact section in `index.html`:
- Update email address
- Update Womplexity website link
- Update CSS Northeast Chapter link

### Customize Colors

Edit `:root` variables in `styles.css`:
```css
--primary-red: #a61c1c;
--dark-maroon: #6b0000;
--accent-gold: #d4af37;
```

## Contributing

To make updates:
1. Clone the repository
2. Make changes to `index.html` or `styles.css`
3. Commit with a descriptive message
4. Push to the main branch
5. Changes will be live within minutes

## Communities

- **Womplexity**: https://womplexity.org
- **CSS Northeast Chapter**: https://css-us-ne.org

---

Built with ❤️ for the Womplexity and CSS US Northeast communities.