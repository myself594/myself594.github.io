# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**一日三餐恋 (Three Meals a Day Love)** - A couples' life recording web application hosted on GitHub Pages. This is a pure frontend static website for couples to track their daily meals, anniversaries, and recipes together.

## Tech Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (no frameworks)
- **Hosting**: GitHub Pages (static site)
- **Storage**: Browser localStorage for data persistence
- **Language**: Chinese (zh-CN)

## Project Structure

```
/
├── index.html          # Main dashboard showing all pages in iframe grid
├── home.html           # Home page with daily overview
├── records.html        # Meal records list view
├── add-record.html     # Add new meal record form
├── anniversary.html    # Anniversary management page
├── add-anniversary.html # Add new anniversary form
├── recipes.html        # Couple's recipe collection
├── add-recipe.html     # Add new recipe form
├── profile.html        # User profile/settings page
└── README.md           # Project readme
```

## Design Conventions

- **Color Scheme**: Pink gradient theme (#FF6B8B to #FFA07A)
- **Font**: PingFang SC, Helvetica Neue, Arial
- **UI Style**: Modern mobile-first design with rounded corners, shadows, and smooth transitions
- **Icons**: Emoji-based icons throughout the interface

## Development Guidelines

1. **No Build Process**: This is a zero-configuration static site. Simply edit HTML files directly.

2. **Data Storage**: All data is stored in browser localStorage. Key patterns:
   - Meal records
   - Anniversaries
   - Recipes
   - User preferences

3. **Responsive Design**: All pages support mobile and desktop views using CSS media queries.

4. **Cache Control**: Meta tags disable browser caching for development convenience.

5. **Navigation**: Pages link to each other directly. The index.html serves as a dashboard showing all pages in iframes.

## Common Tasks

- **Add new feature**: Create a new HTML file following the existing page structure
- **Modify styles**: Edit the `<style>` section within each HTML file (styles are inline)
- **Add data fields**: Update both the form page and the list/display page
- **Test locally**: Open any HTML file directly in a browser
