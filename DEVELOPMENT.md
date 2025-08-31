# Development Guide

## Local Development Setup

To run this Jekyll site locally for development:

### Prerequisites
- Ruby 2.5+ (check with `ruby --version`)
- Bundler gem (`gem install bundler`)

### Installation
```bash
# Clone the repository
git clone https://github.com/ypdu/ypdu.github.io.git
cd ypdu.github.io

# Install dependencies
bundle install

# Serve the site locally
bundle exec jekyll serve

# Or serve with drafts and future posts
bundle exec jekyll serve --drafts --future
```

The site will be available at `http://localhost:4000`

### Development Workflow

1. **Making Changes**: Edit files and save - Jekyll will automatically regenerate
2. **New Posts**: Create files in `_posts/` with format `YYYY-MM-DD-title.md`
3. **New Courses**: Add files to `_courses/` collection
4. **New Projects**: Add files to `_portfolio/` collection
5. **Testing**: Always test locally before pushing to GitHub

### File Structure

```
├── _config.yml           # Site configuration
├── _data/
│   └── navigation.yml    # Site navigation menu
├── _includes/            # Reusable HTML snippets
├── _layouts/             # Page templates
├── _pages/               # Static pages (About, CV, etc.)
├── _posts/               # Blog posts
├── _courses/             # Course information
├── _portfolio/           # Project demos
├── _sass/                # Stylesheets
├── assets/               # CSS, JS, images
├── index.md              # Homepage
└── Gemfile               # Ruby dependencies
```

## Content Guidelines

### Blog Posts
- Use YAML front matter with title, date, permalink, and tags
- Support for code syntax highlighting with triple backticks
- Images should be stored in `/images/` directory
- GIFs are supported for demos

### Courses
- Include course metadata (venue, date, location)
- Provide clear learning objectives and schedule
- Link to external resources and materials
- Use consistent formatting for assignments

### Projects
- Include live demo links when available
- Provide GitHub repository links
- Add installation and usage instructions
- Include screenshots or GIFs showing functionality

## Markdown Features

### Code Blocks
```python
def hello_world():
    print("Hello, World!")
```

### Math (KaTeX)
Inline math: $E = mc^2$

Block math:
$$\int_0^\infty e^{-x} dx = 1$$

### Images with Captions
![Alt text](path/to/image.png)
*Caption text here*

### Links and References
[Link text](URL)
[Internal link](/posts/2025/01/post-title/)

## Deployment

The site is automatically deployed to GitHub Pages when you push to the `master` branch. No additional configuration needed.

### Custom Domain (Optional)
If using a custom domain:
1. Add your domain to the `CNAME` file
2. Configure DNS settings with your domain provider
3. Enable HTTPS in GitHub Pages settings

## Troubleshooting

### Common Issues

1. **Jekyll won't start**: Check Ruby version and run `bundle install`
2. **Changes not showing**: Clear browser cache or try incognito mode
3. **Build failures**: Check GitHub Pages build status in repository settings

### Getting Help
- GitHub Pages Documentation: https://docs.github.com/en/pages
- Jekyll Documentation: https://jekyllrb.com/docs/
- Minimal Mistakes Theme: https://mmistakes.github.io/minimal-mistakes/

## Performance Tips

- Optimize images before uploading (use tools like ImageOptim)
- Keep page sizes reasonable (< 1MB including images)
- Use relative links for internal content
- Test on mobile devices