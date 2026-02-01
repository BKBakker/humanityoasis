# Humanity Oasis Website - Netlify Deployment

This is a complete, production-ready website for Humanity Oasis.

## 🚀 Quick Deploy to Netlify

### Option 1: Drag & Drop (Easiest)
1. Go to [Netlify Drop](https://app.netlify.com/drop)
2. Drag the entire `public` folder onto the upload area
3. Your site will be live immediately!

### Option 2: Git Deploy (Recommended for updates)
1. Create a new repository on GitHub
2. Upload these files to your repository:
   - `public/` folder (with all files inside)
   - `netlify.toml`
3. Go to [Netlify](https://app.netlify.com)
4. Click "Add new site" → "Import an existing project"
5. Connect to your GitHub repository
6. Netlify will auto-detect the settings from `netlify.toml`
7. Click "Deploy site"

### Option 3: Netlify CLI
```bash
npm install -g netlify-cli
cd netlify-site
netlify deploy --prod
```

## 📁 File Structure

```
netlify-site/
├── public/
│   ├── index.html          # Main HTML file with all meta tags & schema
│   ├── app.js              # React application code
│   ├── favicon.ico         # Custom favicon
│   ├── HUMANITYOASIS.png   # Certification badge logo
│   └── oct25_2015_25_of_39.jpg  # Autumn forest photo
├── netlify.toml            # Netlify configuration
└── README.md               # This file
```

## ✨ Features Included

- ✅ Fully responsive design
- ✅ React 18 with Hooks
- ✅ Tailwind CSS styling
- ✅ Google Fonts (Playfair Display, Crimson Pro)
- ✅ Lucide React icons
- ✅ Schema.org JSON-LD (SEO & LLM optimized)
- ✅ Netlify Forms integration (no backend needed!)
- ✅ Custom favicon
- ✅ Beautiful animations and effects
- ✅ Your autumn forest photo integrated
- ✅ Contact email: bryan@newsload.ca

## 📧 Form Submissions

The contact form is configured to use **Netlify Forms** - completely free and no backend required!

Form submissions will appear in your Netlify dashboard under:
`Site Settings` → `Forms`

You can also set up email notifications:
1. Go to your site in Netlify dashboard
2. Navigate to `Site Settings` → `Forms` → `Form notifications`
3. Add email notification to: `bryan@newsload.ca`

## 🎨 Customization

All content is in `public/app.js` and can be easily edited:
- Change text content
- Modify colors (search for color values like `amber-500`)
- Update contact information
- Add/remove sections

## 🌐 Custom Domain

To add your own domain:
1. Go to Netlify dashboard → `Domain settings`
2. Click `Add custom domain`
3. Follow the instructions to update your DNS settings

## 📱 Testing Locally

Simply open `public/index.html` in any modern web browser. Everything works offline!

## 🔧 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📞 Support

For questions about Humanity Oasis certification:
Email: bryan@newsload.ca
Website: https://www.newsload.ca/humanity-oasis

---

Built with ❤️ for human connection
