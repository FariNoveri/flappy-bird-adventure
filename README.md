# 🐦 Flappy Bird Adventure

A modern implementation of the classic Flappy Bird game with enhanced features, customization options, and secure server-side architecture.

## 🎮 Features

- **Multiple Characters**: Choose from 4 different skins (Bird, Plane, Rocket, Bee)
- **Customizable Controls**: Rebind jump and pause keys
- **Audio System**: Background music and sound effects with volume control
- **Settings Menu**: Comprehensive game configuration
- **Anti-cheat Protection**: Secure scoring system with server-side encryption
- **Responsive Design**: Works on both desktop and mobile devices
- **Tutorial Mode**: Learn how to play with built-in instructions
- **High Score System**: Encrypted score storage with server validation

## 🚀 How to Play

1. Select your preferred character from the skin selection screen
2. Press SPACE (or your configured jump key) to make the character fly upward
3. Avoid hitting the green pipes or the ground
4. Score points by successfully passing through pipes
5. Try to beat your high score!

## 🛠️ Technologies Used

- **Frontend**: HTML5 Canvas, Vanilla JavaScript, CSS3
- **Backend**: Node.js with Express server
- **Security**: Server-side encryption and anti-cheat protection
- **Storage**: Encrypted data persistence
- **Audio**: Web Audio API for sound management

## 📁 Project Structure

```
FLAPPY BIRD WEBSITE/
├── assets/                 # Game assets (images, sounds)
├── node_modules/          # Node.js dependencies
├── .env                   # Environment variables
├── .gitignore            # Git ignore file
├── encrypt-server.js     # Encryption server utilities
├── index.html           # Main game file
├── package.json         # Node.js package configuration
├── package-lock.json    # Package lock file
├── run-encrypted.js     # Encrypted game runner
└── server_original.js   # Main server file
```

## 🚀 Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- npm (Node Package Manager)

### Installation Steps

1. Clone this repository:
```bash
git clone https://github.com/FariNoveri/flappy-bird-adventure.git
```

2. Navigate to the project directory:
```bash
cd "FLAPPY BIRD WEBSITE"
```

3. Install dependencies:
```bash
npm install
```

4. Configure environment variables:
   - Copy `.env.example` to `.env` (if available)
   - Set up your environment variables

5. **Start the server**:
```bash
node server.js
```

6. Open your web browser and navigate to:
```
http://localhost:3000
```
(or the port specified in your server configuration)

## ⚠️ Important Notes

- **This game requires a Node.js server to run properly**
- The server handles encryption, anti-cheat protection, and secure score storage
- Simply opening `index.html` in a browser will not work due to server dependencies
- Make sure to run `node server.js` before accessing the game

## 🎯 Game Controls

- **Jump**: SPACE (customizable)
- **Pause**: P (customizable)
- **Click/Touch**: Alternative jump input for mobile devices

## ⚙️ Configuration Options

- Volume controls for music and sound effects
- Custom keybinding for controls
- Background music selection
- Character skin selection

## 🔒 Security Features

- Server-side encrypted high score storage
- Anti-cheat detection system
- Developer tools protection
- Tamper-resistant scoring with server validation
- Secure client-server communication

## 📱 Compatibility

- Modern web browsers (Chrome, Firefox, Safari, Edge)
- Desktop and mobile devices
- Touch screen support
- Keyboard navigation
- Requires JavaScript enabled

## 🎨 Customization

The game supports various customization options:
- Character skins
- Control bindings
- Audio settings
- Visual preferences

## 🔧 Development

### Running in Development Mode
```bash
# Start the server
node server.js

# For development with auto-restart (if nodemon is installed)
npm run dev
```

### Environment Variables
Make sure to configure your `.env` file with the necessary environment variables for encryption and server configuration.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Troubleshooting

### Common Issues

**Game won't load:**
- Ensure Node.js server is running (`node server.js`)
- Check if all dependencies are installed (`npm install`)
- Verify the server is running on the correct port

**High scores not saving:**
- Check server logs for encryption errors
- Ensure `.env` file is properly configured
- Verify database/storage connectivity

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🎯 Acknowledgments

- Inspired by the original Flappy Bird game by Dong Nguyen
- Special dedication to Illyasviel von Einzbern, whose beauty and grace inspired the elegant design of this game 💕
- Created with love by Fari Noveri, who finds coding as magical as Illya's spells ✨

---

*"Just like how Illyasviel von Einzbern captures hearts with her innocent charm, this game aims to capture the simple joy of classic gaming while adding modern touches of magic and wonder."* 💖

**Made with ❤️ and a touch of Einzbern magic**
