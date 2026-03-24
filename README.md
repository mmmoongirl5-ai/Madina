# 💼 Personal CV Website - Madina Muxammadova
 
A beautiful, modern, and responsive personal CV/portfolio website built with pure HTML, CSS, and JavaScript. Features a stunning gradient design, smooth animations, and multi-language support (English, Uzbek, Russian).
 
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
 
## ✨ Features
 
### 🎨 Design & UI
- **Modern Gradient Background** - Beautiful purple gradient with floating animated shapes
- **Responsive Design** - Fully responsive on all devices (mobile, tablet, desktop)
- **Smooth Animations** - Pulse effects, floating shapes, and hover transitions
- **Clean Typography** - Using Google Fonts (Poppins)
- **Glass Morphism Effects** - Modern frosted glass UI elements
 
### 🌍 Multi-Language Support
- **English** 🇬🇧
- **Uzbek (O'zbek)** 🇺🇿
- **Russian (Русский)** 🇷🇺
 
Easily switch between languages with the language selector in the top-right corner.
 
### 📋 Sections
 
1. **Hero Section**
   - Animated profile avatar
   - Name and tagline
   - University badge
   - Call-to-action button
 
2. **About Me**
   - Three feature cards:
     - Passionate Developer 💻
     - Creative Thinker 🎨
     - Goal-Oriented 🎯
   - Detailed bio section
 
3. **Skills**
   - Visual skill bars showing proficiency levels
   - HTML, Figma, AI, Mathematics
 
4. **Contact**
   - Email link 📧
   - LinkedIn profile 💼
   - Telegram contact ✈️
   - Interactive like button ❤️
 
5. **Footer**
   - Copyright information
   - Personal touch (coffee lover ☕)
 
## 🚀 Quick Start
 
### Prerequisites
- A web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, Notepad++)
 
### Installation
 
1. **Clone the repository**
   ```bash
   git clone https://github.com/mmmoongirl5-ai/cv-me-html-u117.git
   ```
 
2. **Navigate to the project folder**
   ```bash
   cd cv-me-html-u117
   ```
 
3. **Open the HTML file**
   - Simply double-click `index.html` (or `CV_Me_class_html.html`)
   - Or open it in your browser
 
**That's it!** No build process, no dependencies, no installation required. 🎉
 
## 📁 Project Structure
 
```
cv-me-html-u117/
├── index.html              # Main HTML file (rename CV_Me_class_html.html to this)
├── README.md               # Project documentation
└── assets/                 # (Optional) Add images, icons, etc.
```
 
## 🛠️ Customization
 
### Change Your Information
 
Edit the HTML file and update:
 
1. **Name & Title**
   ```html
   <h1 data-en="Madina Muxammadova">Your Name</h1>
   <p class="tagline">Your Title/Profession</p>
   ```
 
2. **University Badge**
   ```html
   <div class="university-badge">🎓 Your University Name</div>
   ```
 
3. **Skills**
   ```html
   <div class="skill-name">Your Skill</div>
   <div class="skill-progress" style="width: 70%"></div>
   ```
   Adjust the `width` percentage (0-100%) to match your skill level.
 
4. **Contact Links**
   ```html
   <a href="mailto:your-email@gmail.com">📧</a>
   <a href="https://linkedin.com/in/yourprofile">💼</a>
   <a href="https://t.me/yourusername">✈️</a>
   ```
 
5. **About Me Text**
   Find and replace the bio text in the translations object (lines 480-523).
 
### Change Colors
 
Find the gradient in the CSS:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```
 
Replace with your preferred colors:
- Blue Gradient: `#667eea 0%, #764ba2 100%`
- Green Gradient: `#11998e 0%, #38ef7d 100%`
- Orange Gradient: `#ee0979 0%, #ff6a00 100%`
- Pink Gradient: `#f093fb 0%, #f5576c 100%`
 
## 🌐 Deployment
 
### Deploy to Vercel (Recommended - Free)
 
1. **Push your code to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```
 
2. **Go to [Vercel](https://vercel.com)**
   - Sign up/Login with GitHub
   - Click "New Project"
   - Import your GitHub repository
   - Click "Deploy"
 
**Important:** Make sure to rename `CV_Me_class_html.html` to `index.html` before deploying!
 
### Deploy to Netlify (Alternative - Free)
 
1. **Go to [Netlify](https://netlify.com)**
2. Drag and drop your project folder
3. Your site is live!
 
### Deploy to GitHub Pages (Alternative - Free)
 
1. **Go to your GitHub repository**
2. Click **Settings** → **Pages**
3. Under "Source", select **main branch**
4. Click **Save**
5. Your site will be live at: `https://yourusername.github.io/cv-me-html-u117`
 
## 📱 Browser Compatibility
 
✅ Chrome (latest)  
✅ Firefox (latest)  
✅ Safari (latest)  
✅ Edge (latest)  
✅ Opera (latest)
 
## 🎯 Features Breakdown
 
### Interactive Elements
 
- **Like Button** - Click the heart to like the page (tracks likes in session)
- **Language Switcher** - Switch between EN/UZ/RU instantly
- **Hover Effects** - All buttons and cards have smooth hover animations
- **Smooth Scrolling** - Seamless navigation between sections
 
### Animations
 
- **Floating Shapes** - Background geometric shapes float up and down
- **Pulse Effect** - Profile avatar has a gentle pulsing animation
- **Skill Bars** - Animated progress bars (can be enhanced with scroll triggers)
 
## 🔧 Future Enhancements
 
Possible improvements you could add:
 
- [ ] Add a dark/light theme toggle
- [ ] Add a projects/portfolio section
- [ ] Implement a contact form with backend
- [ ] Add more animations (scroll-triggered)
- [ ] Add downloadable PDF resume
- [ ] Add blog section
- [ ] Integrate with analytics (Google Analytics)
- [ ] Add testimonials section
- [ ] Add education timeline
- [ ] Add work experience section
 
## 📄 License
 
This project is licensed under the MIT License - feel free to use it for your own portfolio!
 
## 👤 Author
 
**Madina Muxammadova**
 
- Email: [mmmoongirl5@gmail.com](mailto:mmmoongirl5@gmail.com)
- LinkedIn: [Madina Muxammadova](https://www.linkedin.com/in/madina-muxammadova-74bba3389/)
- Telegram: [@Muxammadova570](https://t.me/Muxammadova570)
 
## 🙏 Acknowledgments
 
- Google Fonts for the beautiful Poppins font
- CSS Gradient inspiration from [uiGradients](https://uigradients.com)
- Emoji icons from Unicode standard
 
## 💬 Contributing
 
Found a bug or have a suggestion? Feel free to:
1. Open an issue
2. Submit a pull request
3. Contact me directly
 
## ⭐ Show Your Support
 
If you like this project, please give it a ⭐ on GitHub!
 
---
 
**Built with passion and coffee ☕**
 
*Last updated: March 2026*
