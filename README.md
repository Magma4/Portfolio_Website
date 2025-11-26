# Portfolio Website

A modern, responsive portfolio website showcasing professional experience, projects, skills, education, and certifications. Built with a focus on clean design, smooth animations, and user experience.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly across all devices
- **Dark Mode**: Built-in dark mode support with customizable themes
- **Interactive Portfolio**: Horizontal scrolling portfolio section with featured project highlighting
- **Animated Sections**: Smooth scroll animations and transitions using WOW.js
- **Contact Form**: Integrated contact form with FormSubmit integration
- **Magic Cursor**: Customizable cursor effects
- **Modern UI/UX**: Clean, professional design with modern web standards

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with animations and responsive design
- **JavaScript/jQuery**: Interactive functionality and animations
- **PHP**: Contact form backend (via FormSubmit)
- **Libraries & Frameworks**:
  - jQuery
  - WOW.js (scroll animations)
  - Devicons (technology icons)
  - Google Fonts (Mulish, Poppins)

## 📁 Project Structure

```
Portfolio_Website/
│
├── css/                    # Stylesheets
│   ├── colors.css         # Color themes
│   ├── darkMode.css       # Dark mode styles
│   ├── plugins.css        # Plugin styles
│   ├── style.css          # Main stylesheet
│   └── font/              # Custom fonts
│
├── img/                   # Images and assets
│   ├── favicon.png
│   ├── placeholders/      # Placeholder images
│   ├── resume/           # Resume assets
│   ├── slider/           # Hero and portfolio images
│   └── svg/              # SVG icons and graphics
│
├── js/                    # JavaScript files
│   ├── init.js           # Main initialization
│   ├── jquery.js         # jQuery library
│   ├── plugins.js        # Plugin scripts
│   └── modernizr.custom.js
│
├── modal/                 # Modal components
│   └── contact.php       # Contact form handler
│
└── index.html            # Main HTML file
```

## 🚀 Getting Started

### Prerequisites

No special prerequisites required. This is a static website that can run in any modern web browser.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Magma4/Portfolio_Website.git
cd Portfolio_Website
```

2. **Open with Live Server** (Recommended):

   - **VS Code**: Install the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer), then right-click on `index.html` and select "Open with Live Server"

   - **Other IDEs**: Use any Live Server extension or plugin available for your editor

   **Alternative methods:**

   - Simply open `index.html` directly in your web browser (double-click the file)

   - Use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000

   # Using Python 2
   python -m SimpleHTTPServer 8000

   # Using Node.js (http-server)
   npx http-server
   ```

   Then navigate to `http://localhost:8000` in your browser

### Configuration

- **Contact Form**: Update the FormSubmit email in `index.html` (line 994) to your email address
- **Social Links**: Update social media links in the contact section and footer
- **Personal Information**: Customize name, title, bio, and other personal details throughout `index.html`

## 📝 Sections

The portfolio includes the following sections:

1. **Hero**: Introduction with animated background
2. **About**: Professional summary and key competencies
3. **Portfolio**: Horizontal scrolling showcase of projects with GitHub integration
4. **Skills**: Technical expertise with progress indicators
5. **Experience**: Professional work history
6. **Education**: Academic background and certifications
7. **Certifications & Achievements**: Latest updates and credentials
8. **Contact**: Contact form and information

## 🎨 Customization

### Color Themes

The portfolio supports multiple color themes accessible through the settings panel:
- Blue, Green, Brown, Pink, Orange
- Black, White, Purple, Sky
- Cadet Blue, Crimson, Olive, Red

### Dark Mode

Dark mode is enabled by default. Toggle between light and dark modes using the settings panel.

### Adding Projects

To add a new project to the portfolio:

1. Add a new `portfolio_item` div in the portfolio section
2. Include GitHub repository URL for automatic OpenGraph preview
3. Add project details: title, status, description, technologies, and links

Example:
```html
<div class="portfolio_item" data-project="X">
    <div class="project_card">
        <div class="github_preview">
            <img src="https://opengraph.githubassets.com/1/username/repo" alt="Project Name" />
        </div>
        <h3 class="project_title">Project Name</h3>
        <p class="project_status">Status</p>
        <div class="project_description">
            <p>Project description...</p>
        </div>
        <p class="project_tech_full">Technologies Used</p>
        <a class="project_link" href="https://github.com/username/repo" target="_blank">→</a>
    </div>
</div>
```

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- IE 11+ (with fallbacks)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Raymond Frimpong Amoateng**

- GitHub: [@Magma4](https://github.com/Magma4)
- LinkedIn: [raymond-frimpong](https://www.linkedin.com/in/raymond-frimpong)
- Email: raymondamoateng@gmail.com

## 🙏 Acknowledgments

- Design inspiration from modern portfolio templates
- Icons from [Devicons](https://devicon.dev/)
- Fonts from [Google Fonts](https://fonts.google.com/)

## 📞 Contact

For questions, suggestions, or collaboration opportunities, please reach out through:

- Email: raymondamoateng@gmail.com
- LinkedIn: [raymond-frimpong](https://www.linkedin.com/in/raymond-frimpong)
- GitHub: [@Magma4](https://github.com/Magma4)

---

⭐ If you find this project helpful, please consider giving it a star!
