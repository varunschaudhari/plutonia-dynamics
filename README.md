# Plutonia Dynamics - Professional Business Website

A complete, modern, fully responsive multi-page website for Plutonia Dynamics - a leading manufacturer of Storage Racks and Material Handling Solutions in Pune, India.

## 🌟 Features

- **6 Complete Pages**: Home, About, Products, Services, Testimonials, Contact
- **Modern Design**: Clean, professional industrial look with gradient effects
- **Fully Responsive**: Works perfectly on mobile, tablet, and desktop
- **Smooth Animations**: AOS.js scroll animations throughout
- **Interactive Elements**: Testimonials slider, form validation, mobile menu
- **SEO Optimized**: Proper meta tags, semantic HTML, alt texts
- **Fast Loading**: Optimized code and efficient CSS
- **Font Awesome Icons**: Professional icons throughout
- **Google Fonts**: Inter (body) and Poppins (headings)

## 📁 File Structure

```
plutonia-dynamics/
├── index.html              # Home page
├── about.html              # About Us page
├── products.html           # Products page
├── services.html           # Services page
├── testimonials.html       # Testimonials page
├── contact.html            # Contact & Enquiry page
├── css/
│   └── style.css          # Complete stylesheet
├── js/
│   └── main.js            # All JavaScript functionality
├── images/                # Image assets folder
├── logo-no-background.webp # Company logo
└── README.md              # This file
```

## 🎨 Design Specifications

### Color Scheme
- **Primary Blue**: #2563EB / #1E40AF
- **Steel Gray**: #4B5563 / #6B7280
- **Accent Orange**: #F97316
- **Accent Red**: #EF4444
- **White/Off-white**: #FFFFFF / #F9FAFB

### Typography
- **Body Font**: Inter (Google Fonts)
- **Heading Font**: Poppins (Google Fonts)

### Icons
- **Font Awesome 6** (via CDN)

## 🚀 Getting Started

### Option 1: Open Directly
Simply open `index.html` in your web browser.

### Option 2: Local Server (Recommended)
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (http-server)
npx http-server

# PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 📄 Pages Overview

### 1. index.html (Home)
- Hero section with tagline
- Company overview
- Featured products grid (4 products)
- Services highlights
- Testimonials slider
- CTA banner

### 2. about.html (About Us)
- Company history and story
- Mission & values
- Why choose us section
- Location highlight with map

### 3. products.html (Products)
- 6 product categories:
  - Material Handling Trolleys
  - FIFO Storage Rack Systems
  - Heavy-Duty Pallet Racks
  - Cantilever Racks
  - Aluminium Profile Workstations
  - Assembly Line Automation
- Each with image, description, features, and enquiry button

### 4. services.html (Services)
- Product Customization
- Installation Services
- Maintenance & AMC
- Service benefits

### 5. testimonials.html (Testimonials)
- 6 client testimonials with ratings
- Auto-playing slider
- Manual navigation controls
- Stats section

### 6. contact.html (Contact & Enquiry)
- Contact information
- Full enquiry form with validation
- Google Maps embed
- Business hours

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS variables, flexbox, grid
- **Vanilla JavaScript**: No frameworks, pure JS
- **AOS.js**: Animate On Scroll library (CDN)
- **Font Awesome 6**: Icons (CDN)
- **Google Fonts**: Typography (CDN)
- **Unsplash**: High-quality placeholder images (direct links)

## ✨ Key Features

### Navigation
- Sticky header with backdrop blur
- Responsive mobile hamburger menu
- Active page highlighting
- Smooth scrolling

### Animations
- AOS scroll animations
- Hover effects on cards
- Smooth transitions
- Gradient animations

### Forms
- Real-time validation
- Error messages
- Success notifications
- Required field indicators

### Interactive Elements
- Testimonials auto-slider
- Mobile menu toggle
- Floating enquire button (hidden on contact page)
- Smooth scroll to sections

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: < 768px
- **Small Mobile**: < 480px

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📝 Customization

### Update Company Information
Edit contact details in:
- Top bar (all pages)
- Footer (all pages)
- Contact page

### Change Colors
Modify CSS variables in `css/style.css`:
```css
:root {
    --primary-blue: #2563EB;
    --accent-orange: #F97316;
    /* ... */
}
```

### Add/Remove Products
Edit `products.html` to add or modify product cards.

### Update Images
Replace Unsplash URLs with your own images in the HTML files.

## 🔧 Form Functionality

The contact form includes:
- Client-side validation
- Success message display
- Error highlighting
- Required field validation
- Email format validation
- Phone number validation

**Note**: Currently shows success message on submit. To make it functional, connect to a backend service or email service (e.g., Formspree, EmailJS, or your own API).

## 📍 Google Maps

The map uses placeholder coordinates for Pune, Maharashtra. To update:
1. Get your exact location coordinates
2. Update the iframe `src` in `about.html` and `contact.html`
3. Or use Google Maps Embed API with your address

## 🚀 Deployment

### Static Hosting Options
- **Netlify**: Drag and drop the folder
- **Vercel**: Connect GitHub repo
- **GitHub Pages**: Push to repository
- **Any Web Server**: Upload all files

### Before Deploying
1. Replace placeholder images with actual product photos
2. Update contact information
3. Update Google Maps coordinates
4. Connect form to backend/email service
5. Update social media links
6. Test all pages and functionality

## 📞 Support

For questions or customization help, refer to the code comments or contact the development team.

## 📄 License

© 2026 Plutonia Dynamics. All rights reserved.

---

**Built with ❤️ for Plutonia Dynamics**
