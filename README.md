# Pierce Mullen - Academic Website

A clean, minimalist academic website for an early-career neuroscientist, built with static HTML/CSS and fully responsive.

## 🌐 Live Site

Visit the site at: [https://piercemullen.github.io](https://piercemullen.github.io)

## ✨ Features

- **Home**: Professional bio and research statement
- **Research**: Publications with links to DOI, PDF, and data
- **Working Papers/Preprints**: Papers with status badges (Under Review, In Preparation, Preprint)
- **Methods & Skills**: Experimental techniques, computational methods, programming, and statistics
- **Teaching**: Experience, mentoring, and teaching interests
- **CV**: PDF download link
- **Contact**: Email, office location, and academic/social profile links
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Professional Design**: Clean, minimalist design optimized for academia

## 📝 How to Customize

### 1. Personal Information

Edit `index.html` and replace placeholder text (marked with brackets):

- `[University Name]` - Your university
- `[Building Name]` - Your building name
- `[City, State ZIP]` - Your location
- Email addresses
- Social media links

### 2. Research Content

#### Publications
Find the `<!-- Research Section -->` and update:
- Paper titles
- Authors (your name should be listed)
- Journal names and citations
- Update links to actual DOI, PDF, and data repositories

#### Working Papers
Find the `<!-- Working Papers Section -->` and:
- Add your actual preprints and working papers
- Change status badges: `under-review`, `in-preparation`, or `preprint`
- Update bioRxiv links

### 3. Methods & Skills

Update the skills lists under `<!-- Methods & Skills Section -->` to match your expertise.

### 4. Teaching

Update teaching experience, mentoring activities, and interests under `<!-- Teaching Section -->`.

### 5. CV

Replace `cv.pdf` with your actual curriculum vitae PDF file.

### 6. Contact Information

Update email, office location, and social/academic profile links in the `<!-- Contact Section -->`.

## 🎨 Customizing Design

### Colors
Edit `styles.css` and change the CSS variables in the `:root` section:

```css
:root {
    --primary-color: #2c3e50;    /* Main heading color */
    --accent-color: #3498db;      /* Links and accents */
    --background: #ffffff;        /* Page background */
    --background-alt: #f8f9fa;   /* Alternate section background */
}
```

### Fonts
Change fonts in the `:root` section:

```css
--font-primary: -apple-system, BlinkMacSystemFont, 'Segoe UI', ...
```

### Spacing
Adjust spacing variables:

```css
--spacing-sm: 1rem;
--spacing-md: 2rem;
--spacing-lg: 3rem;
```

## 🚀 Deployment

This site is ready to deploy on GitHub Pages:

1. Push your changes to the repository
2. Go to repository Settings → Pages
3. Select the branch to deploy (usually `main`)
4. Your site will be live at `https://yourusername.github.io`

## 📱 Mobile Responsive

The site includes:
- Hamburger navigation menu for mobile devices
- Responsive grid layouts
- Optimized typography for all screen sizes
- Touch-friendly interactive elements

## 🛠️ Technologies

- **HTML5**: Semantic markup
- **CSS3**: Modern responsive design with CSS Grid and Flexbox
- **Vanilla JavaScript**: Navigation functionality
- **No frameworks**: Easy to maintain and fast loading

## 📄 License

Feel free to use this template for your own academic website. No attribution required.

## 💡 Tips

- Keep content concise and professional
- Update publication lists regularly
- Replace all placeholder content before going live
- Test the site on multiple devices
- Optimize images if you add photos
- Keep your CV PDF up to date