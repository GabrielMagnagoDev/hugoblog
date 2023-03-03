---
title: "Meu primeiro post"
subtitle: "começando de algum jeito..."
date: 2023-01-23
draft: false
authors: ["Gabriel Magnago"]
description: "Discover what the Hugo - DoIt theme is all about and the core-concepts behind it."

tags: ["Markdown", "HTML"]
categories: ["documentation"]

featuredImage: "/posts/primeiro-post/laptop-vintage.webp"
featuredImagePreview: "/posts/primeiro-post/laptop-vintage.webp"


hiddenFromHomePage: false
hiddenFromSearch: false
lightgallery: true


toc:
  auto: false
code:
  copy: true

---

Discover what the Hugo - DoIt theme is all about and the core-concepts behind it.
<!--more-->


## Requirements

Lorem ipsum dolor sit amet, graecis denique ei vel, at duo primis mandamus. Et legere ocurreret pri,
animal tacimates complectitur ad cum. Cu eum inermis inimicus efficiendi. Labore officiis his ex,
soluta officiis concludaturque ei qui, vide sensibus vim ad.

* valid bullet
- valid bullet
+ valid bullet

## Installation

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

```js
grunt.initConfig({
  assemble: {
    options: {
      assets: 'docs/assets',
      data: 'src/data/*.{json,yml}',
      helpers: 'src/custom-helpers.js',
      partials: ['src/partials/**/*.{hbs,md}']
    },
    pages: {
      options: {
        layout: 'default.hbs'
      },
      files: {
        './': ['src/templates/pages/index.hbs']
      }
    }
  }
};
```