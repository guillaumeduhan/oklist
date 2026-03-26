# OkList

> The awesome template to create your lists. Launch your directory in minutes.

## About

OkList is an open-source template to create lists and directories. Add your items to `data.json` and deploy.

## Features

- **Ready-to-use template**: Create your list in minutes
- **data.json**: Simply add your items to the JSON file
- **Promoted & Featured**: Highlight specific items
- **Dark Mode**: Light/dark theme included
- **SEO-Friendly**: Optimized for search engines

## Quick Start

1. Clone the repo
2. Add your items in `data.json`
3. `yarn && yarn dev`
4. Deploy to Vercel

## Data Format

```json
[
  {
    "image_url": "/items/example.png",
    "title": "My Item",
    "url": "https://example.com",
    "created_at": "2026-03-26",
    "is_promoted": false,
    "is_featured": false
  }
]
```

## Tech Stack

- Built with Astro
- Tailwind CSS v4
- React
