# Building with Urva

Personal website for Urvashi Patel. A clean, professional site showcasing my journey as a Senior Integration Developer learning AI Engineering in public.

## Live Site

[Visit the site](https://www.urvashipatel.io)

## About

This is my personal website where I share:
- My learning journey from integration expert to AI engineer
- Weekly newsletter updates
- Technical writing and insights
- Progress on Integration Insider

Built with simplicity and performance in mind. No frameworks, just clean HTML, CSS, and JavaScript.

## Tech Stack

- HTML5
- CSS3 (no preprocessors)
- Vanilla JavaScript
- Google Fonts (Sora + DM Sans)
- Hosted on GitHub Pages

## Features

- Responsive design (works on all devices)
- Fast loading (no heavy dependencies)
- Clean, minimal interface
- Newsletter integration with Substack
- Smooth scrolling navigation
- Optimized for mobile

## Quick Start

### Deploy in 3 Steps

1. Fork or clone this repository
2. Rename to `index.html` if needed (GitHub Pages looks for `index.html`)
3. Enable GitHub Pages in Settings

Your site is live at `your-username.github.io`

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/your-username/your-username.github.io.git
```

2. Open `index.html` in your browser:
```bash
open index.html
```

That's it. No build process, no dependencies, no npm install.

## Customization

### Add Your Profile Image

1. Add your image file to the repository (e.g., `profile.jpg`)
2. Find line 527 in `index.html`
3. Replace:
```html
<div class="hero-image fade-in-up stagger-2">
    UP
</div>
```

With:
```html
<div class="hero-image fade-in-up stagger-2">
    <img src="profile.jpg" alt="Urvashi Patel" 
         style="width:100%;height:100%;object-fit:cover;border-radius:1rem;">
</div>
```

### Add Social Media Links

Find the footer section (around line 670). Uncomment and update:
```html
<!-- <a href="YOUR-LINKEDIN-URL" target="_blank">LinkedIn</a> -->
```

Remove `<!--` and `-->`, then add your actual URL.

### Update Latest Content

Find line 538. Update each content item:
```html
<a href="YOUR-POST-URL" class="content-item">
    <div class="content-item-left">
        <span class="content-icon">📝</span>
        <div>
            <h4>Your Post Title</h4>
            <span class="date">2025-01-15</span>
        </div>
    </div>
    <span class="content-item-arrow">→</span>
</a>
```

### Change Brand Colors

Current colors:
- Orange: `#f56607`
- Teal: `#02414b`

Find and replace throughout the CSS (in `<style>` section).

### Update Newsletter Link

The newsletter button links to your Substack. Update line 629:
```html
<a href="https://urvaship.substack.com/subscribe">
```

Replace with your newsletter URL.

## File Structure

```
.
├── index.html              # Main website file
├── profile.jpg             # Your profile image (add this)
└── README.md              # This file
```

That's it. Single file site. Simple to maintain.

## Deployment

### GitHub Pages (Recommended)

1. Create a repository named `your-username.github.io`
2. Upload `index.html`
3. Settings > Pages > Enable
4. Done

Your site is at `https://your-username.github.io`

### Other Options

**Netlify:**
- Drag and drop `index.html`
- Instant deployment

**Vercel:**
- Import repository
- One-click deploy

**Cloudflare Pages:**
- Connect GitHub
- Auto-deploys on push

All are free for personal sites.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Loads in under 1 second
- No JavaScript dependencies
- Minimal CSS
- Optimized images
- Score: 95+ on Lighthouse

## Updates

To update your site:
1. Edit `index.html` locally
2. Test by opening in browser
3. Commit and push to GitHub
4. Changes appear in 1-2 minutes

## Design Philosophy

- Content first
- Fast loading
- Mobile friendly
- No unnecessary features
- Easy to maintain
- Accessible to all

## Credits

Inspired by swyx.io and the "learning in public" philosophy.

## License

Free to use for your own personal website. Please give credit and link back.

## Questions?

Open an issue or reach out:
- Newsletter: [Building with Urva](https://urvaship.substack.com)
- Integration Insider: [integrationinsider.com](https://integrationinsider.com)

## Changelog

### Version 1.0 (January 2025)
- Initial release
- Clean, minimal design
- Newsletter integration
- Mobile responsive
- Fast performance
