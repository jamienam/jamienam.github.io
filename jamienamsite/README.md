# Jamie Nam — Academic Site

Personal academic webpage. Static HTML + CSS, deployed via GitHub Pages.

Live at: https://jamienam.github.io/academic

## Editing

- `index.html` — landing page (About / Bio + research interests)
- `publications.html` — publication list
- `cv.html` — CV (education, experience, awards)
- `blog/index.html` — blog index
- `blog/*.html` — individual posts
- `assets/css/style.css` — styles

## Adding a blog post

1. Copy `blog/welcome.html` to `blog/your-post-slug.html`
2. Edit the title, date, and content
3. Add a `<li class="post-item">` entry to `blog/index.html`

## Profile photo

To replace the "JN" placeholder avatar with a real photo:

1. Drop your photo at `assets/images/profile.jpg`
2. In `index.html`, change:
   ```html
   <div class="avatar" aria-label="Profile photo placeholder">JN</div>
   ```
   to:
   ```html
   <div class="avatar"><img src="/assets/images/profile.jpg" alt="Jamie Nam"></div>
   ```
