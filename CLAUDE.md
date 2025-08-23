# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple Hugo static site for 12F ApS (CVR: 45362957), serving as a company landing page with contact information and business details. The site also hosts subpages for iOS app documentation (privacy policies, terms, etc.). Uses the `hugo-profile` theme for a clean, professional appearance.

## Development Commands

### Build and Serve
- `hugo serve` - Start development server with hot reload (usually runs on http://localhost:1313)
- `hugo` - Build the site for production (outputs to `public/` directory)
- `hugo --minify` - Build with minification for production

### Content Management
- `hugo new content/[app-name]/[filename].md` - Create new documentation pages for iOS apps
- Content is organized under `content/` directory with sections for different app documentation

## Architecture and Structure

### Core Configuration
- **Main config**: `hugo.yaml` - Contains site configuration, theme settings, and all customization
- **Theme**: Uses `hugo-profile` theme (v0.87.0+ Hugo required)
- **Base URL**: https://12f.dk
- **Language**: English (en-us)

### Directory Structure
- `content/` - App documentation organized by app name (pr/, sonicsnap/, wrnty/ contain privacy policies)
- `layouts/` - Custom layout overrides and partials
- `static/` - Static assets (company logo, images, favicons, etc.)
- `public/` - Generated site output (git-ignored, auto-generated)
- `themes/hugo-profile/` - Theme files (submodule)

### Key Features
- **Landing Page**: Simple company homepage with contact information and social links
- **App Documentation**: Dedicated subpages for iOS app privacy policies and documentation
- **Theme Configuration**: Dark theme by default, animations enabled, mobile-responsive
- **Contact Information**: Twitter (@rhjensen), LinkedIn, email (robert@12f.dk), CVR: 45362957
- **Navigation**: Streamlined - most theme sections disabled to focus on company branding

### Deployment
- **GitHub Actions**: Automated deployment to GitHub Pages via `.github/workflows/hugo.yml`
- **Hugo Version**: Uses v0.124.1 in CI/CD, local development uses v0.148.2
- **Build Process**: Includes minification and baseURL configuration for production

### Content Management Notes
- **Simple Structure**: Most hugo-profile theme sections are disabled - focus is on company landing page
- **App Documentation**: Each iOS app has its own content directory for privacy policies, terms, etc.
- **Static Content**: Documentation pages are simple markdown files, no complex content management needed
- **Theme Customization**: Uses Bootstrap 5 and FontAwesome 6, served locally

### Development Notes
- Site uses YAML configuration format instead of TOML
- Bootstrap and FontAwesome are served locally (not from CDN)
- Search and theme toggle are disabled to keep the site simple
- MathJax support is available but currently disabled
- Perfect for adding new iOS app documentation by creating new content directories
# important-instruction-reminders
Do what has been asked; nothing more, nothing less.
NEVER create files unless they're absolutely necessary for achieving your goal.
ALWAYS prefer editing an existing file to creating a new one.
NEVER proactively create documentation files (*.md) or README files. Only create documentation files if explicitly requested by the User.