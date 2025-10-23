# Customization Checklist

Before deploying your support page, you need to customize these items in `index.html`:

## ✅ Required Changes

### 1. Email Address (3 locations)
- [ ] Line ~297: English section email
- [ ] Line ~377: Chinese section email
- [ ] Line ~445: Japanese section email

**Find:** `your-email@example.com`
**Replace with:** Your actual support email

### 2. GitHub Repository (6 locations)
- [ ] Line ~303: English section Issues link
- [ ] Line ~337: English section Documentation link
- [ ] Line ~386: Chinese section Issues link
- [ ] Line ~405: Chinese section Documentation link
- [ ] Line ~455: Japanese section Issues link
- [ ] Line ~474: Japanese section Documentation link

**Find:** `yourusername/pixelate`
**Replace with:** Your actual GitHub username/repo (e.g., `unayung/pixelate`)

### 3. App Store Links (3 locations - After App is Published)
- [ ] Line ~328: English section App Store link
- [ ] Line ~397: Chinese section App Store link
- [ ] Line ~466: Japanese section App Store link

**Find:** `your-app-id`
**Replace with:** Your actual App Store ID (e.g., `id123456789`)

Example:
```html
<!-- Before -->
<a href="https://apps.apple.com/app/your-app-id"

<!-- After -->
<a href="https://apps.apple.com/app/id1234567890"
```

## 🔧 Quick Replace Commands

You can use these commands in your editor:

```bash
# Replace email (do this 3 times or use "Replace All")
Find: your-email@example.com
Replace: your-actual-email@example.com

# Replace GitHub username (do this 6 times or use "Replace All")
Find: yourusername
Replace: unayung

# Replace App Store ID (AFTER app is published)
Find: your-app-id
Replace: id1234567890
```

## 📝 Optional Changes

- [ ] Update FAQ content to match your game's features
- [ ] Add more contact methods if needed
- [ ] Customize the response time text in footer

## 🚀 After Customization

1. Test the page locally by opening `index.html` in a browser
2. Verify all links work correctly
3. Check all three language versions (EN, 中文, 日本語)
4. Commit and push to GitHub
5. Enable GitHub Pages in repository settings
6. Use the GitHub Pages URL as your App Store Support URL

## 📱 App Store Support URL

Once deployed, your support URL will be:
```
https://yourusername.github.io/pixelate-web/
```

Use this URL in **App Store Connect** → **App Information** → **Support URL**
