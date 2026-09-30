# YACL Modrinth Page (Offline)

An offline-capable version of the YetAnotherConfigLib (YACL) Modrinth page that works without API dependencies.

## Features

- Full Modrinth-style page design preserved
- Offline functionality (no API calls required)
- Version selection modal for Minecraft versions:
  - Minecraft 26.2 (Fabric)
  - Minecraft 1.21.11 (Fabric)
- Local JAR downloads
- English language support

## Deployment

### Render.com

This project is configured for deployment on Render.com using the included `render.yaml` file.

To deploy:

1. Push this repository to GitHub
2. Create a new Web Service on Render.com
3. Connect your GitHub repository
4. Render will automatically detect the `render.yaml` configuration
5. Deploy

### Local Development

To run locally:

```bash
# Using Python
python -m http.server 8080

# Using Node.js
npx serve

# Using PHP
php -S localhost:8080
```

Then open http://localhost:8080 in your browser.

## Files

- `index.html` - Main page with offline modifications
- `YetAnotherConfigLib-YACL-26.2.jar` - Minecraft 26.2 version
- `YetAnotherConfigLib-YACL-1.21.11.jar` - Minecraft 1.21.11 version
- `css/` - Styling files
- `js/` - JavaScript files
- `images/` - Image assets
- `fonts/` - Font files

## Credits

- Original Modrinth page design
- YetAnotherConfigLib by isXander
