# Images Directory

This folder contains all images used by The Vampire Diaries website.

## Image Organization

You can organize images in subdirectories as needed:

- `background.jpg` - Main background image (optional)
- `header-bg.jpg` - Header background image (optional)
- `footer-bg.jpg` - Footer background image (optional)
- `logo.png` - Website logo
- `characters/` - Character images
  - `elena.jpg`
  - `stefan.jpg`
  - `damon.jpg`
  - `caroline.jpg`
  - `bonnie.jpg`
  - `jeremy.jpg`

## Usage in CSS

Images are referenced in `styles.css` using relative paths:

```css
background-image: url('images/background.jpg');
```

## Supported Formats

- `.jpg` / `.jpeg`
- `.png`
- `.svg`
- `.webp`
- `.gif`

## Image Optimization Tips

- Use compressed images for web (optimize file size)
- Recommended max width: 1920px for backgrounds
- Recommended max width: 800px for content images
- Use WebP format for better compression when possible
