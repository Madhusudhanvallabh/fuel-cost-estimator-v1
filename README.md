# 🚗 Fuel Cost Calculator

A modern, responsive web application for calculating trip fuel costs and toll expenses. Track your travel expenses efficiently with a beautiful, user-friendly interface.

## 🌐 Live Demo

Visit the calculator: **[https://your-username.github.io/fuel-cost-calculator](https://your-username.github.io/fuel-cost-calculator)**

## ✨ Features

- **💰 Cost Calculation**: Calculate fuel costs based on distance, fuel price, and vehicle mileage
- **🛣️ Toll Support**: Include toll costs in your trip calculations
- **📱 Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **📊 Trip History**: Save and track your last 5 trips
- **📋 Copy Results**: Share formatted trip results with one click
- **💾 Local Storage**: Your data persists between browser sessions
- **🎨 Modern UI**: Beautiful gradient background with glass-morphism design
- **⚡ Real-time Calculation**: Results update automatically as you type

## 🚀 Quick Start

1. **Visit the Website**: Open [your-calculator-url] in any web browser
2. **Enter Trip Details**:
   - Distance in kilometers
   - Fuel price per liter
   - Vehicle mileage (km/L)
   - Optional: Number of tolls and toll fees
3. **Get Results**: See fuel required, costs, and cost per kilometer
4. **Save Trip**: Save your calculation to history for future reference
5. **Copy & Share**: Use the copy button to share formatted results

## 📊 Calculation Formula

The calculator uses these formulas:

- **Fuel Required** = Distance ÷ Vehicle Mileage
- **Fuel Cost** = Fuel Required × Fuel Price
- **Toll Cost** = Number of Tolls × Toll Fee per Toll
- **Total Cost** = Fuel Cost + Toll Cost
- **Cost per KM** = Total Cost ÷ Distance

## 🛠️ For Developers

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fuel-cost-calculator.git
   cd fuel-cost-calculator
   ```

2. Open `index.html` in your browser or serve it using a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

3. Open your browser and navigate to `http://localhost:8000`

### Project Structure

```
fuel-cost-calculator/
├── index.html          # Main application file
├── README.md           # Project documentation
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Pages deployment
```

### Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox/Grid, gradients, and backdrop-filter
- **Vanilla JavaScript**: No frameworks or dependencies
- **LocalStorage API**: Data persistence
- **Clipboard API**: Copy functionality

### Key Features Implementation

- **Responsive Design**: CSS Grid and Flexbox for adaptive layouts
- **Glass Morphism**: Backdrop-filter blur effects with transparent backgrounds
- **Local Storage**: Automatic saving and loading of trip history
- **Form Validation**: Real-time input validation and error handling
- **Toast Notifications**: User feedback for actions
- **Progressive Enhancement**: Works even if JavaScript fails

## 🎨 Design Features

- **Gradient Background**: Blue to purple gradient for visual appeal
- **Glass Morphism Cards**: Transparent cards with blur effects
- **Color-Coded Results**: Different colors for fuel, toll, and total costs
- **Responsive Icons**: SVG icons from Heroicons
- **Mobile-First**: Optimized for mobile devices

## 🌟 Browser Support

- Chrome 88+
- Firefox 87+
- Safari 14+
- Edge 88+

## 📱 Mobile Experience

The calculator is fully optimized for mobile devices with:
- Touch-friendly interface
- Responsive typography
- Optimized input fields
- Mobile-specific interactions

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Make your changes
4. Test thoroughly on different devices
5. Commit with clear messages: `git commit -m "Add feature description"`
6. Push to your fork: `git push origin feature-name`
7. Create a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Icons by [Heroicons](https://heroicons.com/)
- Inspired by modern web design principles
- Built with accessibility and performance in mind

## 📞 Support

If you encounter any issues or have suggestions:

1. Check existing [Issues](https://github.com/your-username/fuel-cost-calculator/issues)
2. Create a new issue with detailed information
3. Include browser version and steps to reproduce

---

**Made with ❤️ for travelers who want to track their fuel costs efficiently**