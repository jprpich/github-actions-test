# Working With Me - Personal Website

A clean, modern "Working With Me" website to help colleagues and collaborators understand your working style, communication preferences, and how to work with you effectively.

## Features

- 📱 Fully responsive design (mobile, tablet, desktop)
- 🎨 Clean, modern UI with smooth animations
- 🎯 Easy-to-navigate sections
- ✏️ Simple to customize
- 🖨️ Print-friendly
- 🌐 No build process required - just open and view

## Sections Included

- **About Me** - Introduction and overview
- **Working Style** - How you work best, what energizes/drains you
- **Communication Preferences** - Best ways to reach you and response times
- **Feedback & Growth** - How you give and receive feedback
- **Collaboration Style** - What to expect and what you need
- **Availability** - Work hours and calendar preferences
- **Personal Interests** - Hobbies and interests outside work
- **Contact Information** - How to get in touch

## Customization Guide

### 1. Basic Information (index.html)

Replace these placeholders with your information:
- `Your Name` - Your actual name
- `Your Role / Title` - Your job title
- `your.email@example.com` - Your email address
- `@yourusername` - Your Slack/Teams handle
- Add your LinkedIn profile link

### 2. Content Sections

Each section is clearly marked in the HTML. Simply find the section and replace the placeholder text with your own content:

```html
<section id="about" class="section">
    <!-- Your content here -->
</section>
```

### 3. Colors & Styling (styles.css)

To customize colors, edit the CSS variables at the top of `styles.css`:

```css
:root {
    --primary-color: #2563eb;     /* Main brand color */
    --primary-dark: #1e40af;      /* Darker shade */
    --text-primary: #1f2937;      /* Main text color */
    --text-secondary: #6b7280;    /* Secondary text */
    /* ... more variables */
}
```

### 4. Emojis

Feel free to change the emojis in section titles or remove them entirely:
- 👋 About Me
- ⚡ Working Style
- 💬 Communication
- 🎯 Feedback
- 🤝 Collaboration
- 📅 Availability
- 🌟 Personal Interests

### 5. Adding or Removing Sections

To add a new section:
1. Copy an existing section block in `index.html`
2. Change the `id` attribute
3. Update the content
4. Add a navigation link in the nav bar

To remove a section:
1. Delete the section block
2. Remove the corresponding navigation link

## How to Use

1. **Local Development**: Simply open `index.html` in your browser
2. **Deploy**: Upload all files to your web hosting service
3. **GitHub Pages**: Push to a GitHub repo and enable GitHub Pages
4. **Share**: Share the URL with your team or include it in your email signature

## Deployment Options

### Option 1: GitHub Pages (Free)
1. Create a new GitHub repository
2. Upload these files
3. Go to Settings → Pages
4. Select your branch and save
5. Your site will be live at `https://yourusername.github.io/repo-name`

### Option 2: Netlify/Vercel (Free)
1. Drag and drop the folder to Netlify or Vercel
2. Get an instant URL

### Option 3: Custom Domain
Upload to any web hosting service that supports static HTML files.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Tips for Customization

- Keep content concise and scannable
- Use bullet points for easy reading
- Be authentic - this is about YOU
- Update regularly as your preferences evolve
- Consider adding a photo in the header
- Link to your calendar tool for easy scheduling

## License

Feel free to use and customize this template for your personal or professional use.

---

**Need help?** The code is well-commented and easy to modify. Each section is clearly labeled in the HTML file.

