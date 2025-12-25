# Dannyps Blog

A personal blog built with Jekyll, featuring thoughts.

## About

This is a personal blog where I share my reflections and insights on various topics. The blog is built using Jekyll and hosted at [blog.dannyps.net](https://blog.dannyps.net).

## Features

- 🎨 Dark theme using Minima skin
- 📝 Markdown-based blog posts
- 🔗 Social links integration (GitHub, X/Twitter)
- 📰 RSS feed support
- 🎯 Clean and responsive design

## Tech Stack

- **Jekyll** - Static site generator
- **Minima** - Jekyll theme (dark variant)
- **Ruby** - Build environment
- **Sass** - Custom styling

## Prerequisites

- Ruby (version 2.5.0 or higher)
- Bundler
- Jekyll

## Installation

1. Clone the repository:
```bash
git clone https://github.com/dannyps/blog.git
cd blog
```

2. Install dependencies:
```bash
bundle install
```

## Development

To run the blog locally:

```bash
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`

### Live Reload

Jekyll automatically watches for file changes and rebuilds the site. Simply refresh your browser to see updates.

## Project Structure

```
.
├── _config.yml          # Site configuration
├── _posts/              # Blog posts
├── _includes/           # Reusable components
├── _sass/               # Custom styles
├── _site/               # Generated static site (gitignored)
├── about.markdown       # About page
├── index.markdown       # Home page
├── Gemfile              # Ruby dependencies
└── 404.html            # Custom 404 page
```

## Writing Posts

Create a new file in `_posts/` following the naming convention:

```
YYYY-MM-DD-title-of-post.markdown
```

Include the front matter at the top:

```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS +0000
categories: category1 category2
---

Your content here...
```

## Configuration

Edit `_config.yml` to customize:
- Site title and description
- Author information
- Social media links
- Theme settings
- URL structure

## Building for Production

To build the site for production:

```bash
bundle exec jekyll build
```

The generated site will be in the `_site/` directory.

## Deployment

The blog is deployed at [blog.dannyps.net](https://blog.dannyps.net). Deployment details may vary based on hosting provider.

## License

Personal blog content and code. All rights reserved unless otherwise specified.

## Contact

- Email: blog-mail@dannyps.net
- GitHub: [@dannyps](https://github.com/dannyps)

## Acknowledgments

Built with [Jekyll](https://jekyllrb.com/) using the [Minima](https://github.com/jekyll/minima) theme.
