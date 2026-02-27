# Calgary × Aramco Ventures — Investment Website

## File Structure
```
calgary-site/
├── index.html
├── README.md
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   └── images/
│       └── (add your photos here)
```

## How to Deploy on GitHub Pages

1. Go to github.com and create a new repository (e.g. `calgary-aramco`)
2. Upload all these files — keeping the folder structure exactly as-is
3. Go to **Settings → Pages**
4. Under **Source**, select **Deploy from a branch**
5. Select `main` branch and `/ (root)` folder
6. Click **Save**
7. Your site will be live at: `https://YOUR-USERNAME.github.io/calgary-aramco/`

## Adding Your Calgary Hero Photo

1. Save your Calgary skyline image as `assets/images/calgary-hero.jpg`
2. Open `assets/css/style.css`
3. Find the `.hero-bg` rule (around line 90)
4. Replace the background property with:

```css
.hero-bg {
  position: absolute;
  inset: 0;
  background:
    linear-gradient(to bottom, rgba(10,10,10,0.2) 0%, rgba(10,10,10,0.7) 60%, #0A0A0A 100%),
    url('../images/calgary-hero.jpg') center / cover no-repeat;
  z-index: 0;
}
```

## Adding More Photos (Optional)
- Any section can have a background image using the same technique
- Recommended: Calgary skyline, Bow River, oil sands aerial, or downtown core photos
- Free photos available at: unsplash.com (search "Calgary")
