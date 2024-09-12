# ViewTube

## Description
ViewTube is a YouTube clone project developed to provide users with a seamless and responsive interface for video playback, search capabilities, and browsing channels. The app integrates real-time data retrieval using the Rapid API to fetch YouTube content, ensuring users have access to the latest videos and channels.

This project is built using React.js, ensuring a modern and efficient user experience.

## Features
- **Video Playback:** Users can watch videos directly in the app.
- **Search Functionality:** Allows users to search for videos and channels based on keywords.
- **Channel Details:** Displays detailed information about YouTube channels and their content.
- **Related Videos:** Recommends videos related to the current video being watched.
- **Real-Time Data Fetching:** Integrated with Rapid API for fetching up-to-date YouTube videos and channel information.
- **Responsive Design:** Designed to work seamlessly across different screen sizes.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/palakdesai4501/ViewTube
    cd viewtube
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory with the following content:

    ```bash
    VITE_REACT_RAPID_API_KEY=your-rapidapi-key
    ```

4. Start the development server:

    ```bash
    npm start
    ```

5. Visit `http://localhost:3000` in your browser to view the app.

## API Integration
The app fetches video and channel data from the [YouTube Data API](https://rapidapi.com/h0p3rwe/api/youtube-search-and-download) using Axios for HTTP requests.

Key API endpoints used:
- **Fetch Videos:** Retrieves video content based on the user's search query.
- **Fetch Channel Info:** Retrieves detailed information about specific channels.

## Main Components

- **Navbar:** Provides navigation options and a search bar for the app.
- **SearchBar:** Allows users to search for videos and channels by entering keywords.
- **VideoDetail:** Displays detailed information and playback for the selected video.
- **ChannelDetail:** Provides details of YouTube channels and lists their content.
- **Feed:** The home feed, showing a variety of video content.
- **SideBar:** Contains category filters for browsing videos by category.
- **VideoCard:** Represents each video in the list view with a thumbnail and video info.
- **Loader:** Shows a loading animation when data is being fetched from the API.

## Future Enhancements
- Add user authentication to allow saving favorite videos and creating playlists.
- Improve video recommendation algorithms based on user history.
- Implement a comments section for each video.

