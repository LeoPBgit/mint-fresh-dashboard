# Mint Fresh - Business Dashboard

A modern, responsive business dashboard application built with vanilla HTML, CSS, and JavaScript. Features a complete authentication system and interactive data visualizations.

![Mint Fresh Dashboard](https://img.shields.io/badge/Status-Production%20Ready-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🚀 Live Demo

**🌐 [View Live Demo](https://leopbgit.github.io/mint-fresh-dashboard/)**

*Note: GitHub Pages may take a few minutes to deploy. If the link doesn't work immediately, please wait 5-10 minutes and try again.*

Alternatively, you can download and open `mint-fresh-app.html` in your browser locally.

## 🔐 Login Credentials

Use any of these credentials to access the dashboard:

| Role  | Email | Password |
|-------|-------|----------|
| Admin | `admin@mintfresh.com` | `admin123` |
| Demo  | `demo@mintfresh.com` | `demo123` |
| User  | `user@mintfresh.com` | `user123` |
| Test  | `test@example.com` | `password123` |

## ✨ Features

### 🔒 Authentication System
- **Credential Validation**: Secure login with predefined accounts
- **Error Handling**: User-friendly error messages with helpful suggestions
- **Form Validation**: Prevents submission with empty fields
- **Visual Feedback**: Shake animation for login errors

### 📊 Dashboard Interface
- **Statistics Cards**: Key business metrics with trend indicators
- **Interactive Charts**: Revenue trends and sales category breakdowns
- **Data Tables**: Recent orders with status tracking
- **Responsive Design**: Mobile-first approach with collapsible sidebar
- **Search Functionality**: Global search with focus animations

### 🎨 Design System
- **Modern Color Palette**: OKLCH-based color system for better perceptual uniformity
- **Typography**: Google Fonts integration (Poppins, Merriweather, JetBrains Mono)
- **Animations**: Smooth transitions and micro-interactions
- **Accessibility**: Semantic HTML and keyboard navigation support

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js for data visualization
- **Icons**: Lucide Icons
- **Styling**: Custom CSS with Tailwind CSS utilities
- **Fonts**: Google Fonts

## 📁 Project Structure

```
mint-fresh-dashboard/
├── mint-fresh-app.html          # Main application file
├── .superdesign/                # Original design iterations
│   └── design_iterations/
│       ├── dashboard_1.html     # Original dashboard
│       ├── login_1.html         # Original login
│       └── login_theme_1.css    # Design system tokens
├── memory-bank/                 # Project documentation
│   ├── projectbrief.md         # Project overview
│   ├── productContext.md       # Product requirements
│   ├── techContext.md          # Technical specifications
│   ├── systemPatterns.md       # Architecture patterns
│   ├── activeContext.md        # Current project state
│   └── progress.md             # Development progress
└── README.md                   # This file
```

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/LeoPBgit/mint-fresh-dashboard.git
   cd mint-fresh-dashboard
   ```

2. **Open the application**
   ```bash
   # Option 1: Open directly in browser
   open mint-fresh-app.html
   
   # Option 2: Serve with a local server (recommended)
   python -m http.server 8000
   # Then visit http://localhost:8000/mint-fresh-app.html
   ```

3. **Login with demo credentials**
   - Use any of the provided credentials above
   - Explore the dashboard features

## 🎯 Key Components

### Login Screen
- Clean, professional authentication interface
- Form validation with real-time feedback
- Smooth animations and transitions
- Responsive design for all devices

### Dashboard
- **Revenue Overview**: Interactive line chart showing monthly trends
- **Sales by Category**: Doughnut chart with category breakdown
- **Statistics Cards**: Key metrics with trend indicators
- **Recent Orders**: Data table with status tracking
- **Navigation**: Organized sidebar with main and management sections

## 🔧 Customization

### Colors
The application uses a sophisticated OKLCH-based color system. Modify colors in the CSS custom properties:

```css
:root {
  --primary: oklch(0.65 0.15 180);
  --secondary: oklch(0.95 0.03 180);
  --background: oklch(0.98 0.02 180);
  /* ... more color tokens */
}
```

### Data
Update chart data and statistics by modifying the JavaScript objects in `mint-fresh-app.html`:

```javascript
// Revenue chart data
data: [18500, 19200, 18700, 17500, 22000, 24500, ...]

// Statistics cards
{ title: 'Total Revenue', value: '$24,780', trend: '+12%' }
```

## 📱 Responsive Design

The application is fully responsive with breakpoints at:
- **Mobile**: < 640px (single column layout)
- **Tablet**: 640px - 768px (collapsed sidebar)
- **Desktop**: > 768px (full layout)

## 🔮 Future Enhancements

- [ ] Backend API integration
- [ ] Real-time data updates
- [ ] Additional dashboard pages
- [ ] User management system
- [ ] Export functionality
- [ ] Dark mode toggle
- [ ] Advanced filtering and search

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Design inspiration from modern business dashboard interfaces
- Chart.js for excellent data visualization capabilities
- Lucide for beautiful, consistent icons
- Google Fonts for typography

---

**Built with ❤️ for modern web experiences**
