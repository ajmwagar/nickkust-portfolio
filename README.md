# Nick Kust Portfolio

Personal portfolio and blog for Nick Kust, Head of Product at Future Present Labs.

🔗 **Live Site**: https://nickkust-portfolio.netlify.app

## About

This is a personal website built with [Hugo](https://gohugo.io/) using the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme. It includes:

- Personal blog with product and economics insights
- About page with professional background
- Contact information
- RSS feed for blog posts
- Dark/light mode toggle
- Mobile-responsive design

## Local Development

### Prerequisites

- [Hugo](https://gohugo.io/installation/) (extended version, v0.112.0 or later)
- [Git](https://git-scm.com/)

### Setup

1. Clone the repository:
```bash
git clone https://github.com/nickkust/nickkust-portfolio.git
cd nickkust-portfolio
```

2. Start the development server:
```bash
hugo server -D
```

3. Open http://localhost:1313 in your browser

## Deployment

This site is automatically deployed to [Netlify](https://netlify.com) on every push to the `main` branch.

## Site Structure

```
.
├── content/            # Site content
│   ├── about/         # About page
│   ├── contact/       # Contact page
│   └── posts/         # Blog posts
├── static/            # Static files (images, etc.)
├── themes/            # Hugo themes
│   └── PaperMod/
├── hugo.toml          # Site configuration
├── netlify.toml       # Netlify configuration
└── README.md          # This file
```

Built with ❤️ and [Hugo](https://gohugo.io/)
