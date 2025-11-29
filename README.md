# Personal Website

A modern, responsive personal website showcasing your resume and professional profile.

## Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Sections Included**:
  - Hero section with call-to-action buttons
  - About Me
  - Work Experience (timeline format)
  - Education
  - Skills
  - Contact section with GitHub link
- **Smooth Scrolling**: Navigation with smooth scroll behavior
- **Mobile Menu**: Hamburger menu for mobile devices

## Getting Started

### Viewing the Website

**Easiest Method (No Installation Required):**
Simply double-click `index.html` to open it in your default web browser. The website will work perfectly this way!

**Alternative: Using a Local Web Server**

If you prefer to use a local server (optional), you can use one of these methods:

**Option 1: Using PowerShell (Windows)**
```powershell
# Navigate to the personal-website folder
cd personal-website

# Start a simple HTTP server
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

**Option 2: Using Node.js**
```bash
npx http-server -p 8000
```

**Note:** The website works perfectly fine by just opening `index.html` directly in your browser. A local server is only needed if you're developing features that require it.

## Customization

### Update Your Information

1. **Personal Details**: 
   - Replace "Your Name" throughout `index.html`
   - Update the GitHub username in the GitHub links (search for `yourusername`)
   - Update email address (search for `your.email@example.com`)
   - Update LinkedIn profile URL (search for `yourprofile`)

2. **About Section**: 
   - Edit the text in the "About Me" section to reflect your background

3. **Experience**: 
   - Update job titles, company names, dates, and responsibilities
   - Add or remove timeline items as needed

4. **Education**: 
   - Update degree information, university names, and dates
   - Add or remove education cards

5. **Skills**: 
   - Update skill tags to match your technical skills
   - Modify categories as needed

### Styling

- Colors can be customized in `styles.css` by modifying the CSS variables at the top:
  ```css
  :root {
      --primary-color: #6366f1;
      --secondary-color: #8b5cf6;
      /* ... */
  }
  ```

### GitHub Link

The website includes GitHub links in two places:
1. Hero section button
2. Contact section link

Make sure to update both with your actual GitHub username.

## File Structure

```
personal-website/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # JavaScript for interactivity
└── README.md       # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Deployment

You can deploy this website to:
- **GitHub Pages**: Push to a GitHub repository and enable Pages
- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your repository
- **Any static hosting service**

## License

Feel free to use this template for your personal website!

