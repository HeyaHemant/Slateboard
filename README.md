# Slateboard ✏️

A dynamic, feature-rich whiteboard application built with React and HTML5 Canvas that enables real-time drawing, sketching, and collaborative design work.

## Features 🎨

- **Multiple Drawing Tools**
  - Line tool with customizable stroke
  - Rectangle and ellipse shapes
  - Arrow tool for annotations
  - Freehand brush for natural drawing
  - Text tool with adjustable positioning

- **Advanced Editing Capabilities**
  - Eraser tool with precision control
  - Undo/Redo functionality
  - Color picker for unlimited creativity
  - Adjustable stroke width

- **User-Friendly Interface**
  - Clean, intuitive toolbar
  - Responsive canvas design
  - Download functionality for saving work
  - Smooth drawing experience

## Tech Stack 💻

- **Frontend Framework:** React.js
- **Styling:** Tailwind CSS
- **Drawing Libraries:**
  - Perfect Freehand - Provides smooth, natural brush strokes
  - Rough.js - Creates hand-drawn, sketchy style graphics
- **State Management:** React Context API
- **Deployment:** Vercel

## Installation 🚀

1. Clone the repository:
    ```bash
    git clone https://github.com/HeyaHemant/slateboard.git
    ```

2. Navigate to the project directory:
    ```bash
    cd slateboard
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

4. Start the development server:
    ```bash
    npm run dev
    ```

## Usage 🖱️

1. Select a tool from the toolbar (line, rectangle, ellipse, arrow, brush, or text)
2. Choose your preferred color using the color picker
3. Click and drag on the canvas to draw
4. Use the eraser tool to remove unwanted elements
5. Utilize undo/redo buttons to manage your changes
6. Download your creation when finished

## Implementation Details 🛠️

- Custom state management using React's Context API and `useReducer`
- Smooth drawing using `useLayoutEffect` for DOM sync
- Robust mouse event handling
- Integrated RoughJS for sketchy-style graphics
- Integrated Perfect Freehand for natural brush strokes
- Tool state managed via custom ToolActionType system
- Undo/redo functionality with history state management

## Recent Updates 🆕

- Added download functionality
- Improved color picker UI
- Fixed text erasing using `measureText`
- Added undo/redo system
- Enhanced brush tool with smoother strokes

## Future Scope 🔮

- **Real-time Collaboration**
  - WebSocket support for multi-user drawing
  - Live cursors and chat
  - Room-based collaboration

- **Feature Enhancements**
  - Resize, rotate, and move shapes
  - Layer system
  - Templates, stickers, and custom shapes
  - Export to PNG, SVG, PDF

- **User Management**
  - Authentication
  - Dashboard for saved boards
  - Sharing permissions
  - Team-based boards

## Contributing 🤝

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License 📝

This project is open source and available under the [MIT License](LICENSE).

## Contact 📧

**Hemant Kumar** – [GitHub](https://github.com/HeyaHemant)

Project Link: [https://github.com/HeyaHemant/slateboard](https://github.com/HeyaHemant/slateboard)
