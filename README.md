# 3D Product Showcase

A modern, interactive product showcase website featuring 3D hover effects and smooth animations. Built with HTML, CSS, and JavaScript using Bootstrap 5.

## 🌟 Features

- **3D Product Cards**
  - Smooth 3D rotation on hover
  - Interactive perspective effect
  - Front and back views
  - Image zoom effect

- **Interactive Elements**
  - Mouse-tracking 3D rotation
  - Smooth scrolling navigation
  - Section fade-in animations
  - Responsive design

- **Modern Design**
  - Gradient backgrounds
  - Clean typography
  - Shadow effects
  - Smooth transitions

- **Responsive Layout**
  - Works on all devices
  - Adaptive card sizes
  - Mobile-friendly navigation

## 🛠️ Technologies Used

- HTML5
- CSS3 (with 3D transforms)
- JavaScript (ES6+)
- Bootstrap 5
- Font Awesome Icons

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/3D-product-showcase.git
```

2. Navigate to the project directory:
```bash
cd 3D-product-showcase
```

3. Open `index.html` in your web browser

## 💻 Usage

1. Replace the product images in `index.html` with your own:
```html
<img src="your-image-url" alt="Product Name">
```

2. Update product information:
```html
<div class="product-back">
    <h3>Your Product Name</h3>
    <p>Your product description</p>
    <button class="btn btn-primary">Learn More</button>
</div>
```

3. Customize colors in `styles.css`:
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
}
```

## 🎨 Customization

### Colors
- Primary gradient: `linear-gradient(135deg, #667eea 0%, #764ba2 100%)`
- Text colors: `#333` for headings, `#666` for body text

### Animations
- Card rotation: 0.8s transition
- Image zoom: 0.3s transition
- Section fade-in: 0.6s animation

### Layout
- Product cards: 400px height (300px on mobile)
- Container width: Bootstrap's default container

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 📱 Responsive Breakpoints

- Mobile: < 768px
- Tablet: 768px - 992px
- Desktop: > 992px

## 🔧 CSS 3D Properties Used

```css
perspective: 1000px;
transform-style: preserve-3d;
backface-visibility: hidden;
transform: rotateY(180deg);
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

Your Name
- GitHub: [@yourusername]((https://github.com/shrfr))
- Email: shreya2005b@gmail.com

## 🙏 Acknowledgments

- [Bootstrap](https://getbootstrap.com/)
- [Font Awesome](https://fontawesome.com/)
- [Unsplash](https://unsplash.com/) for product images 
