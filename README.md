# Arrow Shift — Play Console Website

Static website for Google Play Console (website URL + privacy policy URL).

## Files

| File | Use |
|------|-----|
| `index.html` | App landing page / Play Console website URL |
| `privacy-policy.html` | Required privacy policy URL |
| `assets/logo.png` | App logo |
| `styles.css` | Shared styling |
| `play-store-listing.txt` | Copy-paste text for Play Console listing |

## Preview locally

Open in browser:

```bash
open website/index.html
```

## Host on Blogger (gxdevs)

1. Go to [Blogger](https://www.blogger.com) → your **gxdevs** blog
2. Create a new page/post for **Arrow Shift Home**
   - Switch to HTML view
   - Paste contents of `index.html` (or upload assets to Blogger and fix image paths)
3. Create another page for **Privacy Policy**
   - Paste contents of `privacy-policy.html`
4. Publish both pages and copy the public URLs

Suggested final URLs (update in app after publishing):

- Home: `https://gxdevs.blogspot.com/p/arrow-shift.html`
- Privacy: `https://gxdevs.blogspot.com/p/arrow-shift-privacy-policy.html`

## Play Console fields

| Field | Value |
|-------|--------|
| App name | Arrow Shift |
| Package | com.alienx.arrowshift |
| Developer | Alien X Software |
| Website | Your published `index.html` URL |
| Privacy policy | Your published `privacy-policy.html` URL |

## GitHub Pages (optional)

1. Create repo `arrow-shift-website`
2. Upload `website/` folder contents to root
3. Enable GitHub Pages → main branch
4. URL becomes: `https://YOUR_USERNAME.github.io/arrow-shift-website/`
