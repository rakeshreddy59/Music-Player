# 🎧 Spotify Web Player Clone
A responsive front-end clone of the Spotify web player interface, built purely with HTML, CSS, and vanilla JavaScript. This project focuses on replicating the visual layout, navigation structure, and basic local audio playback functionality of the popular music streaming service.

***

## ✨ Features

* **Responsive Layout:** Sidebar navigation and main content structure resembling the Spotify web app.
* **Sticky Navigation:** A sticky header bar in the main content area for navigation and user options.
* **Local Music Player:** A persistent bottom bar featuring controls for play/pause, volume, and playback progress.
* **Interactive Cards:** Clicking on a song card in the "Trending" section loads that specific track into the player for immediate playback.
* **Dynamic Playback:** Functionality for Next, Previous, and auto-play when a song ends.
* **CSS Truncation:** Ensures long song titles and artist names are correctly truncated with an ellipsis (`...`) instead of wrapping awkwardly.

***

## 🛠️ Technologies Used

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Structure and Semantic Content |
| **CSS3** | Styling, Layout (Flexbox), and Responsiveness |
| **JavaScript (Vanilla)** | Player logic, DOM manipulation, and dynamic song loading |
| **Font Awesome** | Icons for navigation and player controls |

***

## 🚀 Getting Started

Follow these steps to set up the project locally on your machine.

### Prerequisites

You need a modern web browser to view the project. No other software is strictly required, but a code editor (like VS Code) and a local development server are recommended.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/Spotify-Web-Player-Clone.git](https://github.com/your-username/Spotify-Web-Player-Clone.git)
    cd Spotify-Web-Player-Clone
    ```

2.  **Open the project:**
    Simply open the `index.html` file in your preferred web browser.

    Alternatively, use a Live Server extension (if using VS Code) to serve the files, which is better for development.

### Project Structure
Spotify-Web-Player-Clone/
├── assets/                  # All images and local music files (.mp3, .mp4)
├── index.html               # Main structure and JavaScript logic
├── style.css                # All CSS styling
└── README.md                # This file