+++
title = 'Introduction Poison'
date = 2024-07-10T23:08:10+05:30
draft = false
series = 'How to use Poison theme'
tags = ["hugo", "introduction"]
+++

Poison is a clean, professional Hugo theme designed to captivate your readers.

It’s also tiny and privacy conscious. No JavaScript frameworks, icon packs, or Google fonts. No ads or trackers polluting your console window. We kept things simple. A little vanilla JavaScript, a dash of CSS, and the power of Hugo.

All the static assets for the site (JS files, CSS, and fonts) are located within the theme’s /assets/ directory. That way you know exactly what’s going onto your site.

Check out our demo site’s analytics here to gauge community interest in the theme.

## Features
In addition to the standard Built-in templates and shortcodes that come with Hugo, Poison offers some unique features of its own.

### Light & Dark Mode
Give readers the choice to read in light or dark mode. The user’s preference is remembered and saved in local storage. Light mode is the default for first time visitors, but you can change this in your config file.

### Table of Contents
Provide a floating table of contents for readers with large enough screens (i.e. screen-width > 1600 pixels).

If you prefer not to display a table of contents, you can disable them site-wide in your config.toml file.

Alternatively, you can choose to disable the table of contents on a per-post basis by putting the flag in the frontmatter of an individual post.

```
---
title: "Example to demonstrate how to hide the table of contents on a single post"
date: 2023-07-10
draft: false
hideToc: true
tags: ["Hugo"]
---
```