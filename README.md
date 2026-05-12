# Naoki Aizawa - Academic Website

This is a Hugo-based academic website built with the [Wowchemy](https://wowchemy.com/) theme (formerly Academic).

## Quick Start

### Prerequisites
- [Hugo Extended](https://gohugo.io/installation/) (v0.100.0 or later)
- Git
- Node.js and npm (optional, for advanced customization)

### Installation

1. Clone this repository:
```bash
git clone https://github.com/naokiaizawa/naokiaizawa.github.io.git
cd naokiaizawa.github.io
```

2. Initialize the theme submodule:
```bash
git submodule update --init --recursive
```

3. Install Hugo and run the development server:
```bash
hugo server
```

Visit `http://localhost:1313` in your browser to see your site locally.

## Project Structure

```
content/
├── _index.md           # Homepage
├── authors/
│   └── admin/          # Your profile
├── publication/        # Your publications
├── project/            # Your projects
├── event/              # Talks and conferences
└── post/               # Blog posts
static/
├── uploads/            # CVs, documents
└── media/              # Images, videos
config.toml            # Site configuration
```

## Customization

### Update Your Profile
Edit `content/authors/admin/_index.md` with your information:
- Name, title, bio
- Research interests
- Education
- Skills
- Social media links

### Add Publications
1. Create a new folder in `content/publication/`
2. Add `index.md` with publication details
3. Example: `content/publication/my-paper/index.md`

### Add Projects
1. Create a new folder in `content/project/`
2. Add `index.md` with project details
3. Example: `content/project/my-project/index.md`

### Update Site Config
Edit `config.toml` to change:
- Site title and description
- Your email and contact info
- Social media profiles
- Other site-wide settings

### Add CV
Place your CV PDF at `static/uploads/resume.pdf`

## Deployment

### GitHub Pages
This site will automatically deploy to GitHub Pages when you push to the `main` branch (requires GitHub Actions configuration).

To enable GitHub Pages:
1. Go to repository Settings → Pages
2. Set source to "GitHub Actions"
3. Ensure your branch is `main` and the repo name is `username.github.io`

### Build for Production
```bash
hugo --minify
```

## Resources

- [Wowchemy Documentation](https://wowchemy.com/docs/)
- [Hugo Documentation](https://gohugo.io/documentation/)
- [Academic Theme Examples](https://wowchemy.com/templates/)

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

For issues and questions, please check the [Wowchemy GitHub Issues](https://github.com/wowchemy/wowchemy-hugo-themes/issues).
