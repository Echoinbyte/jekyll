# Jekyll Portfolio Website

A modern, responsive Jekyll-powered portfolio website for Sambhav Aryal (Echoinbyte).

![Jekyll](https://img.shields.io/badge/Jekyll-4.3.3-CC0000?style=flat-square&logo=jekyll&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-3.0+-CC342D?style=flat-square&logo=ruby&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

## 🚀 Features

- **Responsive Design**: Mobile-first approach with modern CSS
- **Fast Loading**: Optimized for performance with minimal dependencies
- **SEO Friendly**: Structured data and meta tags for better search visibility
- **Projects Showcase**: Dedicated section for portfolio projects
- **Clean Typography**: Carefully selected fonts and spacing
- **Contact Form**: Easy way for visitors to get in touch

## 📁 Project Structure

```
jekyll/
├── _config.yml          # Site configuration
├── _data/
│   └── projects.yml     # Project data
├── _includes/
│   └── head.html        # HTML head section
├── _layouts/
│   └── default.html     # Default page layout
├── _sass/
│   └── base.scss        # Base styles
├── assets/
│   ├── defaults.scss    # Default styles
│   └── css/
│       └── style.css    # Compiled CSS
├── about.md             # About page
├── contact.md           # Contact page
├── index.md             # Homepage
├── projects.md          # Projects page
└── Gemfile              # Ruby dependencies
```

## 🛠️ Getting Started

### Prerequisites

- Ruby 3.0 or higher
- Bundler gem

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/echoinbyte/jekyll.git
   cd jekyll
   ```

2. **Install dependencies**
   ```bash
   gem install bundler
   bundle install
   ```

3. **Serve the site locally**
   ```bash
   bundle exec jekyll serve
   ```

4. **Open your browser**
   Navigate to `http://localhost:4000` to view the site

### Development

- **Live Reload**: The development server automatically reloads when files change
- **Drafts**: Add `--drafts` flag to include draft posts
- **Future Posts**: Add `--future` flag to include future-dated posts

```bash
bundle exec jekyll serve --drafts --future --livereload
```

## 🎨 Customization

### Site Configuration

Edit `_config.yml` to customize:
- Site title and description
- Social media links
- SEO settings
- Build configurations

### Styling

- Modify `_sass/base.scss` for global styles
- Update `assets/css/style.css` for custom CSS
- Colors and typography can be adjusted in the SCSS variables

### Content

- **Homepage**: Edit `index.md`
- **About**: Update `about.md`
- **Projects**: Modify `projects.md` and `_data/projects.yml`
- **Contact**: Customize `contact.md`

## 📝 Adding Content

### Projects

Add new projects to `_data/projects.yml`:

```yaml
- name: "Project Name"
  description: "Brief project description"
  url: "https://project-url.com"
```

### Pages

Create new pages by adding Markdown files with front matter:

```markdown
---
layout: default
title: "Page Title"
---

# Your content here
```

## 🚀 Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at something like this: `https://echoinbyte.github.io/jekyll`

### Netlify

1. Connect your GitHub repository to Netlify
2. Set build command: `bundle exec jekyll build`
3. Set publish directory: `_site`
4. Deploy automatically on push

### Custom Domain

Add a `CNAME` file to the root directory with your domain name.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Sambhav Aryal (Echoinbyte)**
- GitHub: [@echoinbyte](https://github.com/echoinbyte)
- Website: [Your Website](https://echoinbyte.github.io/jekyll)

## 🙏 Acknowledgments

- Built with [Jekyll](https://jekyllrb.com/)
- Inspired by modern web design principles
- Thanks to the open-source community

---

⭐ Star this repository if you found it helpful!