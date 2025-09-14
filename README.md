# Spotify Clone 🎶

## Overview
This project is a Spotify clone that emulates key features of the popular music streaming service. Built with **HTML**, **CSS**, and **JavaScript**, it provides a responsive and fully functional user experience. The goal of this project is to demonstrate how to create a music streaming app with core features and modern web development practices.

---

## Features

- 🎵 **Playlists**: Dynamic playlist creation and automatic loading of new playlists.
- 📱 **Responsive Design**: Adaptive layout with a hamburger menu for seamless navigation.
- 🎷 **Playback Controls**: Play, pause, skip, and adjust volume effortlessly.
- 🤖 **Smart Playlist Detection**: Automatically detects new playlists when a folder with `info.json` and `cover.jpg` is added to the `songs` directory.
- 👥 **User-Friendly UI**: Intuitive interface with visually appealing elements.

---

## Getting Started

### Live Demo
Try out the live version of the project here: [Spotify Clone Demo](https://vivekbhatt02.github.io/Spotify-Clone/).
Experience responsive design, dynamic playlists, and playback controls in action.

### Clone the Repository
Ensure you have Git installed on your system, then follow these steps:

```bash
# Clone the repository
git clone https://github.com/Vivekbhatt02/Spotify-Clone.git

# Navigate to the project directory
cd Spotify-Clone
```

### Run the Project
- Open the `index.html` file in your browser to view the app.
- For better performance, use a local server such as `Live Server` in VS Code.

---

## Customizing Playlists
You can modify or add playlists to the app. Here’s how:

1. **Fork the Repo**
   Fork this repository to your GitHub account.

2. **Add a Playlist Folder**
   Create a new folder in the `songs` directory. The app will automatically detect it as a new playlist.

3. **Include Playlist Details**
   Add the following files to the new folder:

   - `info.json`: Contains metadata for the playlist.
   - `cover.jpg`: The image used as the playlist thumbnail.

4. **Structure of `info.json`**
   The `info.json` file should follow this structure:

   ```json
   {
       "title": "Playlist Title",
       "description": "A short description of the playlist"
   }
   ```

5. Save your changes, and the app will dynamically load the new playlist when it runs.

---

## Contribution

### How to Contribute
We welcome contributions to this project! Follow these steps:

1. **Fork the Repository**
2. **Create a Branch for Your Feature**
   ```bash
   git checkout -b feature-name
   ```
3. **Make Your Changes**
   Ensure your code follows best practices and does not introduce bugs.

4. **Commit Your Changes**
   ```bash
   git commit -m "Add description of changes"
   ```
5. **Push to Your Fork**
   ```bash
   git push origin feature-name
   ```
6. **Submit a Pull Request**
   Open a pull request on the original repository with a description of your changes.

### Reporting Issues
If you encounter a bug or have a feature request, please submit an issue here: [Submit an Issue](https://github.com/Vivekbhatt02/Spotify-Clone/issues). Provide detailed information to help resolve the issue quickly.

---

## Acknowledgments
I, [@Vivekbhatt02](https://github.com/Vivekbhatt02), am the primary contributor to this project. Thanks to all the open-source tools, libraries, and resources that made this project possible.

---

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as per the terms of the license.

---

🌟 **If you like this project, give it a star on GitHub!** 🌟

