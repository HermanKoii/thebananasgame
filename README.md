# The Bananas Game - Web Card Matching Application

## Project Overview

The Bananas Game is an interactive web application that allows users to swipe and match cards to earn prizes. The game is designed to be an engaging, fun way to interact with web content and potentially contribute to tagging or categorizing web resources.

### Key Features
- Card-based swiping interface
- Dynamic content display
- Interactive gameplay mechanics
- Firebase integration for potential backend functionality

## Technologies Used

- **Frontend**: 
  - HTML5
  - AngularJS (1.x)
  - Custom JavaScript
- **Styling**: CSS
- **Libraries**:
  - Typed.js (for text animations)
  - Firebase (for potential backend services)

## Getting Started

### Prerequisites
- Modern web browser
- Basic understanding of web technologies
- (Optional) Local web server for development

### Local Setup
1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/the-bananas-game.git
   cd the-bananas-game
   ```

2. Open `index.html` directly in a web browser, or use a local web server
   ```bash
   # Example using Python's simple server
   python -m http.server 8000
   ```

3. Navigate to `http://localhost:8000` in your web browser

## Project Structure
```
.
├── index.html         # Main application entry point
├── css/
│   └── index.css      # Styling for the application
├── js/
│   ├── angular.js     # AngularJS framework
│   ├── firebase.js    # Firebase integration
│   ├── index.js       # Main application logic
│   └── typed.js       # Text typing animation library
├── media/             # Image assets for cards
└── pages/             # Additional page components
```

## Game Mechanics

The game presents users with a stack of cards that can be navigated using:
- Swipe/Click interactions
- Next button ("> " control) to move between cards
- Dynamic card display with images and overlay text

## Configuration

- No external configuration required
- Firebase configuration can be found in `js/firebaseConfig.js`

## Deployment

### Static Hosting
The application can be deployed on:
- GitHub Pages
- Netlify
- Vercel
- Any static website hosting service

Deployment steps:
1. Ensure all files are in the root directory
2. Upload the entire project folder
3. Configure hosting to serve `index.html` as the entry point

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Your Name - [Your Email]

Project Link: https://github.com/yourusername/the-bananas-game