# PA-NOTE - Personal Note Taking Application

A modern, responsive note-taking web application with a clean user interface and dark mode support.

## Features

- **Create, Edit, and Delete Notes**: Easily manage your notes with a simple and intuitive interface
- **Categories**: Organize your notes with categories (General, Work, Personal, Ideas)
- **Search Functionality**: Quickly find notes by searching titles and content
- **Dark Mode**: Toggle between light and dark themes for comfortable viewing
- **Text Formatting**: Basic text formatting options including font family, size, and color
- **Local Storage**: All notes are saved in your browser's local storage
- **Export Notes**: Backup your notes by exporting them as JSON
- **Responsive Design**: Works on desktop and mobile devices
- **Profile Management**: Customize your profile settings

## Project Structure

```
UPDATED-PA-NOTE/
├── elements/           # SVG assets and images
│   ├── PanotePencil.svg       # Light mode logo
│   └── PanotePencilDark.svg   # Dark mode logo
├── static/             # HTML pages
│   ├── index.html      # Main note-taking page
│   └── profile.html    # User profile page
├── template/           # CSS stylesheets
│   └── style.css       # Main stylesheet
└── README.md
```

## Getting Started

1. Clone the repository
2. Open `static/index.html` in your web browser
3. Start creating notes!

## Usage

### Creating a Note
1. Click the "+ New Note" button
2. Enter a title and content
3. Select a category
4. Click "Save Note"

### Editing a Note
1. Hover over a note card to reveal its content
2. Click the edit (pencil) icon
3. Make your changes
4. Click "Save Note"

### Searching Notes
1. Click the search icon in the navigation
2. Type your search query
3. Notes matching your query will be displayed

### Dark Mode
Toggle dark mode by clicking the moon/sun switch in the navigation bar.

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- Local Storage API
- Font Awesome Icons
- Tailwind CSS (for profile page)

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## License

This project is open source and available for educational purposes.