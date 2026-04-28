# Rey John Raya Portfolio

A modern, single-file HTML portfolio with embedded CSS and JavaScript. Features a responsive design with neon theming, smooth animations, and working contact form powered by Netlify Forms.

## Features

- ✨ Responsive design (mobile, tablet, desktop)
- 🎨 Neon dark theme with smooth animations
- 📱 Smooth scroll reveal effects
- ✉️ Working contact form (Netlify Forms)
- ⌨️ Typing animation for hero section
- 📊 Skill bars with animations
- 🔗 Social media links
- ⚡ Zero dependencies - pure HTML/CSS/JS

## Local Testing

1. Open `portfolio-rey.html` directly in your browser
2. Or use a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js (if installed)
   npx http-server
   ```

## Deploy to Netlify

### Option 1: Connect GitHub (Recommended)

1. Push this folder to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git remote add origin https://github.com/your-username/my-portfolio.git
   git push -u origin main
   ```

2. Go to [netlify.com](https://netlify.com)
3. Click "New site from Git"
4. Connect your GitHub repository
5. Deploy! Netlify will automatically handle form submissions

### Option 2: Drag & Drop Deploy

1. Go to [netlify.com](https://netlify.com)
2. Log in or sign up
3. Drag and drop the folder to Netlify
4. Your site is live!

### Option 3: Netlify CLI

```bash
npm install -g netlify-cli
netlify deploy --prod
```

## Contact Form

The contact form is powered by Netlify Forms. When deployed to Netlify, form submissions are automatically handled and you can:

- View submissions in the Netlify dashboard
- Set up email notifications
- Integrate with services like Slack or Zapier

## Customization

Edit `portfolio-rey.html` to update:
- **Name & title**: Search for "Rey John Raya"
- **Links**: Update GitHub, LinkedIn, and email URLs
- **Skills**: Modify the skills section
- **Projects**: Update the project timeline
- **Colors**: Change CSS variables in `:root` selector

## Browser Support

Works in all modern browsers:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers

## License

© 2026 Rey John Raya. All rights reserved.
