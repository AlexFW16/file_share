# file_share

Drop a PDF here for someone else to download.

## Quick upload (45MB PDF)

### Option 1: Fastest - GitHub Release (Recommended for 45MB)
Keeps repo light, gives direct download link.

```bash
# Put your PDF in this folder, then:
gh release create v1.0 your-file.pdf --title "PDF share" --notes "45MB PDF"

# Share this link:
# https://github.com/AlexFW16/file_share/releases/download/v1.0/your-file.pdf
```

Or via web: https://github.com/AlexFW16/file_share/releases/new -> drag & drop PDF -> Publish -> share link.

### Option 2: Direct git push
```bash
# Put your PDF in this folder, then:
git add your-file.pdf
git commit -m "Add PDF"
git push

# Share this link:
# https://github.com/AlexFW16/file_share/blob/main/your-file.pdf
# Direct download (raw): https://raw.githubusercontent.com/AlexFW16/file_share/main/your-file.pdf
```

## Download
Other person just clicks the link above -> Download button / or `wget <link>`.
