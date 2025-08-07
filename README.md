# Villa One Six - Record Label Website

A modern, responsive website for Villa One Six record label, showcasing artists and providing a platform for music discovery.

## Features

- **Responsive Design**: Optimized for all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Artist Showcase**: Integrated Spotify embeds for each artist
- **Social Media Integration**: Direct links to all social platforms
- **Contact Form**: Interactive contact form for inquiries
- **SEO Optimized**: Meta tags and structured content for search engines
- **Fast Loading**: Optimized images and lazy loading for performance

## Artists Featured

- **Mwef**: Electronic music producer with innovative soundscapes
- **D3dbeat**: Dynamic producer pushing electronic music boundaries

## Technologies Used

- HTML5
- CSS3 (with modern features like Grid, Flexbox, and CSS Variables)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Poppins)

## Deployment on Vercel

### Prerequisites
- Node.js installed on your machine
- Vercel account (free at vercel.com)
- Vercel CLI installed globally: `npm install -g vercel`

### Deployment Steps

1. **Prepare the project**:
   ```bash
   cd /Users/Chris/Downloads/VillaOneSix
   ```

2. **Deploy to Vercel**:
   ```bash
   vercel
   ```

3. **Follow the prompts**:
   - Set up and deploy? **Y**
   - Which scope? Select your account
   - Link to existing project? **N**
   - Project name: **villa-one-six** (or your preferred name)
   - Directory: **./** (current directory)
   - Auto-detect settings? **Y**

4. **Custom Domain Setup** (after initial deployment):
   - Go to your Vercel dashboard
   - Select your project
   - Go to Settings → Domains
   - Add `villaonesix.com`
   - Configure DNS records as instructed by Vercel

### Alternative: GitHub Integration

1. **Create a GitHub repository**:
   - Create a new repository on GitHub
   - Push your code to the repository

2. **Connect to Vercel**:
   - Go to vercel.com
   - Click "New Project"
   - Import your GitHub repository
   - Deploy automatically

## File Structure

```
VillaOneSix/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── package.json        # Project configuration
├── vercel.json         # Vercel deployment configuration
├── README.md           # Project documentation
└── Images/             # Image assets
    ├── Final logo with writing/
    │   └── villaonesix.com.png
    ├── Final logo without writing/
    │   └── icon.png
    └── sunset.png
```

## Customization

### Adding New Artists

1. **HTML**: Add a new artist card in the artists section:
   ```html
   <div class="artist-card">
     <div class="artist-info">
       <h3 class="artist-name">Artist Name</h3>
       <p class="artist-description">Artist description...</p>
       <div class="artist-social">
         <!-- Social links -->
       </div>
     </div>
     <div class="spotify-embed">
       <!-- Spotify embed iframe -->
     </div>
   </div>
   ```

2. **Update the stats**: Change the artist count in the about section

### Changing Colors

The main brand colors are defined in CSS:
- Primary: `#ff6b35` (Orange)
- Secondary: `#ff9a00` (Amber)
- Dark: `#1a1a1a` (Near Black)

### Updating Contact Information

Edit the contact section in `index.html` and update:
- Email address
- Social media links
- Contact form action (if using a backend service)

## Performance Optimization

- Images are optimized for web
- Lazy loading implemented for Spotify iframes
- CSS and JavaScript are minified for production
- Proper caching headers configured in `vercel.json`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

MIT License - Feel free to use and modify for your own projects.

## Support

For questions or issues, contact: info@villaonesix.com
