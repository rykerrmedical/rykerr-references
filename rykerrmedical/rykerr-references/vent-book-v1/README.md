# Clean Reference Pages

## What's Different

- No embedded CSS - uses your site's styles
- No headers/titles - just the iframe and controls
- Original source loads by default
- Clean control bar with 3 options:
  * Original Link (new tab)
  * Archive Link (new tab)
  * View Archive in Frame (button)

## Installation

1. **Copy all .md files** to your `vent-book-v1/` folder (or wherever you want)

2. **Add CSS to your main stylesheet** (e.g., `assets/css/main.css`):
   Copy the contents of `reference-styles.css` into your main CSS file

3. **Commit and push**:
   ```bash
   cd ~/rykerrmedical/rykerr-references
   # Delete old files
   rm -rf vent-book-v1/*.md
   # Copy new files
   cp ~/path/to/clean_reference_pages/*.md vent-book-v1/
   # Add CSS to assets/css/main.css or style.css
   git add .
   git commit -m "Update reference pages with clean layout"
   git push
   ```

4. **Wait for GitHub Pages to rebuild** (2-3 minutes)

## Features

- Loads original source immediately in iframe
- Control bar at top for switching views
- Uses all your site's existing styles
- Minimal, clean design
- Works with your existing navigation/header/footer

Total pages: 200
