# Notes App
A simple and intuitive note-taking application with local storage persistence.

# Features
* Create Notes - Add new notes with a single click
* Auto-Save - Notes are automatically saved to browser's local storage
* Delete Notes - Remove unwanted notes with delete button
* Responsive Design - Works on all screen sizes
* Beautiful UI - Gradient background with clean interface
* Persistent Storage - Notes remain even after browser refresh

# Live Demo:
https://tahirahmad88.github.io/ResponsiveNotesApplicationJavaScript/

# ScreenShot:
<img width="1149" height="586" alt="Notes" src="https://github.com/user-attachments/assets/ef5e2663-9303-4e8b-b637-1a89e1dd9f85" />

# Project Structure
NotesApp/

├── index.html          # Main HTML file
├── style.css           # Styling file
├── script.js           # Application logic

└── images/             # Image assets
    ├── notes.png       # Notes icon
    ├── edit.png        # Create note icon
    └── delete.png      # Delete note icon

# How to Use
1. Create a Note - Click the "Create Notes" button
2. Write Content - Click on any note and start typing
3. Delete a Note - Click the trash icon on any note
4. Auto-Save - All changes are saved automatically

# Technologies Used
* HTML5 - Structure
* CSS3 - Styling with gradients and animations
* JavaScript - DOM manipulation and local storage

# How It Works
# Local Storage
* Notes are stored in browser's localStorage
* Data persists across browser sessions
* No database required

# Key Functions

// Save notes to local storage
localStorage.setItem("notes", notesContainer.innerHTML);

// Load notes from local storage
notesContainer.innerHTML = localStorage.getItem("notes");

# Features
* Contenteditable - Notes are editable directly
* Event Delegation - Efficient event handling
* Auto-Save - Saves on every keyup event
* Enter Key Handling - Custom line break behavior

# Customization
Change Colors

/* In style.css */

background: linear-gradient(135deg, #bb80f2, #95c0ff);
/* Change to your preferred colors */
Change Note Width

.input-box {
    max-width: 500px; /* Adjust width */
    min-height: 150px; /* Adjust height */
}

# Author
Tahir Ahmad

# GitHub: 
@TahirAhmad88

Star this repository if you like it!


