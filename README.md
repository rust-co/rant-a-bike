# Rant-a-Bike Podcast Landing Page

🚴 A beautiful, responsive landing page for the Rant-a-Bike podcast with links to all major podcast platforms, email contact, and Mailchimp newsletter subscription.

## Live Site

The site is hosted on GitHub Pages at: `https://rust-co.github.io/rant-a-bike`

## Features

- **Modern, Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Large Logo Display** - Eye-catching bike emoji with gradient background
- **Podcast Platform Links** - Direct links to:
  - RSS Feed (rss.com)
  - Spotify
  - Deezer
  - Apple Podcasts
  - YouTube
- **Email Contact Link** - Easy way for listeners to get in touch
- **Mailchimp Newsletter Integration** - Embeddable subscription form with validation
- **Beautiful Gradients** - Purple/blue gradient design throughout

## Customization

### Update Podcast Links

Edit `index.html` and replace the following URLs with your actual podcast links:

```html
<!-- RSS Feed -->
https://rss.com/podcasts/rant-a-bike

<!-- Spotify -->
https://open.spotify.com/show/your-podcast-id

<!-- Deezer -->
https://www.deezer.com/show/your-podcast-id

<!-- Apple Podcasts -->
https://podcasts.apple.com/podcast/rant-a-bike/id

<!-- YouTube -->
https://www.youtube.com/c/rant-a-bike

<!-- Email Contact -->
hello@rant-a-bike.com
```

### Setup Mailchimp Integration

1. Create a Mailchimp account at https://mailchimp.com
2. Create an audience/list for your podcast
3. In Mailchimp, go to "Audience" → "Signup forms" → "Embedded forms"
4. Copy your form's embed code
5. Replace the form section in `index.html` with your Mailchimp embed code (keep the styling)

### Update Email Address

Edit the "Get in Touch" button:

```html
<a href="mailto:your-email@example.com" class="email-link">
```

### Customize Colors

The site uses a purple-to-blue gradient. To change colors, edit the CSS in `index.html`:

```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

Change `#667eea` and `#764ba2` to your preferred colors.

## File Structure

```
rant-a-bike/
├── index.html      # Main landing page (all HTML, CSS, and form in one file)
├── README.md       # This file
```

## Deployment

This site is automatically deployed to GitHub Pages whenever you push changes to the `main` branch. The site will be available at:

```
https://rust-co.github.io/rant-a-bike
```

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients and flexbox
- **JavaScript** - Mailchimp form validation (included via CDN)
- **GitHub Pages** - Free hosting

## License

MIT License - Feel free to use and modify for your podcast project.

## Support

For questions or issues, open an issue on this repository.

---

**Made for podcast creators by podcast creators** 🎙️
