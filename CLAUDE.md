# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static marketing website for Gold Spotter, a gold prospecting mobile app. The site showcases app features and provides Google Play download links.

## Related Repository

The Gold Spotter mobile app source code is in a separate repository:
- **Git URL**: `git@github.com:cwoskoski/gold-spotter.git`
- **Relative path**: `../gold-spotter`

When working on features that require coordination between the website and app, reference the app repo at the relative path above.

## Architecture

- **Static site**: No build system, framework, or dependencies
- **Single page**: `index.html` with all content
- **Styling**: `css/styles.css` using CSS custom properties for theming
- **Assets**: `images/` contains logo and app screenshots

## Development

Open `index.html` directly in a browser. No server or build step required.

## Brand Colors (from app theme)

Defined as CSS custom properties in `:root`:
- `--primary-gold: #D4A017`
- `--bright-gold: #FFD700`
- `--deep-brown-bg: #1E1410` (main background)
- `--surface-brown: #2D1F1A`
- `--surface-variant: #3D2914`
