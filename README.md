# 📄 GitHub Pages Resume

A modern, responsive resume website built for GitHub Pages. This template features a clean, professional design that looks great on all devices and prints beautifully.

## 🚀 Quick Start

### Step 1: Enable GitHub Pages

1. Push this repository to GitHub
2. Go to your repository on GitHub
3. Click on **Settings** (in the repository tab bar)
4. Scroll down to **Pages** in the left sidebar
5. Under **Source**, select **Deploy from a branch**
6. Choose **main** branch and **/ (root)** folder
7. Click **Save**
8. Your resume will be live at: `https://yourusername.github.io/repository-name`

### Step 2: Customize Your Resume

Edit the `index.html` file to add your personal information:

1. **Personal Information**
   - Replace "Your Name" with your actual name
   - Update the title/role
   - Add your bio/summary
   - Update contact information (email, phone, location)
   - Add your LinkedIn and GitHub URLs

2. **Profile Picture**
   - Replace the placeholder image URL in the `<img>` tag
   - You can use a direct link to an image or upload an image to your repository

3. **Experience Section**
   - Update job titles, companies, and dates
   - Modify bullet points to reflect your actual experience
   - Add or remove timeline items as needed

4. **Education Section**
   - Update degree, university, and graduation year
   - Modify relevant coursework

5. **Skills Section**
   - Update programming languages, frameworks, and tools
   - Add or remove skill categories as needed

6. **Projects Section**
   - Replace with your actual projects
   - Update project descriptions
   - Add real GitHub and demo links

## 🎨 Customization

### Colors

The color scheme is defined in CSS custom properties at the top of `styles.css`. You can easily change the colors by modifying these variables:

```css
:root {
    --primary-color: #2563eb;    /* Main accent color */
    --secondary-color: #1e40af;  /* Darker accent */
    --accent-color: #3b82f6;     /* Lighter accent */
    /* ... other colors */
}
```

### Fonts

The resume uses the Inter font family. You can change this by updating the Google Fonts link in `index.html` and the `--font-family` variable in `styles.css`.

### Layout

The design is fully responsive and includes:

- Desktop layout (1200px max width)
- Tablet layout (768px and below)
- Mobile layout (480px and below)
- Print-friendly styles

## 📱 Features

- **Fully Responsive**: Looks great on desktop, tablet, and mobile
- **Print Optimized**: Clean, professional print layout
- **Modern Design**: Uses modern CSS techniques and beautiful typography
- **Fast Loading**: Minimal dependencies, optimized for performance
- **SEO Friendly**: Proper HTML structure and meta tags
- **Accessible**: Semantic HTML and good contrast ratios

## 🛠 File Structure

```
cameron/
├── index.html          # Main resume page
├── styles.css          # All styling
└── README.md          # This file
```

## 🔧 Advanced Customization

### Adding New Sections

To add a new section, follow this structure in `index.html`:

```html
<section class="section new-section">
    <h3 class="section-title">
        <i class="fas fa-icon-name"></i>
        Section Name
    </h3>
    <!-- Section content here -->
</section>
```

### Custom Styling

Add your custom CSS at the bottom of `styles.css` to override default styles.

### Adding Analytics

To track visitors, add Google Analytics by inserting the tracking code in the `<head>` section of `index.html`.

## 📄 PDF Generation

To create a PDF version of your resume:

1. Open your GitHub Pages URL in a browser
2. Press `Ctrl+P` (or `Cmd+P` on Mac)
3. Select "Save as PDF"
4. The print styles will automatically apply for a clean PDF layout

## 🚨 Troubleshooting

### GitHub Pages Not Working?

- Make sure your repository is public (or you have GitHub Pro for private repos)
- Check that you've selected the correct branch and folder in Pages settings
- It may take a few minutes for changes to appear

### Images Not Loading?

- Use absolute URLs for images (e.g., from GitHub, LinkedIn, or image hosting services)
- Make sure image URLs are publicly accessible

### Custom Domain?

- In your repository settings under Pages, you can add a custom domain
- Create a `CNAME` file in your repository root with your domain name

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for improvements!

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

**Need help?** Open an issue in this repository or check the [GitHub Pages documentation](https://docs.github.com/en/pages).
