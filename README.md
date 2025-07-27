# 🌍 Global Glimpse - Your Gateway to World News

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/UdayDey0909/Global-Glimpse-News-Website)](https://github.com/UdayDey0909/Global-Glimpse-News-Website/commits/main)
[![Issues](https://img.shields.io/github/issues/UdayDey0909/Global-Glimpse-News-Website)](https://github.com/UdayDey0909/Global-Glimpse-News-Website/issues)
[![Stars](https://img.shields.io/badge/github-stars-yellow)](https://github.com/UdayDey0909/Global-Glimpse-News-Website/stargazers)
[![Forks](https://img.shields.io/badge/github-forks-blue)](https://github.com/UdayDey0909/Global-Glimpse-News-Website/network/members)

<div align="center">
  <img src="src/public/icon.png" alt="Global Glimpse Logo" width="120" height="120">
  <h3>Stay Informed, Stay Empowered</h3>
  <p>Your daily dose of global news, empowering stories, and insights to help you stay ahead in a rapidly changing world.</p>
</div>

---

## 📸 Live Preview

### 🏠 Homepage Preview
<div align="center">
  <img src="src/assets/HomePage-Preview.jpeg" alt="Global Glimpse Homepage" width="800" style="border-radius: 10px; box-shadow: 0 4px 20px rgba(0,0,0,0.1);">
  <p><em>Main homepage with news categories and featured articles</em></p>
</div>

### 📄 Page Preview
<div align="center">
  <img src="src/assets/Page-Preview.jpeg" alt="Global Glimpse Page Layout" width="800" style="border-radius: 10px; box-shadow: 0 4px 20px rgba(0,0,0,0.1);">
  <p><em>Detailed page layout showing article display and navigation</em></p>
</div>

### 🔄 Application Flow Diagram
<div align="center">
  <img src="src/assets/Flow-Diagram.png" alt="Global Glimpse Application Flow" width="800" style="border-radius: 10px; box-shadow: 0 4px 20px rgba(0,0,0,0.1);">
  <p><em>Complete application flow and user journey</em></p>
</div>

---

## ✨ Features

### 🎯 Core Features

- **📰 Live News Feed** - Real-time articles from trusted sources worldwide
- **🏷️ Category Navigation** - Browse news by Business, Entertainment, Technology, Health, Sports, and Science
- **🔍 Smart Search** - Find articles by keywords with instant results
- **📱 Responsive Design** - Perfect experience on mobile, tablet, and desktop
- **🌙 Dark/Light Mode** - Toggle between themes for comfortable reading
- **⚡ Fast Loading** - Optimized performance with smooth animations

### 🎨 User Experience

- **🎭 Interactive UI** - Hover effects, smooth transitions, and engaging animations
- **📊 News Statistics** - Track article counts and source credibility
- **📧 Newsletter Subscription** - Stay updated with email notifications
- **🔗 Social Media Integration** - Share articles across platforms
- **📖 Read More Options** - Extended content and related articles

### 🛡️ Quality & Trust

- **✅ Verified Sources** - 99% trusted news sources
- **📈 Daily Updates** - 500+ articles published daily
- **🔒 Privacy Focused** - No tracking, clean browsing experience
- **🌐 Global Coverage** - News from around the world

---

## 🚀 Quick Start

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for API access
- Optional: Local development server

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/UdayDey0909/Global-Glimpse-News-Website.git
   cd Global-Glimpse-News-Website
   ```

2. **API Key Setup** (Optional - Free key included)

   ```bash
   # A free NewsAPI key is already included for quick testing
   # If you want to use your own key, register at https://newsapi.org/
   # and replace the key in src/data/config.js
   ```

3. **Launch the application**

   ```bash
   # Option 1: Open index.html directly in your browser
   # Option 2: Use a local server (recommended)
   npx live-server
   # or
   python -m http.server 8000
   # or
   php -S localhost:8000
   ```

4. **Access the application**

   ```
   Open your browser and navigate to:
   http://localhost:8000 (if using local server)
   or simply open index.html in your browser
   ```

---

## 🔒 Security Considerations

### API Key Management

ℹ️ **Note**: A free NewsAPI key is included for demonstration purposes, allowing users to test the project immediately without registration.

⚠️ **For Production Use**: The current implementation exposes the API key in client-side code. Consider:

1. **Use Environment Variables**: Store API keys in environment variables
2. **Backend Proxy**: Create a backend service to handle API calls
3. **Rate Limiting**: Implement rate limiting to prevent abuse
4. **CORS Configuration**: Properly configure CORS for production

### Best Practices

- Never commit API keys to version control
- Use HTTPS in production
- Implement proper error handling
- Validate user inputs

---

## 🛠️ Troubleshooting

### Common Issues

#### 1. **API Rate Limit Exceeded**
```
Error: "rateLimited" or "429 Too Many Requests"
```
**Solution**: 
- The included free API key has a 1000 requests/day limit
- Register for your own free key at https://newsapi.org/ for personal use
- Implement caching for repeated requests
- Consider upgrading your API plan for higher limits

#### 2. **Images Not Loading**
```
Error: CORS policy blocking images
```
**Solution**:
- Use a proxy service for images
- Implement fallback images
- Check image URLs for validity

#### 3. **Search Not Working**
```
Error: Search results empty
```
**Solution**:
- The included API key has rate limits (1000 requests/day for free tier)
- If you hit the limit, register for your own key at https://newsapi.org/
- Check network connectivity
- Ensure search query is not empty

#### 4. **Dark Mode Not Persisting**
```
Error: Theme resets on page refresh
```
**Solution**:
- Check localStorage is enabled
- Verify JavaScript is running
- Clear browser cache

### Browser Compatibility

| Browser | Version | Status            |
| ------- | ------- | ----------------- |
| Chrome  | 90+     | ✅ Full Support    |
| Firefox | 88+     | ✅ Full Support    |
| Safari  | 14+     | ✅ Full Support    |
| Edge    | 90+     | ✅ Full Support    |
| IE      | 11      | ⚠️ Limited Support |

---

## 📁 Project Structure

```
Global-Glimpse/
├── 📄 index.html                 # Main entry point with auto-redirect
├── 📖 README.md                  # Project documentation
├── 📁 src/                       # Source code directory
│   ├── 📁 pages/                 # HTML pages
│   │   ├── 🏠 HomePage.html      # Main homepage
│   │   ├── 💼 Business.html      # Business news
│   │   ├── 🎭 Entertainment.html # Entertainment news
│   │   ├── 💻 Technology.html    # Technology news
│   │   ├── 🏥 Health.html        # Health news
│   │   ├── ⚽ Sports.html         # Sports news
│   │   ├── 🔬 Science.html       # Science news
│   │   ├── 📰 topNews.html       # Top trending news
│   │   ├── 🆕 latestNews.html    # Latest news
│   │   ├── 👤 forYou.html        # Personalized news
│   │   ├── 🔍 searchResult.html  # Search results
│   │   ├── 🤝 partnerships.html  # Partnership information
│   │   ├── 📋 privacyPolicy.html # Privacy policy
│   │   ├── 📜 Terms&Conditions.html # Terms and conditions
│   │   └── ⚖️ Disclaimer.html    # Legal disclaimer
│   ├── 🎨 css/                   # Stylesheets
│   │   ├── 🏠 HomePage.css       # Homepage styles
│   │   ├── 🎨 style.css          # Global styles
│   │   ├── 🧭 nav.css            # Navigation styles
│   │   └── 📰 blog.css           # Article styles
│   ├── ⚡ js/                     # JavaScript files
│   │   ├── 🏠 script.js          # Main functionality
│   │   ├── 💼 Business.js        # Business page logic
│   │   ├── 🎭 Entertainment.js   # Entertainment page logic
│   │   ├── 💻 Technology.js      # Technology page logic
│   │   ├── 🏥 Health.js          # Health page logic
│   │   ├── ⚽ Sports.js           # Sports page logic
│   │   ├── 🔬 Science.js         # Science page logic
│   │   ├── 📰 topNews.js         # Top news logic
│   │   ├── 🆕 latestNews.js      # Latest news logic
│   │   ├── 👤 forYou.js          # Personalized news logic
│   │   └── 🔍 Search.js          # Search functionality
│   ├── ⚙️ data/                   # Configuration
│   │   └── ⚙️ config.js          # API configuration
│   ├── 🖼️ assets/                 # Images and media
│   │   ├── 📸 Fallback_Image.jpg
│   │   ├── 🖼️ Mobile_Hero_Section.jpeg
│   │   ├── 🖼️ Newspaper_1.jpg
│   │   ├── 🖼️ Newspaper2.jpg
│   │   ├── 🏠 HomePage-Preview.jpeg
│   │   ├── 📄 Page-Preview.jpeg
│   │   └── 🔄 Flow-Diagram.png
│   └── 🌐 public/                 # Public assets
│       ├── 🖼️ heroSection.jpeg   # Hero background
│       └── 🎯 icon.png           # Website icon
└── 📁 .vscode/                   # VS Code configuration
```

---

## 🛠️ Technologies & Tools

### Frontend Technologies

- **🌐 HTML5** - Semantic markup and structure
- **🎨 CSS3** - Modern styling with Flexbox and Grid
- **⚡ JavaScript (ES6+)** - Dynamic functionality and API integration
- **📱 Responsive Design** - Mobile-first approach

### External APIs & Services

- **📰 NewsAPI.org** - Real-time news data
- **🎨 Boxicons** - Beautiful icon library
- **🌐 Google Fonts** - Typography (Poppins, Roboto)

### Development Tools

- **🔧 VS Code** - Code editor with extensions
- **🚀 Live Server** - Local development server
- **📦 Git** - Version control

---

## 🎯 Key Features Deep Dive

### 📰 News Categories

- **Business** - Market trends, economy, and corporate news
- **Entertainment** - Movies, music, celebrities, and culture
- **Technology** - Tech innovations, startups, and digital trends
- **Health** - Medical breakthroughs, wellness, and healthcare
- **Sports** - Athletic events, teams, and sports analysis
- **Science** - Research discoveries, space, and scientific breakthroughs

### 🔍 Search Functionality

- **Instant Search** - Real-time results as you type
- **Keyword Matching** - Find articles by title, content, or author
- **Filtered Results** - Search within specific categories
- **Search History** - Track your recent searches

### 📱 Responsive Design

- **Mobile-First** - Optimized for smartphones and tablets
- **Desktop Experience** - Full-featured interface for larger screens
- **Touch-Friendly** - Easy navigation on touch devices
- **Fast Loading** - Optimized images and assets

---

## 🚀 Performance & Optimization

### Loading Speed

- **Optimized Images** - Compressed and properly sized
- **Minified CSS/JS** - Reduced file sizes
- **Lazy Loading** - Images load as needed
- **Caching** - Browser caching for faster repeat visits

### SEO Optimization

- **Semantic HTML** - Proper heading structure
- **Meta Tags** - Optimized for search engines
- **Alt Text** - Descriptive image alt attributes
- **Clean URLs** - SEO-friendly page structure

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### 🐛 Reporting Bugs

1. Check existing issues to avoid duplicates
2. Create a detailed bug report with steps to reproduce
3. Include browser version and device information

### 💡 Suggesting Features

1. Open an issue with the "enhancement" label
2. Describe the feature and its benefits
3. Provide mockups or examples if possible

### 🔧 Code Contributions

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

### 📝 Code Style

- Follow existing code formatting
- Add comments for complex logic
- Test your changes thoroughly
- Update documentation if needed

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Uday Dey

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 📞 Support & Contact

### 📧 Get in Touch

- **Email**: [uday-dey-work@gmail.com](mailto:uday-dey-work@gmail.com)
- **LinkedIn**: [Uday Dey](https://www.linkedin.com/in/uday-dey-76a066345/)
- **Twitter**: [@uday_dey_work](https://twitter.com/uday_dey_work)

## 🙏 Acknowledgments

- **NewsAPI.org** for providing reliable news data
- **Boxicons** for the beautiful icon library
- **Google Fonts** for typography
- **Contributors** who help improve this project
- **Users** who provide valuable feedback

---

<div align="center">
  <h3>🌟 Star this repository if you find it helpful!</h3>
  <p>Made with ❤️ by <a href="mailto:uday-dey-work@gmail.com">Uday Dey</a></p>
  <p><em>Stay informed, stay empowered with Global Glimpse!</em></p>
</div>
