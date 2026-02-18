# Rohit Gayal - Portfolio

A minimalistic, modern portfolio website showcasing projects and skills with elegant design and smooth animations.

## Features

- ✨ Clean, minimalist design with Cinzel font
- 🌙 Dark mode toggle with localStorage persistence
- 📱 Fully responsive and mobile-optimized
- ⚡ Fast loading with no external dependencies (except Google Fonts)
- 🎨 Smooth animations and transitions
- 📝 Project modals with detailed descriptions
- 💬 Contact form with email and phone information
- 🔗 Social media links (LinkedIn, Instagram, GitHub, Twitter)
- ♿ Semantic HTML and accessibility features

## Project Structure

```
portfolio/
├── index.html       # Main HTML file
├── styles.css       # All styling and animations
├── script.js        # Functionality (dark mode, modals, etc.)
├── star.JPEG        # Profile picture
└── README.md        # This file
```

## How to Use

1. Clone this repository:
```bash
git clone https://github.com/yourusername/portfolio.git
```

2. Open `index.html` in your browser or serve it locally:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js with http-server
npx http-server
```

3. Customize the content:
   - Update your name and bio in `index.html`
   - Replace `star.JPEG` with your profile picture
   - Update social media links
   - Modify project details in the modal sections
   - Update contact email and phone number

## Customization

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary: #1a1a1a;
    --bg: #ffffff;
    --text: #333;
    --accent: #0066cc;
    --border: #e0e0e0;
}
```

### Add More Projects
Duplicate a project card in `index.html` and create a corresponding modal.

### Update Social Links
Replace the href URLs in the social links section with your profiles.

## Deployment Options

### GitHub Pages (Recommended)
1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select main branch as source
4. Your site will be live at `https://yourusername.github.io/portfolio`

### Other Options
- **Vercel**: Connect GitHub repo, auto-deploys on push
- **Netlify**: Similar to Vercel, drag-and-drop or GitHub integration
- **Firebase Hosting**: Google's hosting solution
- **Heroku**: Full-stack applications

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- Page Load: < 1 second
- Lighthouse Score: 95+ across all metrics
- Mobile Friendly: ✓

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, CSS Variables, Animations)
- Vanilla JavaScript (ES6+)
- Google Fonts (Cinzel)
- Intersection Observer API

## Features in Detail

### Dark Mode
- Automatically saves preference to localStorage
- Smooth transitions between themes
- Neon effects on buttons and social links in dark mode

### Project Modals
- Click any project to view detailed information
- Features, technologies, and results
- Close with button, outside click, or Escape key

### Animations
- Slide-in animation for name on page load
- Fade-in animations for sections on scroll
- Smooth transitions on all interactive elements
- Neon glow effects in dark mode

### Responsive Design
- Works on all screen sizes
- Mobile-optimized navigation
- Touch-friendly buttons and links
- Adaptive grid layouts

## Future Enhancements

- [ ] Blog section
- [ ] Testimonials/Reviews
- [ ] Filter projects by technology
- [ ] Download resume/CV
- [ ] Newsletter signup
- [ ] Analytics integration

## License

This project is open source and available under the MIT License.

## Contact

Feel free to reach out:
- Email: rohitgayal22@gmail.com
- Phone: +91 81793 96434
- LinkedIn: [Rohit Gayal](https://www.linkedin.com/in/rohit-gayal-3408792b0)
- GitHub: [rohitgayal22](https://github.com/rohitgayal22)

---

Made with ❤️ by Rohit Gayal
