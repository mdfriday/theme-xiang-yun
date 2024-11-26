<h1 align=center>Hugo Xiang Yun Theme | <a href="https://themes.mdfriday.com" rel="nofollow">Demo</a></h1>

[![Hugo](https://img.shields.io/badge/hugo-0.134-blue.svg)](https://gohugo.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Build with Hugo](https://github.com/mdfriday/theme-xiang-yun/actions/workflows/hugo.yml/badge.svg)](https://github.com/mdfriday/theme-xiang-yun/actions/workflows/hugo.yml)

<h3><a href="https://mdfriday.com" rel="nofollow">MDFriday</a> showcase theme</h3>

**Xiang Yun**, meaning "Auspicious Cloud," is a theme designed to showcase all the themes supported by MDFriday.  
It embodies a sense of harmony and elegance, making it perfect for displaying theme variations with clarity and style.  
From simple previews to in-depth examples, this theme caters to MDFriday users looking for inspiration and customization.

![Screenshot](https://raw.githubusercontent.com/mdfriday/theme-xiang-yun/main/images/screenshot.png)

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Versioning](#versioning)
- [Contributing](#contributing)

---

## Features

- A unified showcase of all MDFriday-supported themes
- Elegant and minimal design inspired by auspicious clouds
- Responsive and mobile-friendly layout
- Configurable theme sections and navigation
- Optimized for quick theme previews and user exploration

---

## Requirements

- Hugo 0.112.7 or higher
- Go Modules enabled

---

## Installation

### Install as Hugo Module

The recommended way to install **Xiang Yun** is via Hugo Modules.

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
path = "github.com/mdfriday/theme-xiang-yun"
```

#### Step 3: Load and Run
Download the module and run your site:

```bash
hugo mod get -u
hugo server --minify
```

## Versioning

This theme follows a simple incremental versioning. e.g. `v1`, `v2` and so on. There might be breaking changes between versions.

To ensure stability, use a released version tag. For the latest features and updates, use the `main` branch.

## Contributing

### [Acknowledgements](https://github.com/mdfriday/theme-xiang-yun/graphs/contributors)

Contributions are encouraged and highly appreciated.  
Goals for contributions include:

- Enhancing customization options
- Maintaining simplicity and readability
- Supporting diverse MDFriday themes seamlessly
- Minimizing dependencies on external libraries

Report issues or suggest improvements via [GitHub Issues](https://github.com/mdfriday/theme-xiang-yun/issues).  
Pull requests are always welcome!