# BKS Abogados - Website

Professional website for BKS Abogados, a legal services firm in Chile. This website provides information about the firm's services, team, and contact details.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Professional Styling**: Clean and modern design with a professional color scheme
- **Smooth Navigation**: Smooth scrolling between sections for better user experience
- **Accessibility**: Semantic HTML and proper ARIA labels for improved accessibility
- **SEO Optimized**: Meta tags and structured content for better search engine visibility

## 📁 Project Structure

```
bksabogados/
├── index.html      # Main HTML file with website structure
├── styles.css      # CSS file with all styling and responsive design
├── script.js       # JavaScript file for smooth scrolling functionality
├── README.md       # Project documentation
└── CNAME           # Domain configuration for GitHub Pages
```

## 🚀 Setup and Installation

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/CandelaBesprosvan/bksabogados.git
   cd bksabogados
   ```

2. **Open the website**:
   Simply open `index.html` in your web browser:
   - Double-click the `index.html` file, or
   - Right-click and select "Open with" your preferred browser

3. **Local Server (Optional)**:
   For a more realistic development environment, you can use a local server:
   
   **Using Python:**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```
   Then visit `http://localhost:8000` in your browser.
   
   **Using Node.js (http-server):**
   ```bash
   npx http-server -p 8000
   ```

## 🌐 Deployment

### GitHub Pages

This website is configured to be deployed using GitHub Pages.

1. **Automatic Deployment**:
   - The site is automatically deployed from the `main` branch
   - Any push to the `main` branch will trigger a deployment
   - The site will be available at `https://www.bksabogados.cl`

2. **Manual Deployment**:
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select the branch you want to deploy (usually `main`)
   - Select the root folder (`/`)
   - Click "Save"

3. **Custom Domain**:
   - The `CNAME` file contains the custom domain configuration
   - Ensure your DNS settings point to GitHub Pages servers
   - GitHub Pages will handle HTTPS automatically

## 📝 Customization

### Updating Content

1. **Edit HTML** (`index.html`):
   - Update text content in the hero, services, about, and contact sections
   - Add or remove service cards as needed
   - Modify contact information

2. **Edit Styles** (`styles.css`):
   - Customize colors by changing CSS variables in `:root`
   - Adjust spacing, fonts, and layouts
   - Modify responsive breakpoints if needed

3. **Edit JavaScript** (`script.js`):
   - The smooth scrolling functionality is already implemented
   - You can add additional interactivity as needed

### Color Scheme

The default color scheme can be customized in `styles.css`:

```css
:root {
  --primary-color: #1e3a8a;    /* Main brand color */
  --secondary-color: #3b82f6;  /* Secondary brand color */
  --accent-color: #60a5fa;     /* Accent color */
  --text-dark: #1f2937;        /* Dark text */
  --text-light: #6b7280;       /* Light text */
}
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup for structure
- **CSS3**: Modern styling with flexbox and grid
- **JavaScript (ES6+)**: Smooth scrolling and navigation
- **GitHub Pages**: Free hosting and deployment

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

Copyright © 2024 BKS Abogados. All rights reserved.

## 📞 Contact

For any inquiries about the website or legal services:

- **Email**: contacto@bksabogados.cl
- **Phone**: +56 9 0000 0000
- **Website**: https://www.bksabogados.cl

---

**Note**: This website is designed to be simple, professional, and easy to maintain. All files are static and require no build process or dependencies.