# NoteApp

# 📝 My Notes - Full Stack Notes Application

A beautiful, interactive, and fully functional notes application built with React. Features a modern UI with smooth animations, real-time search, and persistent storage.

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager
- Modern web browser

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/notes-app.git
cd notes-app
```

2. **Install dependencies**
```bash
npm install
```

3. **Install required packages**
```bash
npm install react react-dom lucide-react
```

4. **Start the development server**
```bash
npm start
```

5. **Open your browser**
```
http://localhost:3000
```

## 🛠 Alternative Setup with Vite

If you prefer using Vite for faster development:

1. **Create a new Vite project**
```bash
npm create vite@latest notes-app -- --template react
cd notes-app
```

2. **Install dependencies**
```bash
npm install lucide-react
```

3. **Replace `src/App.jsx` with the Notes App code**

4. **Run the app**
```bash
npm run dev
```

## 📱 Usage

### Adding a Note
1. Enter a title in the "Note Title" field
2. Write your content in the textarea
3. Click "Add Note" or press `Ctrl + Enter`

### Editing a Note
1. Hover over any note card
2. Click the **Edit** icon (✏️)
3. Modify the title and/or content
4. Click **Save** to confirm or **Cancel** to discard

### Deleting a Note
1. Hover over any note card
2. Click the **Delete** icon (🗑️)
3. Note will be removed with animation

### Searching Notes
1. Use the search bar at the top
2. Type keywords to filter notes
3. Results update in real-time

## 🏗 Project Structure

```
notes-app/
├── public/
│   └── index.html
├── src/
│   ├── App.jsx              # Main Notes App component
│   ├── index.js             # Entry point
│   └── index.css            # Global styles
├── package.json
└── README.md
```

## ✨ Features

- ✅ Add, view, edit, and delete notes
- ✅ Real-time search functionality
- ✅ Beautiful gradient UI with animations
- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Persistent storage with localStorage
- ✅ Form validation and error handling
- ✅ Keyboard shortcuts (Ctrl+Enter)
- ✅ Toast notifications

## 🧪 Available Scripts

- `npm start` - Start development server
- `npm run build` - Create production build
- `npm test` - Run tests
- `npm run eject` - Eject from Create React App



---
