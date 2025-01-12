# Blogfolio (aka PrasadM's Blog)

Welcome to PrasadM's Blog, a personal blog built using Jekyll. This project showcases various posts, portfolio items, and products.

## Introduction

Blogfolio is a web application that combines a personal blog and portfolio. It allows users to showcase their projects and share their thoughts through blog posts.

## Features

- Responsive design
- Blog post management
- Project showcase
- Contact form
- SEO friendly

## Getting Started
*Prerequisites*
[Ruby](https://www.ruby-lang.org/en/documentation/installation/)
[Jekyll](https://jekyllrb.com/docs/installation/)

## Installation

To get started with the project, clone the repository and install the dependencies:

```sh
git clone https://github.com/prasad-kmd/blogfolio.git
cd blogfolio
bundle install
```

## Usage

To run the project locally, use the following command:

```sh
bundle exec jekyll serve
```

Open your browser and navigate to `http://localhost:4000` to view the website.

## Configuration

The main configuration file is ```_config.yml``` . Update this file to change site settings such as title, email, description, and more.

## Adding Content

### Blog Posts

Blog posts are stored in the ```_posts``` directory. Create a new file with the following naming convention:

```
YEAR-MONTH-DAY-title.MARKUP
```

Example:

```markdown
---
layout: post
title:  "Welcome to Jekyll!"
date:   2025-01-06 20:28:36 +0530
categories: jekyll update
---
Your content here.
```

### Portfolio Items

Portfolio items are stored in ```portfolio.yml``` . Add new items in the following format:

```yaml
- name: "Project Name"
  url: "/project-url"
  description: "Project description"
```

### Products

Products are stored in ``` products.yml ```b. Add new items in the following format:

```yaml
- name: "Product Name"
  url: "/product-url"
  description: "Product description"
```

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Project Structure

The project structure is as follows:

```markdown
📦 prasad-kmd/blogfolio
├─ .gitignore
├─ 404.html
├─ Gemfile
├─ Gemfile.lock
├─ _config.yml
├─ _data
│  ├─ portfolio.yml
│  └─ products.yml
├─ _drafts
│  ├─ you-draft-posts-here.html
├─ _includes
│  ├─ KaTeX.html
│  ├─ fontawesome.html
│  ├─ footer.html
│  ├─ head.html
│  ├─ highlightjs.html
│  ├─ navigation-bad.html
│  ├─ navigation.html
│  ├─ post-card.html
│  └─ share-fab.html
├─ _layouts
│  ├─ default.html
│  ├─ home.html
│  └─ post.html
├─ _posts
│  ├─ your-posts-here.html
├─ assets
│  ├─ css
│  │  ├─ blog.css
│  │  ├─ button.css
│  │  ├─ common.css
│  │  ├─ fonts
│  │  │  ├─ brand-icons.eot
│  │  │  ├─ brand-icons.svg
│  │  │  ├─ brand-icons.ttf
│  │  │  ├─ brand-icons.woff
│  │  │  ├─ brand-icons.woff2
│  │  │  ├─ icons.eot
│  │  │  ├─ icons.otf
│  │  │  ├─ icons.svg
│  │  │  ├─ icons.ttf
│  │  │  ├─ icons.woff
│  │  │  ├─ icons.woff2
│  │  │  ├─ outline-icons.eot
│  │  │  ├─ outline-icons.svg
│  │  │  ├─ outline-icons.ttf
│  │  │  ├─ outline-icons.woff
│  │  │  └─ outline-icons.woff2
│  │  ├─ index.css
│  │  └─ semantic.css
│  ├─ cursor
│  │  ├─ cursor_fluent.svg
│  │  ├─ cursor_plumpy.svg
│  │  ├─ help.cur
│  │  └─ pointer.cur
│  ├─ font
│  │  ├─ [some fonts included]
│  │  ├─ fonts.css
│  │  └─ stylesheet.css
│  ├─ fontawesome-free-5.15.4-web
│  │  ├─ LICENSE-and-icons
│  ├─ img
│  │  ├─ svg
│  │  │  ├─ 720x480.svg
│  │  │  ├─ 9to5G.svg
│  │  │  ├─ 9to5M.svg
│  │  │  ├─ aa.svg
│  │  │  ├─ banner.svg
│  │  │  ├─ blogger.svg
│  │  │  ├─ deviantart.svg
│  │  │  ├─ facebook.svg
│  │  │  ├─ facebook2.svg
│  │  │  ├─ github.svg
│  │  │  ├─ gmail.svg
│  │  │  ├─ google.svg
│  │  │  ├─ google_maps.svg
│  │  │  ├─ linkedin.svg
│  │  │  ├─ medium.svg
│  │  │  ├─ meta.svg
│  │  │  ├─ reddit.svg
│  │  │  ├─ researchgate.svg
│  │  │  ├─ telegram_app.svg
│  │  │  ├─ twitter_circled.svg
│  │  │  ├─ weather.svg
│  │  │  ├─ web_address.svg
│  │  │  └─ youtube.svg
│  │  └─ webp
│  │     ├─ WEB_LOGO01_PM.webp
│  │     └─ pm.webp
│  ├─ js
│  │  ├─ _js
│  │  │  └─ script_org.js
│  │  ├─ components
│  │  │  ├─ advice.js
│  │  │  ├─ ipconfig.js
│  │  │  └─ weather.js
│  │  ├─ fetch
│  │  │  ├─ 9to5G.js
│  │  │  ├─ 9to5M.js
│  │  │  └─ AP.js
│  │  ├─ index.js
│  │  ├─ jquery-3.7.1.min.js
│  │  ├─ rss-parser.min.js
│  │  ├─ rss-parser.min.js.map
│  │  └─ semantic.js
│  └─ vid
│     └─ bg.mp4
├─ blog-01-06-2025.xml
├─ blog
│  ├─ index.html
│  └─ index.old.html
├─ index.html
├─ load-more-posts.html
├─ portfolio.html
├─ products.html
└─ profile.html
```
©generated by [Project Tree Generator](https://woochanleee.github.io/project-tree-generator)

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Make sure to follow the code style and include tests for any new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.