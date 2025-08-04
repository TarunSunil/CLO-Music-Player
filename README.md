# CLO - Music Player

**CLO - Music Player** is a modern and stylish web-based music player that allows you to play, pause, skip, and repeat your favorite songs directly from your browser. The player features an intuitive interface, dynamic playlists, and smooth playback controls, making it perfect for music lovers who want a simple yet powerful listening experience.

## 🎵 Features

- **Play/Pause/Skip Controls:** Easily play, pause, skip to next or previous tracks.
- **Progress Bar:** Interactive progress bar to seek your music.
- **Repeat & Shuffle Modes:** Toggle between repeat, repeat-one, and shuffle.
- **Dynamic Playlist:** Browse and select from a visually appealing song list.
- **Responsive Layout:** Looks great on both desktop and mobile devices.
- **Stylish UI:** Modern gradient backgrounds, soft shadows, and attractive imagery.

## 🖼️ Demo Screenshot

> <img width="2495" height="1257" alt="image" src="https://github.com/user-attachments/assets/3d673931-0405-4251-aae2-d5ab908ff5f0" />


## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/CLO-Music-Player.git
cd CLO-Music-Player
```

### 2. Add Your Songs

- **Images:** Place `.jpg` album art images in the `images` folder.
- **Music:** Place `.mp3` song files in the `songs` folder.

### 3. Add Your Tracks

Edit the `music-list.js` file:

```javascript
{
  name: "Song Name",
  artist: "Artist Name",
  img: "image-file-name-without-extension",
  src: "song-file-name-without-extension"
}
```
> Example:
> - For `songs/music-1.mp3` and `images/music-1.jpg`, use `"img": "music-1"`, `"src": "music-1"`.

Add your tracks to the `allMusic` array as shown.

### 4. Open the App

Simply open `index.html` in your browser. No server required!

## 🛠️ File Structure

| File/Folder      | Purpose                                     |
|------------------|---------------------------------------------|
| `index.html`     | Main UI and layout of the music player      |
| `style.css`      | Styling and responsive design               |
| `script.js`      | Player functionality and controls           |
| `music-list.js`  | Song metadata and playlist configuration    |
| `images/`        | Album art images (`.jpg`)                   |
| `songs/`         | Audio tracks (`.mp3`)                       |

## 🎨 Customization

- **Theme:** Change gradient colors in `style.css` under the `:root` selector.
- **Song List:** Add, edit, or remove songs using `music-list.js`.
- **Icons:** Uses Google Fonts (Poppins) for modern look.

## 📦 Dependencies

- Pure **HTML, CSS, JavaScript** — no external JS libraries required.
- Google Fonts (online import).

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit pull requests for enhancements or bugfixes.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Credits

- Album art and music used in this project are placeholders. Replace with your own files as needed.
- UI inspired by popular web music players.

**Enjoy your music!**

[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/89231590/c3914c2c-5049-4b66-9543-5ddb74045932/index.html
[2] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/89231590/6f505d94-0b32-4357-aa36-9775f8f46f93/music-list.js
[3] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/89231590/e8aa5a1c-efcf-45fe-8b7e-f925c4648470/script.js
[4] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/89231590/3563e6d2-17e9-4a50-83e5-2a33bbdb2f7a/style.css
