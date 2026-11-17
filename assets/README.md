# assets

Header images for the repo README and the GitHub social preview.

| File | Use |
|---|---|
| `banner-light.png`, `banner-dark.png` | README header, 2560x1040. Swapped by `<picture>` to match the reader's theme. |
| `social-preview.png` | GitHub social preview, 1280x640. Upload under Settings > General > Social preview. |
| `banner.html` | Source for all three. Uses IBM Plex fonts and the project's colour tokens. |

## Re-render

Needs Chrome and an internet connection (it loads IBM Plex from Google Fonts).

```
chrome --headless=new --hide-scrollbars --force-device-scale-factor=2 --window-size=1280,520 --virtual-time-budget=8000 --screenshot=banner-light.png "file:///PATH/assets/banner.html?theme=light"
chrome --headless=new --hide-scrollbars --force-device-scale-factor=2 --window-size=1280,520 --virtual-time-budget=8000 --screenshot=banner-dark.png  "file:///PATH/assets/banner.html?theme=dark"
chrome --headless=new --hide-scrollbars --force-device-scale-factor=1 --window-size=1280,640 --virtual-time-budget=8000 --screenshot=social-preview.png "file:///PATH/assets/banner.html?theme=light&h=640"
```
