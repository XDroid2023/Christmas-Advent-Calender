# 🎄 Interactive Christmas Advent Calendar

A beautiful, interactive web-based advent calendar featuring daily inspirational Christmas messages, falling snow animation, and text-to-speech capabilities.

![Christmas Advent Calendar](preview.png)

## ✨ Features

- **25 Interactive Boxes**: One for each day leading up to Christmas
- **Inspirational Messages**: Unique, thoughtful Christmas messages for each day
- **Text-to-Speech**: Listen to the messages being read aloud
- **Snow Animation**: Beautiful falling snow effect
- **Responsive Design**: Works perfectly on all devices
- **Progress Saving**: Remembers which boxes you've already opened
- **Professional Design**: Elegant Christmas theme with modern aesthetics

## 🚀 Getting Started

1. Clone this repository:
```bash
git clone https://github.com/yourusername/christmas-advent-calendar.git
cd christmas-advent-calendar
```

2. Start a local server:
```bash
# Using Python 3
python3 server.py
```

3. Open your browser and visit:
```
http://localhost:3000
```

## 💻 Usage

- Click on any numbered box to reveal the day's message
- Click the speaker button to hear the message read aloud
- Close the message by clicking the X or clicking outside the modal
- Your opened boxes will remain marked even after refreshing the page

## 🛠 Technical Details

### Technologies Used
- HTML5
- CSS3 (with modern features like CSS Grid and animations)
- JavaScript (ES6+)
- Web Speech API for text-to-speech
- Local Storage for progress saving

### Browser Support
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Other modern browsers with Web Speech API support

## 🎨 Customization

### Changing Messages
Edit the `messages` array in `script.js` to customize the daily messages.

### Modifying Colors
The color scheme can be adjusted by editing the CSS variables in `styles.css`:
```css
:root {
    --christmas-red: #c1121f;
    --christmas-dark-red: #780000;
    --christmas-green: #165B33;
    --christmas-dark-green: #0d3320;
    --gold: #FFD700;
    --cream: #FFF8E7;
}
```

## 📱 Responsive Design

The calendar is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones
- Different screen orientations

## 🔒 Local Storage

The calendar uses browser's Local Storage to remember which boxes have been opened, ensuring your progress is saved between visits.

## 🎯 Accessibility

- Semantic HTML structure
- ARIA labels where needed
- Keyboard navigation support
- Text-to-speech functionality
- High contrast color scheme

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 🙏 Acknowledgments

- Fonts from Google Fonts
- Snow animation inspired by various CSS animation tutorials
- Text-to-speech powered by Web Speech API

## 🐛 Known Issues

- Text-to-speech may not work in browsers that don't support the Web Speech API
- Snow animation might affect performance on low-end devices

## 📞 Support

If you encounter any issues or have questions, please:
1. Check the known issues section
2. Create a new issue in the repository
3. Provide detailed information about your browser and system

---

Made with ❤️ for spreading Christmas cheer
