# YouTube Thumbnail Downloader

## Description

YouTube Thumbnail Downloader is a simple, user-friendly web application that allows users to easily preview and download thumbnails from YouTube videos. By simply pasting a YouTube video URL, users can instantly see and download the video's thumbnail in three different sizes: small, medium, and large.

## Features

- **Instant Preview**: As soon as a valid YouTube URL is pasted, thumbnails are displayed automatically.
- **Multiple Sizes**: Provides thumbnails in three sizes - small, medium, and large.
- **Easy Download**: Each thumbnail size has its own download button for quick saving.
- **Responsive Design**: Built with Bootstrap, ensuring a good experience on both desktop and mobile devices.
- **Client-Side Processing**: All processing is done in the browser, ensuring fast performance and no server requirements.

## Setup

1. Clone this repository or download the HTML file.
```bash
git clone https://github.com/mrxehmad/YT-Thumbnail-Downloader.git
```
2. Host HTML file in a web Hosting or Run locally.

That's it! No additional setup or installation is required.

## Usage

1. Open the YouTube Thumbnail Downloader in your web browser.
2. Copy a YouTube video URL.
3. Paste the URL into the input box on the webpage.
4. Thumbnails will automatically appear in three sizes: small, medium, and large.
5. Click the "Download" button under any thumbnail to save it to your device.

## Technical Details

- Built with HTML, CSS, and JavaScript.
- Uses Bootstrap 5 for styling and responsiveness.
- Extracts video ID from YouTube URLs using a regular expression.
- Utilizes YouTube's thumbnail API to fetch images.

## Limitations

- Relies on YouTube's public thumbnail API, which may change without notice.
- Cannot access private or unlisted video thumbnails.
- Thumbnail quality is limited to what YouTube provides publicly.

## Contributing

Feel free to fork this project and submit pull requests with improvements or open issues for any bugs you find or features you'd like to suggest.

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
