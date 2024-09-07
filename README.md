title: Nourhene Guellouz
description: |
  Welcome to my portfolio! I’m Nourhene Guellouz, a computer science student with a focus on web development, machine learning, data science, and automation. Explore my projects and skills below.

baseurl: "" # Base URL for your site
url: "https://nourhene-guellouz.github.io" # Your GitHub Pages URL

# Theme configuration
theme: jekyll-theme-cayman # A modern, responsive theme

# Logo
logo: /assets/img/headshot_circle.png

# Navigation
navigation:
  - title: Home
    url: /
  - title: Projects
    url: /projects
  - title: About
    url: /about
  - title: Contact
    url: /contact

# Social links (optional)
social_links:
  - title: LinkedIn
    url: https://www.linkedin.com/in/nourhene-guellouz
    icon: linkedin
  - title: GitHub
    url: https://github.com/Nourhene-Guellouz
    icon: github

# Layout options
show_downloads: false # Option to show a download button

# Author
author:
  name: Nourhene Guellouz
  email: nourheneguellouz@example.com

# Plugins (if needed)
plugins:
  - jekyll-feed
  - jekyll-seo-tag

# Markdown options
markdown: kramdown
kramdown:
  input: GFM

# Include extra files (e.g., Google Analytics, custom scripts)
include:
  - _pages
  - _projects

# Exclude files and directories
exclude:
  - README.md
  - .gitignore

# Sass (CSS) options
sass:
  style: compressed

# Permalinks
permalinks:
  posts: /:year/:month/:day/:title/
  pages: /:title/
