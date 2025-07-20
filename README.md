# Universal yt-dlp Command Generator

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
![Static Site](https://img.shields.io/badge/site-static-green.svg)
![Vanillia JS](https://img.shields.io/badge/tech-Vanilla_JS-yellow.svg)

A browser-based, single-file web app that provides a user-friendly graphical interface (GUI) for generating complex commands for the powerful `yt-dlp` command-line video downloader. This tool simplifies the process of using `yt-dlp`'s advanced features without needing to memorize all the flags and syntax.

**[➡️ Live Demo Link (Replace with your link)](#)**

---

<!-- Add a screenshot of your application here -->
![Screenshot of the Universal yt-dlp Command Generator](https://i.imgur.com/your-screenshot.png) 

---

## ✨ Features

This tool is packed with features to cover a wide range of downloading needs:

- **Universal URL Support**: Works with any video or playlist URL supported by `yt-dlp`.
- **Quality Selection**: Choose from various quality options, including specific resolutions (1080p, 720p), preferred formats (MP4, WebM), or audio-only (MP3).
- **Custom Output**: Specify a download directory and a custom filename template using `yt-dlp` variables.
- **Network Options**:
    - Route traffic through a **Proxy Server**.
    - Set a **Download Speed Limit** to manage bandwidth.
- **Download Management**:
    - Use a **Download Archive** file to prevent re-downloading videos, perfect for managing playlists or channel backups.
    - **Force Overwrite** of existing files.
- **Subtitle Support**: Easily embed available subtitles into the video file.
- **User-Friendly Interface**:
    - A clean, modern, and responsive dark-themed UI.
    - **Save Settings**: Your preferences are automatically saved in your browser's local storage.
    - **One-Click Copy**: Instantly copy the generated command to your clipboard.

## 🚀 How to Use the Generator

1.  **Open the Web Page**: Navigate to the `index.html` file or the live demo link.
2.  **Enter URL**: Paste the video or playlist URL into the first input field.
3.  **Configure Options**: Select your desired quality, set output paths, and toggle any other advanced options you need.
4.  **Generate**: Click the "Generate Command" button.
5.  **Copy & Paste**: Click the "Copy Command" button and paste the command into your terminal.

## 📋 Prerequisites

To execute the generated command, you must have the following installed on your system:

1.  **Python**: Required for `yt-dlp`. Download from [python.org](https://www.python.org/downloads/) and ensure it's added to your system's PATH.
2.  **yt-dlp**: Install it by running the following command in your terminal:
    ```sh
    pip install -U yt-dlp
    ```
3.  **FFmpeg**: Essential for merging separate video and audio files (common for high-quality downloads) and for converting formats. Download from [ffmpeg.org](https://ffmpeg.org/download.html) and add it to your system's PATH.

## ☁️ Host Your Own Version

This is a completely client-side application, meaning you can host it for free on any static web hosting service.

1.  **Download the Code**: Save the complete code as a single `index.html` file.
2.  **Deploy**: Upload the `index.html` file to a static hosting provider. Popular free options include:
    - [Netlify](https://www.netlify.com/) (drag-and-drop deployment)
    - [Vercel](https://vercel.com/)
    - [GitHub Pages](https://pages.github.com/)

## 🛠️ Technologies Used

- **HTML5**: For the structure of the web page.
- **CSS3**: For custom styling and layout.
- **Tailwind CSS**: For rapid UI development.
- **Vanilla JavaScript**: For all the application logic, with no external frameworks.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
