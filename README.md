# Secret Archive — PeppermintGrave

Secret Archive is the music archive/player for the PeppermintGrave website.

## Audio

The MP3 files in `audio/` are the original files supplied for this project. They are included **untouched**; they have not been re-encoded or quality-compressed.

## License

### Website code
The HTML, CSS, and JavaScript in this package are released under the **MIT License**. See `LICENSE` for the full license text.

### Music and artwork
The music/audio files and any original artwork or other creative assets are **NOT covered by the MIT License**. All rights are reserved by their respective copyright owner(s). You may not redistribute, sell, re-upload, modify, sample, or otherwise use these assets outside the permissions granted by their owner(s).

If you own these assets and want a different license for them, replace this notice with the license you choose.

## GitHub Pages setup

1. Create a GitHub repository.
2. Upload `index.html`, `LICENSE`, `README.md`, and the entire `audio/` folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your main branch and `/ (root)`, then save.
6. Open the GitHub Pages URL after deployment finishes.

### Important
Keep the `audio` folder beside `index.html` and keep the filenames unchanged. The player references the songs using relative paths such as `audio/mosslight-drift.mp3`.
