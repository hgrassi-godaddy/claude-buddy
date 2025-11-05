# Claude Buddy 🤖

Hackathon project created by the Patacones Unicorns (Patacorns for short): Adol Coneo, Kevin Tellez, and Haley Grassi

<img width="420" height="420" alt="image" src="https://github.com/user-attachments/assets/a5002305-adfc-4c94-8baf-94ff15c05824" />

A friendly coding companion interface built with React and Tailwind CSS. Claude Buddy provides an interactive chat experience with a customizable AI assistant for coding help and conversation.


## Features ✨

- **Chat Interface**: Clean, modern chat UI similar to ChatGPT with message bubbles
- **Dark/Light Mode**: Toggle between themes with full UI support
- **Customizable Bubbles**: Color picker for personalizing user message bubbles
- **Expandable Text Input**: Auto-resizing textarea that grows as you type
- **Buddy Character**: Large dedicated space for AI companion customization
- **Friendship System**: Track your relationship progress with Buddy
- **File Upload**: Support for code file uploads and analysis
- **Quick Actions**: Pre-built buttons for common coding tasks

## Tech Stack 🛠️

- **React 19.1.1** - Modern React with hooks
- **Vite 7.2.0** - Fast build tool and dev server
- **Tailwind CSS 4.1.16** - Utility-first CSS framework
- **react-colorful** - Color picker component
- **PostCSS** - CSS processing

## Getting Started 🚀

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd claude-buddy
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   ```
   http://localhost:5173
   ```

## Project Structure 📁

```
src/
├── components/
│   ├── ChatInterface.jsx      # Main chat UI component
│   ├── BuddyStatus.jsx        # Buddy character and status display
│   ├── BuddyAnimation.jsx     # Character animations and interactions
│   └── FileUpload.jsx         # File upload functionality
├── App.jsx                    # Main application component
├── main.jsx                   # Application entry point
└── index.css                  # Global styles and Tailwind imports
```

## Features in Development 🚧

- **Buddy Customization**: Dress up system for the AI companion
- **Enhanced Animations**: More interactive character behaviors
- **Code Analysis**: File content processing and insights
- **Extended Chat**: Message history and conversation management

## Contributing 🤝

Feel free to submit issues, feature requests, or pull requests to help improve Claude Buddy!

## License 📄

MIT License - see LICENSE file for details.
