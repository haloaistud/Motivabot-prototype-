# Motivabot - Your Golden AI Motivational Assistant

A modern, interactive web application that provides personalized motivation, goal tracking, and AI-powered conversations to help you stay motivated and achieve your goals.

## 🌟 Features

- **Goal Setting & Tracking**: Set, manage, and track your personal goals with visual progress indicators
- **AI-Powered Chat**: Intelligent conversations with context-aware responses using advanced NLP
- **Speech Synthesis**: Text-to-speech functionality for an immersive experience
- **Daily Motivation**: Curated inspirational quotes with speech output
- **Dark/Light Mode**: Toggle between themes for comfortable viewing
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Persistent Storage**: Your goals and preferences are saved locally
- **Real-time Progress**: Visual progress tracking with animated progress bars

## 🚀 Demo

Open `index.html` in your web browser to start using Motivabot immediately - no installation required!

## 💻 Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **NLP**: Built-in natural language processing for context-aware responses
- **Speech API**: Web Speech API for text-to-speech functionality
- **Storage**: LocalStorage for data persistence
- **Styling**: Custom CSS with golden theme and smooth animations

## 🔧 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/motivabot.git
   ```

2. Navigate to the project directory:
   ```bash
   cd motivabot
   ```

3. Open `index.html` in your web browser:
   ```bash
   open index.html
   # or
   python -m http.server 8000  # For local development server
   ```

## 📱 Usage

### Setting Goals
1. Enter your goal in the "Set Your Goals" section
2. Click "Add Goal" to save it
3. Watch your progress bar update automatically
4. Delete goals using the red "Delete" button

### Chat Interaction
1. Type messages in the chat input field
2. Motivabot will respond with contextually relevant motivation
3. Responses are automatically spoken (if TTS is enabled)

### Customization
- **Theme Toggle**: Switch between dark and light modes
- **Text-to-Speech**: Enable/disable speech synthesis
- **New Quotes**: Generate fresh motivational quotes

## 🎯 Key Features Explained

### Advanced NLP Processing
- Context-aware responses based on user input
- Sentiment analysis for appropriate motivation
- Pattern recognition for common motivational needs

### Speech Synthesis
- High-quality text-to-speech using Web Speech API
- Customizable speech parameters
- Automatic speech for bot responses and quotes

### Progress Tracking
- Visual progress bars with smooth animations
- Goal completion tracking
- Motivational feedback based on progress

## 🔒 Privacy & Data

- All data is stored locally in your browser
- No personal information is transmitted to external servers
- Complete privacy and data control

## 🌐 Browser Compatibility

- Chrome 80+ (Recommended)
- Firefox 75+
- Safari 13+
- Edge 80+

**Note**: Speech synthesis requires a modern browser with Web Speech API support.

## 🛠️ Development

### Project Structure
```
motivabot/
├── index.html          # Main application file
├── README.md          # Project documentation
├── .github/
│   └── workflows/
│       └── deploy.yml # GitHub Actions deployment
└── assets/           # Future assets directory
```

### Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Setup

For local development with live reload:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (with live-server)
npx live-server

# Using PHP
php -S localhost:8000
```

## 📋 Roadmap

- [ ] User accounts and cloud sync
- [ ] Advanced goal categories
- [ ] Achievement system
- [ ] Social sharing features
- [ ] Mobile app version
- [ ] Integration with calendar apps
- [ ] Advanced analytics dashboard

## 🐛 Known Issues

- Speech synthesis may not work in private/incognito mode
- Progress calculation is currently based on goal count (not completion status)
- Some older browsers may not support all features

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 👏 Acknowledgments

- Inspirational quotes from various historical figures
- Web Speech API for text-to-speech functionality
- Modern CSS techniques for responsive design

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/yourusername/motivabot/issues) page
2. Create a new issue with detailed information
3. Join our community discussions

## ⭐ Show Your Support

If you find Motivabot helpful, please consider giving it a star on GitHub!

---

**Made with ❤️ for everyone who needs a little motivation in their life.**