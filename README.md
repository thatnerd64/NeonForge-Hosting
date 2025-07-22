# C+N Hosting Website

A modern, pay-as-you-go web hosting website featuring affordable plans starting at just $0.50/month. Built for gamers, small projects, Discord bots, and anyone who needs simple, reliable hosting without enterprise pricing.

## 🎨 Design Features

- **Minimalist Design**: Clean, modern interface with black background
- **Neon Accents**: Orange (#FF8C00) and pink (#FFB6C1) highlights for visual appeal  
- **Responsive Layout**: Fully responsive design that works on all devices
- **Interactive Elements**: Smooth animations, hover effects, and visual feedback
- **Professional Branding**: C+N Hosting branding with custom logo design
- **Accessibility**: Built with Atkinson Hyperlegible font for better readability

## 🚀 Quick Start

### Prerequisites
- Node.js (version 14 or higher)

### Installation & Running

1. **Clone or download the project files**

2. **Start the local server:**
   ```bash
   node server.js
   ```

3. **Open your browser and navigate to:**
   ```
   http://localhost:3000
   ```

### Alternative: Using npm
```bash
npm start
```

## 📁 Project Structure

```
cn-hosting-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── server.js           # Local development server
├── package.json        # Project configuration
└── README.md           # This file
```

## 🎯 Website Sections

1. **Hero Section**: Eye-catching introduction with animated server icons and "Pay As You Go" messaging
2. **Who We Are For**: Targeted audience section highlighting gamers, small projects, and developers
3. **Services**: Four simple plans (LFIT, Starter, Growing, Pro) with clear feature lists
4. **Pricing**: Four transparent pricing tiers ($0.50, $2, $5, $10 per month) with no hidden fees
5. **Contact**: Smart contact form with plan selection auto-fill and Discord/email support
6. **Disclaimer**: Honest transparency about being a small operation, including uptime limitations
7. **Footer**: Quick links, support options, and social connections

## 🎨 Customization

### Colors
The website uses a consistent color scheme:
- **Primary**: Black (#000000) background
- **Accent**: Orange (#FF8C00) and Pink (#FFB6C1)
- **Success**: Green (#00ff88) for highlights and CTAs
- **Text**: White (#ffffff) and light gray (#cccccc)

### Fonts
- **Primary**: Atkinson Hyperlegible (Google Fonts) - chosen for excellent readability
- **Icons**: Font Awesome 6.0

### Key Features to Customize
- Company information in the contact section
- Pricing plans and features
- Service descriptions
- Logo and branding elements

## 📱 Responsive Design

The website is fully responsive and includes:
- Mobile-first design approach
- Hamburger menu for mobile navigation
- Optimized layouts for tablets and phones
- Touch-friendly interactive elements

## 🔧 Technical Features

- **Smart Form Auto-fill**: Clicking pricing plans auto-fills contact form with:
  - Plan selection in subject line
  - Email persistence using localStorage
  - Intelligent field focusing based on what's empty
  - Visual highlighting of fields needing attention
  - Pre-filled message templates
- **Smooth Scrolling**: Navigation links smoothly scroll to sections
- **Form Validation**: Contact form with email validation and persistence
- **Animations**: Intersection Observer for scroll-triggered animations
- **Mobile Navigation**: Auto-hiding navbar on scroll with hamburger menu
- **Loading Animations**: Smooth page load transitions
- **Notification System**: User-friendly feedback messages
- **Typing Effect**: Animated hero title on page load

## 🌐 Deployment

To deploy this website:

1. **Static Hosting** (Recommended):
   - Upload `index.html`, `styles.css`, and `script.js` to any static hosting service
   - Services: Netlify, Vercel, GitHub Pages, AWS S3, etc.

2. **Node.js Hosting**:
   - Deploy with the included `server.js` to platforms like Heroku, Railway, or DigitalOcean

## 📞 Support

For questions or support, please contact:
- Discord: that_neon
- Email: baconsgigaserver@gmail.com
- Discord Server: https://discord.gg/FVTtydJ965

## 📄 License

This project is licensed under the MIT License.

## 💡 Special Features

### Email Auto-fill System
When users click on a pricing plan's "Choose Plan" button:
1. The contact form subject is automatically filled with the selected plan details
2. If the user has previously submitted the form, their email is saved and can be reused
3. Empty fields are highlighted with a green pulsing animation
4. Smart focus management guides users through the form
5. Pre-filled message templates for quick inquiries

### Target Audience Focus
The website specifically caters to:
- **Gamers** needing affordable game servers
- **Small Projects** requiring simple hosting without complexity
- **Developers** needing testing environments or portfolio hosting

### Pricing Philosophy
- No contracts
- No hidden fees
- Pay only for what you use
- Start at just $2/month
- Scale up when needed

---

**C+N Hosting** - Simple, Affordable Hosting for Real People