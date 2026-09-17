# Flavio Alvarez Penate Portfolio

This site is a personal portfolio for displaying my personal and school projects. It organizes project descriptions into a Jekyll collection and presents them through a simple portfolio website.

## Technologies and Frameworks

- **Jekyll**: Static site generator for building the portfolio.
- **Ruby and Bundler**: Runtime and dependency management for the Jekyll project.
- **Markdown**: Content format used for project, page, and post content.
- **Bootstrap 5**: Frontend layout and responsive navigation utilities, loaded from a CDN.
- **GitHub Pages**: Hosting and deployment platform.
- **GitHub Actions**: Automated build and deployment workflow.

## Project Structure

- `_projects/`: Personal and school project entries.
- `_layouts/`: Templates for the home page, project pages, and other pages.
- `_includes/`: Shared header and footer components.
- `index.markdown`: Portfolio homepage content.
- `_config.yml`: Jekyll site configuration and collection settings.

## Local Development

Install the Ruby dependencies and start the Jekyll development server:

```bash
bundle install
bundle exec jekyll serve
```

Then open the local URL shown by Jekyll, usually `http://localhost:4000/my-projects-site/`.
