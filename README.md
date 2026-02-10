# Portfolio Website

A modern, responsive personal portfolio website showcasing projects, skills, and professional experience.

![Portfolio Preview](https://via.placeholder.com/800x400/667eea/ffffff?text=Portfolio+Website)

## 🚀 Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Project Showcase**: Interactive portfolio gallery with filtering by technology
- **Blog Integration**: Built-in blog system with markdown support
- **Contact Form**: Functional contact form with email validation
- **Dark/Light Mode**: Theme toggle for better user experience
- **Smooth Animations**: CSS animations and scroll effects
- **SEO Optimized**: Meta tags and semantic HTML for better search engine visibility

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: CSS Grid, Flexbox, CSS Variables
- **Icons**: Font Awesome
- **Fonts**: Google Fonts
- **Deployment**: GitHub Pages

## 📂 Project Structure

```
portfolio-website/
├── index.html          # Main homepage
├── about.html          # About page
├── projects.html       # Projects showcase
├── blog.html          # Blog listing
├── contact.html       # Contact form
├── css/
│   ├── style.css      # Main stylesheet
│   └── responsive.css # Responsive styles
├── js/
│   ├── main.js        # Main JavaScript
│   └── projects.js    # Project filtering
├── images/            # Image assets
└── blog/             # Blog posts
```

## 🚦 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/kakadeaarush1-svg/portfolio-website.git
```

2. Navigate to the project directory:
```bash
cd portfolio-website
```

3. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server
```

4. Visit `http://localhost:8000` in your browser

## 🎨 Customization

### Changing Colors

Edit CSS variables in `css/style.css`:

```css
:root {
  --primary-color: #667eea;
  --secondary-color: #764ba2;
  --text-color: #333333;
  --bg-color: #ffffff;
}
```

### Adding Projects

Add project data in `js/projects.js`:

```javascript
const projects = [
  {
    title: "Project Name",
    description: "Project description",
    image: "images/project.jpg",
    tech: ["HTML", "CSS", "JavaScript"],
    github: "https://github.com/username/repo",
    live: "https://project-demo.com"
  }
];
```

## 📝 Writing Blog Posts

Blog posts are stored in the `blog/` directory as HTML files. Each post should include:

- Title and metadata
- Featured image
- Content with proper formatting
- Author information and date

## 🌐 Deployment

### GitHub Pages

1. Go to repository Settings
2. Scroll to GitHub Pages section
3. Select `main` branch as source
4. Click Save
5. Your site will be live at `https://username.github.io/portfolio-website/`

### Alternative Hosting

- **Netlify**: Connect your GitHub repo for automatic deployments
- **Vercel**: Deploy with zero configuration
- **Cloudflare Pages**: Fast global CDN distribution

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Aarush Kakade**

- GitHub: [@kakadeaarush1-svg](https://github.com/kakadeaarush1-svg)
- Portfolio: [Coming Soon]

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Unsplash for placeholder images
- The open-source community for inspiration

## 📞 Contact

Feel free to reach out for collaborations or questions!

---

⭐ Star this repository if you find it helpful!
