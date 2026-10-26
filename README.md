# AADIT Infra & Builders website

Static site (no build step). Files: `index.html`, `privacy.html`, `netlify.toml`.

## Deploy with Netlify (auto-deploy on every push)
1. Push this repo to GitHub (see commands below).
2. Netlify > Add new site > Import an existing project > GitHub > pick this repo.
3. Build command: leave empty. Publish directory: `.` (already set in netlify.toml). Deploy.
4. Netlify detects the enquiry form on the first deploy. In the site's Forms settings, add an email notification so each enquiry reaches your inbox.
5. From now on, every `git push` to `main` redeploys automatically.

## First push
```
git remote add origin https://github.com/<your-user>/<repo>.git
git push -u origin main
```

## Placeholders to fill before launch
WhatsApp Business, Instagram, office address, phone (contact section); privacy notice details; real testimonials (`TESTIMONIALS` in index.html); real project photos.

## Real timelapse video (optional)
Put a short MP4 at `assets/timelapse.mp4`. If the file exists, the site shows it instead of the illustrated 14-stage animation. Keep it under ~25 MB (compress it first).
