# TaskFlow - Modern Project Management Landing Page

A modern, responsive SaaS landing page for TaskFlow, a project management tool designed for modern teams. Built with vanilla HTML, CSS, and JavaScript.

![TaskFlow Preview](https://img.shields.io/badge/Status-Live-brightgreen) ![License](https://img.shields.io/badge/License-MIT-blue) ![Version](https://img.shields.io/badge/Version-1.0.0-purple)

## 🚀 Features

### Landing Page Components
- **Animated Hero Section** - Eye-catching entrance animations with floating elements
- **Features Section** - 6 feature cards with custom SVG icons
- **Pricing Section** - 3-tier pricing (Free $0, Pro $19/mo, Team $49/mo) with Stripe integration
- **Testimonials** - 3 customer reviews with star ratings
- **FAQ Accordion** - 5 expandable questions with smooth animations
- **Contact Form** - Email validation and submission handling
- **Newsletter Signup** - Mailchimp-style UI with success states

### Technical Features
- 🌓 **Dark/Light Mode** - System preference detection with manual toggle
- 📱 **Fully Responsive** - Mobile-first design that works on all devices
- ✨ **Smooth Animations** - Scroll-triggered animations and micro-interactions
- ⚡ **Performance Optimized** - Minimal dependencies, fast load times
- ♿ **Accessible** - ARIA labels, keyboard navigation, semantic HTML
- 🎨 **CSS Custom Properties** - Easy theming and customization

## 📁 Project Structure

taskflow-landing/
├── index.html          # Main landing page
├── report.html         # Build report with project details
├── style.css           # All styles with CSS custom properties
├── script.js           # JavaScript functionality
└── README.md           # Project documentation

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/taskflow-landing.git
   ```

2. **Navigate to the project**
   ```bash
   cd taskflow-landing
   ```

3. **Open in browser**
   - Simply open `index.html` in your preferred browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve
     ```

## 🎨 Customization

### Theme Colors
Edit the CSS custom properties in `style.css`:

```css
:root {
  --color-primary: #6366f1;
  --color-primary-dark: #4f46e5;
  --color-secondary: #10b981;
  --color-accent: #f59e0b;
}
```

### Pricing Plans
Update the pricing cards in `index.html` to modify:
- Plan names and descriptions
- Pricing amounts
- Feature lists
- Stripe payment links

### Content
All content is in `index.html` - simply edit the text within the HTML tags.

## 💳 Stripe Integration

The pricing cards include Stripe payment button placeholders. To activate:

1. Create a Stripe account at [stripe.com](https://stripe.com)
2. Create products and pricing in your Stripe dashboard
3. Generate payment links for each plan
4. Replace the `href="#"` in the pricing buttons with your Stripe payment links

```html
<a href="https://buy.stripe.com/your-link" class="btn btn-primary btn-block">
    Get Started
</a>
```

## 📧 Form Handling

### Contact Form
The contact form currently logs submissions to the console. To enable actual submissions:

1. **Using a service like Formspree:**
   ```html
   <form action="https://formspree.io/f/yourcode" method="POST">
   ```

2. **Using your own backend:**
   Update the `handleContactSubmit` function in `script.js`

### Newsletter Signup
Similar setup - integrate with your email service provider:
- Mailchimp
- ConvertKit
- SendGrid
- Custom API

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

## 📱 Responsive Breakpoints

```css
/* Mobile: Default */
/* Tablet: 768px */
/* Desktop: 1024px */
/* Large Desktop: 1280px */
```

## ⚡ Performance

- **No external JS frameworks** - Vanilla JavaScript only
- **Single CSS file** - No CSS frameworks, custom built
- **Optimized animations** - Uses CSS transforms and opacity for 60fps
- **Lazy loading ready** - Structure supports image lazy loading
- **Minimal DOM manipulation** - Efficient JavaScript patterns

## 📊 Build Report

Visit `/report.html` to view:
- Complete file listing
- AI crew members used in development
- Token usage and costs
- Deployment information
- Build statistics

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Inter Font](https://fonts.google.com/specimen/Inter) - Beautiful typeface by Rasmus Andersson
- [Heroicons](https://heroicons.com/) - SVG icon inspiration
- Design inspired by modern SaaS landing pages

## 📞 Support

For support, email support@taskflow.app or open an issue in this repository.

---

Built with ❤️ for modern teams everywhere.