Place your product images in this folder using the filenames below (or update the `src` paths in `index.html`):

- classic-99.jpg        — Classic 99-Bead Misbah
- butterscotch.jpg      — Butterscotch Misbah
- cognac-antiqued.jpg   — Cognac Antiqued Beads
- 33-bead.jpg           — 33-Bead Prayer Beads
- custom-designer.jpg   — Custom Designer Misbah
- gift-set.jpg          — Gift Set - Premium Package

Helpful PowerShell commands to download images (replace URL with your actual image URLs):

```powershell
cd "C:\Users\Administrator\Downloads\Amber Jewelry Web Content Writing Guide\assets"
Invoke-WebRequest -Uri "<IMAGE_URL>" -OutFile "classic-99.jpg"
Invoke-WebRequest -Uri "<IMAGE_URL>" -OutFile "butterscotch.jpg"
Invoke-WebRequest -Uri "<IMAGE_URL>" -OutFile "cognac-antiqued.jpg"
Invoke-WebRequest -Uri "<IMAGE_URL>" -OutFile "33-bead.jpg"
Invoke-WebRequest -Uri "<IMAGE_URL>" -OutFile "custom-designer.jpg"
Invoke-WebRequest -Uri "<IMAGE_URL>" -OutFile "gift-set.jpg"
```

After placing images, open `index.html` in a browser to verify. If you'd like, provide direct image URLs and I can download and add them for you.