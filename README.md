---
title: Readme
layout: layouts/landing
tags: footer
---
# Complete design system with tokens, components, templates & layouts. Build with Eleventy 2.0.1, LiquidJS & DecapCMS.
Project started Friday September 20th, 2024.

## Design System

### Tokens
CSS variables:
- color using calc & oklch
- typography using clamp & Google fonts
- spacing or density
- animations
- themes like dark mode
- macro layouts
Icons from JS library

### Components

#### Navigation
in _partials/navigation
- primary
- secondary
- footer
- pagination for JSON datas (pagination.page.previous.title)
- pagination for collections (getPreviousCollectionItem)
- breadcrumbs
- list

#### Content
in _partials/content
- card
- expander
- images
- table
- tabs
- tag
- callout

#### Forms
in _partials/forms
- button
- checkbox
- message
- radio
- select
- text input

### Templates / Patterns
in _partials/templates
- 404
- hero or banner
- main
- footer
- paginate datas
- forms

### Layouts
in _partials/layouts with HTML5 landmarks, grid positionning, wireframe & color versions.
using LiquidJS render with parameters.
- landing
- portfolio
- blog
- doc

## Eleventy
- CSS framework
- JSON datas: in _data
- collections: primary, secondary, footer, blog, doc
- iconography

### CSS Framework
/assets/css/style.liquid with permalink: /assets/css/style.css & LiquidJS render
- tokens.css
- base/normalize.css
- base/main.css
- themes/wireframe.css
- components/navigation/primary.css
- components/navigation/pagination.css
- components/forms/cta.css
- layouts/blog.css

## Git
- headless CMS: DecapCMS
- Git repo: .git (maybe Gitflow)
- GitHub with GitHub Pages deploy