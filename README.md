# BLACKEM LLC - Premium Chauffeur Service Website

A modern, responsive website for BLACKEM LLC, a luxury chauffeur service company. Built with HTML5, CSS3, and JavaScript, featuring a professional design that reflects the premium nature of the service.

## 🌟 Features

### Design & User Experience
- **Modern Luxury Design**: Elegant black and gold color scheme with premium typography
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Subtle animations and transitions for enhanced user experience
- **Professional Typography**: Uses Playfair Display for headings and Inter for body text
- **Interactive Elements**: Hover effects, form interactions, and smooth scrolling

### Sections
1. **Hero Section**: Eye-catching landing area with call-to-action
2. **About Us**: Company information with feature highlights
3. **Services**: Five main service offerings with icons and descriptions
4. **Booking Form**: Comprehensive booking system with validation
5. **Contact**: Contact information and contact form
6. **Footer**: Company information and quick links

### Technical Features
- **Mobile-First Design**: Responsive navigation with hamburger menu
- **Form Validation**: Client-side validation for booking and contact forms
- **Smooth Scrolling**: Anchor link navigation with smooth scrolling
- **Intersection Observer**: Scroll-triggered animations
- **Performance Optimized**: Debounced scroll events and optimized animations
- **Accessibility**: Keyboard navigation and screen reader friendly

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation
1. Clone or download the project files
2. Open `index.html` in your web browser
3. The website is ready to use!

### File Structure
```
ShirinAvez/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
└── bucket-policy.json  # AWS bucket policy (existing)
```

## 📱 Responsive Design

The website is fully responsive and optimized for:
- **Desktop**: 1200px+ (Full layout with side-by-side sections)
- **Tablet**: 768px - 1199px (Adjusted grid layouts)
- **Mobile**: < 768px (Stacked layout with mobile navigation)

## 🎨 Design System

### Colors
- **Primary Gold**: `#d4af37` (Luxury accent color)
- **Dark Gold**: `#b8941f` (Button hover states)
- **Black**: `#1a1a1a` (Footer background)
- **Light Gray**: `#f8f9fa` (Section backgrounds)
- **Text Gray**: `#666` (Secondary text)

### Typography
- **Headings**: Playfair Display (Serif)
- **Body Text**: Inter (Sans-serif)
- **Font Weights**: 300, 400, 500, 600, 700

### Icons
- Font Awesome 6.0.0 for all icons
- Consistent icon styling with gold accent color

## 🔧 Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-gold: #d4af37;
    --dark-gold: #b8941f;
    --black: #1a1a1a;
    --light-gray: #f8f9fa;
    --text-gray: #666;
}
```

### Adding New Services
1. Add a new service card in the services section of `index.html`
2. Include appropriate Font Awesome icon
3. Update the booking form service options

### Modifying Content
- Edit text content directly in `index.html`
- Update contact information in both contact section and footer
- Modify form fields as needed

## 📧 Form Functionality

### Booking Form
- **Fields**: Pickup/drop-off locations, date, time, service type, passengers, contact info
- **Validation**: Required field validation
- **Submission**: Simulated API call with success message

### Contact Form
- **Fields**: Name, email, subject, message
- **Validation**: Required field validation
- **Submission**: Simulated API call with success message

## 🌐 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📄 License

This project is created for BLACKEM LLC. All rights reserved.

## 🤝 Support

For technical support or customization requests, please contact the development team.

---

**BLACKEM LLC** - Professional. Punctual. Premium. 