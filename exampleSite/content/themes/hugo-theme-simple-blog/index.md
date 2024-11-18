---
aliases:
- /hugo-theme-simple-blog
draft: false
expiryDate: 2026-01-12T10:16:13Z
githubInfo:
  id: 267472161
  createdat: 2023-09-05T16:15:43Z
  updatedat: 2024-10-03T11:07:34Z
  name: hugo-theme-simple-blog
  description: simple-blog is a simple blog theme for hugo.
  htmlurl: https://github.com/10mohi6/hugo-theme-simple-blog
  stars: 10
htmlURL: https://github.com/10mohi6/hugo-theme-simple-blog
hugoVersion:
  min: ""
  max: ""
  extended: false
lastMod: 2024-07-21T10:16:13Z
meta:
  author:
    homepage: https://github.com/10mohi6
    name: 10mohi6
  description: A clean, responsive, minimal, bootstrap, customizable, light, personal,
    simple blog hugo theme
  features:
  - simple
  - blog
  - responsive
  - minimal
  - clean
  - light
  - personal
  - bootstrap
  - customizable
  - hugo
  - theme
  homepage: https://github.com/10mohi6/hugo-theme-simple-blog
  license: MIT
  licenselink: https://github.com/10mohi6/hugo-theme-simple-blog/blob/master/LICENSE.md
  min_version: "0.41"
  name: simple-blog
  tags:
  - simple
  - blog
  - responsive
  - minimal
  - clean
  - light
  - personal
  - bootstrap
  - customizable
  - hugo
  - theme
modulePath: github.com/10mohi6/hugo-theme-simple-blog
slug: hugo-theme-simple-blog
tags:
- blog
- bootstrap
- light
- minimal
- personal
- responsive
themeWarnings: []
title: simple-blog
weight: 10362

---
# simple-blog

simple-blog is a simple blog theme for [hugo](http://gohugo.io/).

![screenshot](https://raw.githubusercontent.com/10mohi6/hugo-theme-simple-blog/master/images/screenshot.png)

## Features

- based on [bootstrap](https://getbootstrap.com/)
- pagination
- tags
- categories

## Installation

```shell
$ git clone https://github.com/10mohi6/hugo-theme-simple-blog themes/simple-blog
```

## Usage

```shell
$ hugo server -t simple-blog
```

## Configuration

config.toml

```toml
theme = "simple-blog"
baseURL = "<your site url>"
title = "<your site title>"
copyright = "© 2020 copyright text."
paginate = 3
languageCode = "en"
DefaultContentLanguage = "en"
enableInlineShortcodes = true
footnoteReturnLinkContents = "^"

[menu]

  [[menu.main]]
    identifier = "about"
    name = "About"
    url = "/about/"
    weight = 10

[taxonomies]
category = "categories"
tag = "tags"

[params]
description = "<your site description>"
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
