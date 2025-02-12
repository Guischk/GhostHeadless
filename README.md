# Ghost Headless Theme

A minimal Ghost theme designed to disable the frontend and operate in headless mode. This theme returns 404 responses for all frontend requests while keeping the Ghost Admin and API fully functional.

## Features

- 🚫 Completely disabled frontend
- ✅ Fully functional Ghost Admin
- 🔑 Accessible Content API
- 🎯 Optimized for headless usage
- 🔒 Search engine indexing prevented

## Installation

1. Download or clone this repository
2. Copy the `headless-theme` folder to your Ghost themes directory
3. Restart Ghost
4. In Ghost Admin, go to Settings > Design and activate "Ghost Headless Theme"

## Usage

After installation, your Ghost instance will:

- Return 404 for all frontend requests
- Keep Ghost Admin accessible at `/ghost`
- Maintain API endpoints:
  - Content API: `/ghost/api/v3/content`
  - Admin API: `/ghost/api/v3/admin`

## Configuration

The theme is configured with:

- No frontend rendering
- API-only mode
- 25 posts per page in API responses
- All Ghost card styles disabled
