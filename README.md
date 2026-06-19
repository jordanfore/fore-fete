# FORE fête

Interactive guide to Paris Fête de la Musique 2026 - curated for emerging creatives, independent thinkers, and community builders.

## What's Inside

- **92 events** across Paris - club nights, day parties, street activations, boat parties
- **20 restaurants** - street food & indie gems for the young creative crowd
- **Language guide** - essential phrases & cultural slang to navigate & engage with locals
- **Interactive map** - explore locations, filter by type, discover neighborhoods

## Features

- **Mobile-first design** - optimized for browsing on the go
- **List view** - all events with full details, searchable and filterable
- **Interactive map** - Leaflet.js powered, color-coded by event type
- **Live search** - find events by name, venue, or genre
- **Type filters** - Day Party, Club Night, Street, Food
- **Language reference** - searchable French/English phrases
- **Dark, intentional aesthetic** - aligned with FORE brand values

## How to Deploy to GitHub Pages

### 1. Create a GitHub Repository

```bash
# Initialize git (if not already done)
git init

# Add all files
git add .

# Initial commit
git commit -m "Initial commit: FORE fête guide"

# Create a new repo at github.com/jordanfore/fore-fete
# Then set the remote and push
git remote add origin https://github.com/jordanfore/fore-fete.git
git branch -M main
git push -u origin main
```

### 2. Enable GitHub Pages

1. Go to your repository: `https://github.com/jordanfore/fore-fete`
2. Click **Settings** (top right)
3. Scroll to **Pages** (left sidebar)
4. Under "Build and deployment", select:
   - **Source:** Deploy from a branch
   - **Branch:** main (or master)
   - **Folder:** / (root)
5. Click **Save**

### 3. Live Site

Your site will be live at: **https://jordanfore.github.io/fore-fete**

Share this link! 🔗

## Files Included

- `index.html` - Main interactive site (all CSS/JS embedded)
- `data.json` - All event, restaurant, and language data
- `README.md` - This file
- `.gitignore` - Git ignore rules

## Browser Compatibility

Works on all modern browsers (Chrome, Firefox, Safari, Edge). Mobile-first responsive design.

## Technology Stack

- **Frontend:** Vanilla HTML5, CSS3, JavaScript
- **Mapping:** Leaflet.js
- **Data:** Static JSON
- **Hosting:** GitHub Pages (free, fast, reliable)

## Design Philosophy

Built with FORE's core values:
- We don't wait fore change - we make it
- Where they see barriers, we see opportunity
- This guide exists for the people, by the people
- Community over clout

---

**FORE fête** - Democratizing access to Paris's underground creative scene. 🎭✨
