# PIXELATE TD - Support Page

Beautiful, responsive support page for PIXELATE TD hosted on GitHub Pages.

## Features

- 🌍 Multi-language support (English, 中文, 日本語)
- 📱 Fully responsive design
- 🎨 Modern gradient design
- 📧 Contact information
- ❓ FAQ section
- 🔗 Quick links

## Setup GitHub Pages

### Option 1: Enable GitHub Pages (Recommended)

1. Go to your repository settings on GitHub
2. Navigate to **Settings** → **Pages**
3. Under "Source", select **main** branch
4. Click **Save**
5. Your site will be published at: `https://yourusername.github.io/pixelate-web/`

### Option 2: Using Custom Domain (Optional)

1. Add a `CNAME` file with your custom domain
2. Configure DNS settings with your domain provider
3. Enable HTTPS in GitHub Pages settings

## Customize the Page

Edit `index.html` and update the following:

### 1. Email Address (Multiple Locations)
Replace ALL instances of `your-email@example.com` with your actual email:
```html
<a href="mailto:your-email@example.com">your-email@example.com</a>
```

Search for: `your-email@example.com` and replace all (appears 3 times - EN, ZH, JA)

### 2. GitHub Repository Link (Multiple Locations)
Replace `yourusername/pixelate` with your actual repository:
```html
<a href="https://github.com/yourusername/pixelate/issues" target="_blank">
```

Search for: `yourusername/pixelate` and replace all (appears 6 times)

### 3. App Store Links (Important!)
After your app is published, replace `your-app-id` with your actual App Store ID:
```html
<a href="https://apps.apple.com/app/your-app-id"
```

Search for: `your-app-id` and replace all (appears 3 times - EN, ZH, JA)

### 4. Update FAQs (Optional)
Customize the FAQ content in all three language sections.

## File Structure

```
pixelate-web/
├── index.html          # Main support page
└── README.md          # This file
```

## Local Testing

Simply open `index.html` in your browser to preview the page locally.

## For App Store Submission

Use this URL as your **Support URL**:
```
https://yourusername.github.io/pixelate-web/
```

## Deployment

Just push to GitHub and it will automatically be published:

```bash
git add .
git commit -m "Add support page"
git push origin main
```

Wait a few minutes for GitHub Pages to build and deploy.

## License

Same as PIXELATE TD project.
