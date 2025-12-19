# 🎄 Christmas Invitation Website

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen.svg)](https://christmas-invitation-website.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> A festive and interactive web-based invitation platform for Christmas celebrations, featuring countdown timer, video invitations, photo galleries, and RSVP functionality.

![Christmas Invitation Preview](https://github.com/danielwidhiarto/ChristmasInvitationWebsite/blob/main/assets/background.jpeg?raw=true)

## 🌟 Features

### 🎅 Core Features

- **⏰ Live Countdown Timer**: Real-time countdown to the Christmas celebration using Simply Countdown library
- **🎬 Video Invitation**: Embedded video player for personalized invitation messages
- **📸 Photo Galleries**: Interactive carousel galleries showcasing pre-event activities:
  - Diakonia charity activities
  - Visits to sick congregation members
  - Other community service events
- **📝 RSVP Form**: Comprehensive attendance confirmation system with family member categories:
  - PKB/PKP/PKLU (Adult members)
  - PA (Youth members)
  - PT/GP (Children members)
- **🎵 Background Music**: Auto-playing background audio for festive atmosphere
- **📱 Responsive Design**: Fully mobile-friendly layout that adapts to all screen sizes

### 🎨 Design Features

- Beautiful festive color scheme (Christmas red and green)
- Smooth scrolling animations
- Bootstrap 5-powered responsive grid
- Custom fonts (Sacramento & Work Sans)
- Bootstrap Icons integration
- Parallax background effects

## 🚀 Live Demo

Visit the live website: [Christmas Invitation Website](https://christmas-invitation-website.vercel.app/)

## 📋 Prerequisites

To run this project locally, you only need:

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic knowledge of HTML/CSS/JavaScript (for customization)

## 🛠️ Installation & Setup

### Quick Start

1. **Clone the Repository**

   ```bash
   git clone https://github.com/danielwidhiarto/ChristmasInvitationWebsite.git
   cd ChristmasInvitationWebsite
   ```

2. **Open in Browser**

   - Simply open `index.html` in your web browser
   - Or use a local server (recommended):

   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx serve
   ```

3. **Access the Website**
   - Direct file: `file:///path/to/index.html`
   - Local server: `http://localhost:8000`

### Customization

#### Update Event Details

Edit the countdown date in `index.html`:

```javascript
simplyCountdown(".simply-countdown", {
  year: 2023, // Change to your event year
  month: 12, // Change to your event month
  day: 23, // Change to your event day
});
```

#### Replace Images

- Add your images to the `assets/` folder
- Update image references in `index.html`

#### Modify RSVP Form

- Update form action URL in `index.html` (line ~227)
- Customize form fields as needed

#### Change Background Music

- Replace `audio/backgroundsong.mp3` with your audio file
- Ensure the file format is supported (.mp3, .wav, .ogg)

## 📁 Project Structure

```
ChristmasInvitationWebsite/
├── index.html                          # Main HTML file
├── style.css                           # Custom styles
├── README.md                           # Documentation
├── assets/                             # Images and media
│   ├── background.jpeg                 # Hero section background
│   ├── diakonia1-3.jpeg               # Charity event photos
│   ├── jemaatsakit1-9.jpeg            # Church visit photos
│   ├── pranatal1.JPG                  # Pre-event photos
│   ├── tkp1-6.jpeg                    # Community service photos
│   └── video.mp4                      # Invitation video
├── audio/
│   └── backgroundsong.mp3             # Background music
└── countdown/
    ├── simplyCountdown.min.js         # Countdown library
    └── simplyCountdown.theme.default.css  # Countdown styles
```

## 🎯 Technology Stack

- **HTML5** - Structure and content
- **CSS3** - Styling and animations
- **JavaScript** - Interactive functionality
- **Bootstrap 5.3.0** - Responsive framework
- **Bootstrap Icons** - Icon library
- **Simply Countdown** - Countdown timer library
- **Google Fonts** - Typography (Sacramento, Work Sans)

## 📱 Browser Compatibility

| Browser | Supported Version |
| ------- | ----------------- |
| Chrome  | ✅ Latest         |
| Firefox | ✅ Latest         |
| Safari  | ✅ Latest         |
| Edge    | ✅ Latest         |
| Opera   | ✅ Latest         |

## 🎨 Color Scheme

```css
--pink: #CB282C    /* Primary color (Christmas Red) */
--bg: #216127      /* Background color (Christmas Green) */
--shadow: 0 2px 2px rgb(0 0 0 / 0.5)
```

## 📸 Screenshots

### Hero Section with Countdown

The landing page features a beautiful countdown timer with a festive background.

### Photo Gallery Carousels

Interactive carousels showcasing various pre-event activities and community service.

### RSVP Form

Easy-to-use form for guests to confirm their attendance with family member count.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Ideas

- Add more animation effects
- Implement dark/light theme toggle
- Add multi-language support
- Create additional gallery layouts
- Improve form validation
- Add social media sharing features

## 🐛 Issues & Support

Found a bug or have a suggestion? Please:

1. Check existing [Issues](https://github.com/danielwidhiarto/ChristmasInvitationWebsite/issues)
2. Create a new issue with:
   - Clear description
   - Steps to reproduce (for bugs)
   - Expected vs actual behavior
   - Screenshots if applicable

## 👥 Authors & Credits

- **Design & Development**:
  - [@danielwidhiarto](https://instagram.com/danielwidhiarto)
  - [@babywidhiarto](https://www.instagram.com/a.babywidhiarto/)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Bootstrap team for the amazing framework
- Simply Countdown library developers
- Google Fonts for beautiful typography
- Sektor Pelayanan 13 community

## 📞 Contact

For questions or feedback:

- Instagram: [@danielwidhiarto](https://instagram.com/danielwidhiarto)
- Instagram: [@babywidhiarto](https://www.instagram.com/a.babywidhiarto/)

---

<div align="center">
  <p>Made with ❤️ and 🎄 by Sektor Pelayanan 13</p>
  <p>⭐ Star this repo if you found it helpful!</p>
</div>
