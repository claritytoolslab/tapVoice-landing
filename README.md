# TapVoice Landing Page

Premium landing page for TapVoice Apple Watch AI app.

## Features

- **Premium Apple-inspired design** with gradients and glassmorphism
- **Mobile-first responsive** layout
- **Netlify Forms integration** with spam protection
- **Single HTML file** - no build process needed
- **Fast loading** with no external dependencies
- **SEO optimized** with proper meta tags

## Quick Start

1. Deploy to Netlify by connecting this repository
2. Forms will automatically work with Netlify Forms
3. Replace demo placeholders with actual content:
   - Add demo video in the demo section (look for "📹 Demo Video Coming Soon")
   - Update Apple Watch mockup with real screenshots
   - Customize colors and gradients in CSS `:root` variables

## Customization

### Colors
Edit the CSS custom properties in `:root`:
```css
--primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
--secondary-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
--accent-gradient: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
```

### Content
- Update hero headlines and copy
- Replace Apple Watch mockup content
- Add real demo video/GIF in demo section
- Customize benefits and features

### Forms
Two Netlify Forms are included:
- Hero form: `name="waitlist"`
- CTA form: `name="waitlist-final"`

## Deployment

1. Push to GitHub
2. Connect repository to Netlify
3. Deploy - no build command needed
4. Forms will automatically be active

## File Structure

```
/
├── index.html          # Complete landing page
├── README.md          # This file
└── netlify.toml       # Netlify configuration
```

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive
- Progressive enhancement for older browsers