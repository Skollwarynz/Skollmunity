# 🎨 Skollmunity

[![Deploy Jekyll to GitHub Pages](https://github.com/Skollmunity/Skollmunity.github.io/actions/workflows/deploy.yml/badge.svg)](https://github.com/Skollmunity/Skollmunity.github.io/actions/workflows/deploy.yml)
[![Jekyll](https://img.shields.io/badge/Static%20Site%20Generator-Jekyll-red.svg)](https://jekyllrb.com/)
[![GitHub Pages](https://img.shields.io/badge/Hosted%20On-GitHub%20Pages-blue.svg)](https://pages.github.com/)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

> **Learn, discover, and build a creative community together.**  
> An open source blog exploring color psychology, visual theory, superhero costume design, fine art, and film color analysis.

---

## 📖 About The Blog

**Skollmunity** is a dedicated platform created by [Skollwarynz](https://linktr.ee/skollmunity) to decode the hidden language of colors and visual composition. From the psychological impact of primary hues (red, blue, yellow) and metallic shades (gold, silver, bronze) to narrative color theory in cinema (*Whiplash*, *Squid Game*, *Gurren Lagann*) and comics, this blog offers accessible yet thoughtful reflections on visual storytelling.

Originally published on WordPress, this blog has been completely converted to **Jekyll** and open sourced on **GitHub Pages**.

---

## ✨ Features

- **🚀 100% Static & Fast**: Built with Jekyll 4.x and hosted directly on GitHub Pages with zero database overhead.
- **🎨 Custom Skollmunity Theme**: Ultra-lightweight custom HTML5/CSS3 layout tailored for color theory and art storytelling without heavy frameworks.
- **🌓 Automatic Dark Mode**: Smooth dark theme matching modern system preferences via CSS variables.
- **🖼️ Self-Contained Media**: All images and assets are archived locally in `assets/images/`, preserving the visual history.
- **🔗 Source-Linked Imagery**: Images featuring external artist/source credits are clickable links directly to their original platforms (Shutterstock, Freepik, Wikipedia, etc.).
- **📂 Categorized Browsing**: Instant navigation across core topics:
  - Color Psychology
  - Color Theory & Schemes
  - Superheroes & Costume Design
  - TV Series & Film Symbolism
  - Art History & Philosophy
- **📱 Responsive & Accessible**: Optimized for mobile, tablet, and desktop viewports with a responsive navigation drawer.

---

## 📁 Repository Structure

```text
.
├── _config.yml               # Jekyll site settings and metadata
├── Gemfile                   # Ruby gem dependencies
├── index.html                # Homepage with hero & post grid
├── categories.html           # Dedicated category index & archive
├── about.md                  # About Skollmunity page
├── art.md                    # "What is art?" standalone essay
├── 404.html                  # Friendly error page
├── _posts/                   # 28 published articles (YYYY-MM-DD-slug.md)
├── _drafts/                  # Unpublished article drafts
├── _layouts/                 # Custom layouts (default, home, post, page)
├── _includes/                # Header, footer, and head partials
├── assets/
│   ├── css/style.css         # Modern custom stylesheet
│   └── images/               # Archived local images & media
└── .github/workflows/        # Automated GitHub Pages CI/CD workflow
```

---

## 🚀 Running Locally

To run and preview the blog on your local computer:

### 1. Prerequisites
Make sure you have Ruby and Bundler installed:
```bash
ruby -v
gem install bundler
```

### 2. Clone & Install
```bash
git clone https://github.com/Skollmunity/Skollmunity.github.io.git
cd Skollmunity.github.io
bundle install
```

### 3. Start Development Server
```bash
bundle exec jekyll serve
```
Open your browser and navigate to:
```text
http://localhost:4000
```

To include drafts while editing:
```bash
bundle exec jekyll serve --drafts
```

---

## 🌐 Deploying to GitHub Pages

This project is configured for **`https://Skollmunity.github.io`**.

### Standard Setup:
1. Push this repository to GitHub under the name `Skollmunity.github.io` (or your preferred repo name).
2. Go to **Settings** > **Pages** in your GitHub repository.
3. Under **Build and deployment** > **Source**, choose:
   - **GitHub Actions** (recommended, uses `.github/workflows/deploy.yml`), OR
   - **Deploy from a branch** (`main` / root).
4. Your blog will automatically build and publish!

---

## ✍️ Adding New Articles

To publish a new article, create a new Markdown file in the `_posts/` folder following the naming convention:
`_posts/YYYY-MM-DD-your-slug.md`

Add the YAML front matter at the top:
```yaml
---
layout: post
title: "Your Article Title"
date: YYYY-MM-DD HH:MM:SS +0000
slug: "your-article-slug"
categories: ['Color psychology']
tags: ['color', 'psychology']
image: "/assets/images/your-image.jpg"
---

Your markdown content goes here...
```

---

## 🤝 Community & Connect

- **Author**: Skollwarynz
- **Linktree**: [linktr.ee/skollmunity](https://linktr.ee/skollmunity)
- **GitHub**: [github.com/Skollmunity](https://github.com/Skollmunity)

---

## 📜 License

- **Code & Theme**: Open source under the [MIT License](https://opensource.org/licenses/MIT).
- **Articles & Content**: Licensed under [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).
