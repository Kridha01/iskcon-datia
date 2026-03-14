# ISKCON Datia Website

A spiritual website for ISKCON Datia center.

## Setup

1. Download 4K Krishna images and place them in the `images/` folder:
   - `krishna1.jpg`, `krishna2.jpg`, `krishna3.jpg` (for hero slider) - 3840x2160 or higher
   - `about-krishna.jpg` (for about section) - High resolution
   - `seva1.jpg`, `seva2.jpg`, `seva3.jpg` (for seva section) - High resolution

2. **4K Image Sources**:
   - **Unsplash**: Search for "Krishna" - https://unsplash.com/s/photos/krishna
   - **Pexels**: Free 4K images - https://www.pexels.com/search/krishna/
   - **Pixabay**: High res Krishna images - https://pixabay.com/images/search/krishna/
   - **Wikimedia Commons**: Public domain - https://commons.wikimedia.org/wiki/Category:Krishna
   - **ISKCON Official**: https://iskcon.org/photos/

3. **Image Requirements**:
   - Format: JPG or PNG
   - Minimum: 1920x1080 for HD, 3840x2160 for 4K
   - Aspect ratio: 16:9 preferred for hero images
   - File size: Keep under 2MB for web performance

## Local Testing

Run: `python -m http.server 8000`

Visit: http://localhost:8000

## Global Hosting

### Option 1: GitHub Pages (Free)
1. Create a GitHub account
2. Create a new repository named `iskcon-datia`
3. Upload all files from this folder
4. Go to Settings → Pages → Source: Deploy from branch → Branch: main
5. Your site will be live at: https://yourusername.github.io/iskcon-datia/

### Option 2: Netlify (Free)
1. Go to https://netlify.com
2. Drag and drop the entire folder
3. Your site gets a free URL instantly

### Option 3: Vercel (Free)
1. Go to https://vercel.com
2. Import your GitHub repo or upload folder
3. Deploy automatically

## Features

- Responsive design
- Image slider
- Seva opportunities
- Contact information
- Bank donation details