# file_share - hosted via GitHub Pages

**Site:** https://alexfw16.github.io/file_share/

Drop a PDF here -> it will be hosted at `https://alexfw16.github.io/file_share/YOUR-FILE.pdf`

## Upload 45MB PDF (quick)

1. Copy PDF into this folder:
   ```bash
   cp /path/to/your.pdf .
   ```

2. Push to GitHub Pages:
   ```bash
   git add your.pdf
   git commit -m "Add PDF"
   git push
   ```

3. Wait ~30-60s for Pages to deploy, then share:
   ```
   https://alexfw16.github.io/file_share/your.pdf
   ```

Anyone can download directly - no login needed.

## Alternative: via `gh` CLI
```bash
gh release create v1.0 your.pdf --title "PDF"  # also works, but Pages URL is shorter
```

Site source: `main` branch `/` (Pages legacy build). `.nojekyll` enabled for binary files.
