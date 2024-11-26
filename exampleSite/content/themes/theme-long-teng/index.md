---
aliases:
- /theme-long-teng
draft: false
expiryDate: 2026-05-15T00:38:21Z
githubInfo:
  id: 0
  createdat: 0001-01-01T00:00:00Z
  updatedat: 0001-01-01T00:00:00Z
  name: ""
  description: ""
  htmlurl: ""
  stars: 0
htmlURL: https://github.com/mdfriday/theme-long-teng
hugoVersion:
  min: ""
  max: ""
  extended: false
lastMod: 2024-11-21T00:38:21Z
meta:
  author:
    homepage: https://mdfriday.com
    min_version: 0.112.7
    name: MDFriday
  demosite: https://longteng.app.mdfriday.com
  description: Long Teng is a vibrant product landing page theme inspired by Chinese
    colors. It is designed to showcase your product or service, highlight its key
    features, and engage potential users. With flexible configuration options, it’s
    perfect for creating a visually appealing and effective online presence.
  features:
  - responsive design
  - customizable content
  - Chinese color theme
  - service showcase
  - call-to-action buttons
  - user trust section
  homepage: https://github.com/mdfriday/theme-long-teng
  license: MIT
  licenselink: https://github.com/mdfriday/theme-long-term/blob/main/LICENSE
  name: Long Teng
  tags:
  - company
  - landing
  - responsive
  - light
  - mdfriday
modulePath: github.com/mdfriday/theme-long-teng
slug: theme-long-teng
tags:
- company
- landing
- responsive
- light
- mdfriday
themeWarnings: []
title: Long Teng
weight: 480

---
<h1 align=center>Hugo Long Teng Theme | <a href="https://mdfriday.com" rel="nofollow">Demo</a></h1>

[![Hugo](https://img.shields.io/badge/hugo-0.134-blue.svg)](https://gohugo.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Build with Hugo](https://github.com/mdfriday/theme-long-teng/actions/workflows/hugo.yml/badge.svg)](https://github.com/mdfriday/theme-long-teng/actions/workflows/hugo.yml)

<h3><a href="https://mdfriday.com" rel="nofollow">MD Friday</a> product launch Hugo theme</h3>

**Lóng Téng**, meaning "Soaring Dragon," is a theme crafted to symbolize growth, innovation, and power.  
It is designed for creating captivating product launch pages, showcasing your offerings with elegance and clarity.  
From highlighting features to telling your product's story, this theme is tailored for modern and forward-thinking creators.

![Screenshot](https://raw.githubusercontent.com/mdfriday/theme-long-teng/main/images/screenshot.png)

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Shortcodes](#shortcodes)
- [Versioning](#versioning)
- [Contributing](#contributing)

---

## Features

- Inspired by the Chinese color spectrum
- Configurable Navigation Menu
- Customizable Hero Section with Tagline
- Trust Indicators for Users and Websites
- Clean, Responsive, and Mobile-Friendly Design
- Optimized for Product Showcase Pages

---

## Requirements

- Hugo 0.112.7 or higher
- Go Modules enabled

---

## Installation

### Install as Hugo Module

The recommended way to install **Lóng Téng** is via Hugo Modules.

#### Step 1: Initialize Hugo Modules
If you haven't already, initialize Hugo modules in your project:

```bash
hugo mod init github.com/your/repo
```

#### Step 2: Update `config.toml`
Add the theme as a module in your configuration file:

```toml
[module]
[[module.imports]]
path = "github.com/mdfriday/theme-long-teng"
```

#### Step 3: Load and Run
Download the module and run your site:

```bash
hugo mod get -u
hugo server --minify
```

## Versioning

This theme follows a simple incremental versioning. e.g. `v1`, `v2` and so on. There might be breaking changes between versions.

If you want lower maintenance, use one of the released versions. If you want to live on the bleeding edge of changes, you can use the `main` branch and update your website when needed.

## Contributing

### [Extra credits to contributors](https://github.com/mdfriday/theme-manual-of-me/graphs/contributors)

Contributions are welcome and I will review and consider pull requests.  
Primary goals are:

- Keep it simple.
- Keep minimal (or zero) default configuration.
- Avoid interference with user-defined layouts.
- Avoid using JS if it can be solved by CSS.

Feel free to open issues if you find missing configuration or customisation options.
