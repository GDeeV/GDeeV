# Gerrit De Vynck - Personal Website

A clean, professional personal website for showcasing your work as a technology journalist.

## What's Included

- **Responsive Design**: Works on all devices (mobile, tablet, desktop)
- **Modern Styling**: Built with Tailwind CSS
- **Smooth Navigation**: Fixed navigation bar with smooth scrolling
- **Key Sections**:
  - Home: Introduction and call-to-action
  - About: Your background and coverage areas
  - Work: Featured articles and reporting
  - Contact: Ways to reach you

## Customization Guide

### 1. Update Your Information

Open `index.html` and customize these sections:

**Contact Information (lines 147-152)**:
```html
<a href="mailto:your.email@washpost.com" ...>
<a href="https://twitter.com/yourusername" ...>
```

**Your Articles (lines 104-133)**:
Replace the placeholder article titles, descriptions, and links with your actual published work.

**About Section (lines 73-81)**:
Update the biography to reflect your actual experience and interests.

### 2. Optional Customizations

**Colors**: Change the color scheme by modifying lines 11-14:
```javascript
'primary': '#3B82F6',  // Currently blue
'secondary': '#10B981'  // Currently green
```

**Profile Photo**: Add a profile image in the home section if desired

## Deployment Options for Your Hover Domain

Since you have a domain with Hover, here are the easiest ways to get your site online:

### Option 1: GitHub Pages (Recommended - Free)
1. Keep your code in this GitHub repository
2. Go to Settings → Pages in your GitHub repo
3. Select the branch to deploy (usually `main`)
4. Your site will be at `https://yourusername.github.io/repositoryname`
5. In Hover, add a CNAME record pointing to your GitHub Pages URL

### Option 2: Netlify (Easy - Free)
1. Go to [netlify.com](https://netlify.com)
2. Sign up and connect your GitHub account
3. Deploy this repository
4. In Hover, update your domain's nameservers or add DNS records as Netlify instructs

### Option 3: Vercel (Easy - Free)
1. Go to [vercel.com](https://vercel.com)
2. Import this GitHub repository
3. Deploy with one click
4. Follow Vercel's instructions to connect your Hover domain

### Option 4: Traditional Web Hosting
1. Find a web host (Bluehost, SiteGround, etc.)
2. Upload `index.html` to your hosting account
3. Your Hover domain may already point to your hosting provider

## Setting Up DNS with Hover

Regardless of which hosting option you choose:

1. Log into [hover.com](https://hover.com)
2. Go to your domain's DNS settings
3. Follow your hosting provider's instructions to add:
   - A records (for direct IP addresses)
   - CNAME records (for services like GitHub Pages/Netlify/Vercel)

## Testing Locally

To preview your site before deploying:

1. Simply open `index.html` in your web browser
2. Or use a local server:
   ```bash
   # Python 3
   python -m http.server 8000

   # Then visit http://localhost:8000
   ```

## Next Steps

1. Customize the content in `index.html`
2. Add links to your actual published articles
3. Update contact information
4. Choose a deployment method
5. Connect your Hover domain

## Support

For questions about:
- **This template**: Feel free to ask!
- **Hover DNS**: Check [Hover's DNS documentation](https://help.hover.com/hc/en-us/articles/217282457)
- **GitHub Pages**: See [GitHub Pages docs](https://docs.github.com/en/pages)
- **Netlify**: See [Netlify docs](https://docs.netlify.com/)
