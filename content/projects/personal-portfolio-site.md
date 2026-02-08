---
title: 'Personal Portfolio Site'
date: 2025-10-15T10:00:00-00:00
lastmod: 2025-10-15T10:00:00-00:00
description: 'A fast, SEO-optimized personal website built with Hugo. Features structured data, perfect Lighthouse scores, and automated deployment to GitHub Pages.'
tags: ['hugo', 'seo', 'static site']
tech: ['Hugo', 'HTML', 'CSS', 'GitHub Actions']
github: 'https://github.com/samsepiol/portfolio'
type: 'projects'
---

This website is itself a project. Built with Hugo for maximum performance and SEO optimization.

## Goals

The primary goal was to create a personal website that scores perfectly on Lighthouse audits for performance, accessibility, best practices, and SEO. Secondary goals included easy content management and automated deployment.

## Technical Approach

Hugo was chosen for its build speed and zero-JavaScript output. The theme is custom-built to maintain full control over the HTML output, ensuring semantic markup and proper structured data on every page.

### SEO Features

Every page includes JSON-LD structured data, Open Graph meta tags, Twitter Cards, and proper canonical URLs. The sitemap is generated automatically during the build.

### Performance

The site uses no JavaScript, a system font stack, minimal CSS, and fingerprinted assets with long cache headers. Images are lazy-loaded with explicit dimensions to prevent layout shift.

## Results

The site consistently achieves 100 scores across all Lighthouse categories. Time to First Byte is under 50ms thanks to static hosting on a CDN.
