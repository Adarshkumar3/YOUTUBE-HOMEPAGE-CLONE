# YouTube Homepage Clone

A vanilla JavaScript implementation of a YouTube-like interface with advanced features.
# Demo Link -https://adarshkumar3.github.io/YOUTUBE-HOMEPAGE-CLONE/

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [API](#api)
- [Contributing](#contributing)
- [License](#license)

## Features

- Fetch and display trending videos
- Search functionality
- Infinite scrolling
- Video playback
- Filtering by upload date
- Sorting by relevance, date, view count, and rating
- Responsive design for mobile and desktop

## Getting Started

### Prerequisites

- A modern web browser
- An API key from [RapidAPI](https://rapidapi.com/ytdlfree/api/youtube-v3-alternative/) for the YouTube v3 Alternative API

### Installation

1. Clone the repository or download the HTML file:

```bash
git clone https://github.com/Adarshkumar3/YOUTUBE-HOMEPAGE-CLONE
```

2. Open the HTML file in a text editor.

3. Replace the API key in the `apiOptions` object with your own key:

```javascript
const apiOptions = {
    method: 'GET',
    headers: {
        'X-RapidAPI-Key': 'YOUR_API_KEY_HERE',
        'X-RapidAPI-Host': 'yt-api.p.rapidapi.com'
    }
};
```

4. Save the file and open it in a web browser.

## Usage

- The page will load trending videos by default.
- Use the search bar at the top to search for specific videos.
- Scroll down to automatically load more videos.
- Click on a video thumbnail to play the video.
- Use the "Upload Date" dropdown to filter videos by recency.
- Use the "Sort by" dropdown to change the order of the results.

## API

This project uses the [YouTube v3 Alternative API](https://rapidapi.com/ytdlfree/api/youtube-v3-alternative/) from RapidAPI. You will need to sign up for a RapidAPI account and subscribe to this API to get your API key.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

---

Created with ❤️ by Adarsh Kumar
