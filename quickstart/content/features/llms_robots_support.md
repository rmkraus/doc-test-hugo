+++
title = 'LLMs.txt & Robots.txt Support'
date = 2025-01-27T12:00:00-00:00
draft = false
+++

# LLMs.txt & Robots.txt Support

Built-in support for modern web standards that help both AI crawlers and search engines understand your documentation.

## LLMs.txt

Automatically generates a structured [`/llms.txt`](../../llms.txt) file that provides AI models with a clear overview of your site content, including:
- Site title and description
- Page hierarchy with links and descriptions
- Organized by sections and sub-sections

## Robots.txt

Enhanced [`robots.txt`](../../robots.txt) with dynamic features:
- Automatic sitemap reference
- Excludes pages marked with `sitemap_exclude: true`
- Includes llms.txt reference when enabled

Both files are generated automatically from your Hugo content structure.