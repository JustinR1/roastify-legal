# App Icon Upload Instructions

## Step 1: Copy the Icon
Copy your app icon from your private repo:
- **Source:** `roll-call-app/assets/icon.png`
- **Destination:** Root of this repo (same level as `index.html`)
- **File name:** `app-icon.png`

## Step 2: Add to Git
```bash
git add app-icon.png
git commit -m "Add app icon for social sharing"
git push
```

## What This Does
When someone shares https://roastifyai.app from your app's "Share with Friends" button, the Open Graph meta tags will display:
- Title: "RoastifyAI: Get Roasted by AI"
- Description: "Upload a photo and get hilariously roasted by AI 🔥"
- Image: Your app icon
- URL: https://roastifyai.app

This creates a nice preview card instead of plain text when sharing on social media or messaging apps.
