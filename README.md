# YouTube to Spotify Playlist Converter

This project allows you to transfer songs from a YouTube playlist to a Spotify playlist. It automates the process of searching for songs on YouTube, extracting their titles and artists, and adding them to a Spotify playlist of your choice.

## Features

- Retrieve songs from a YouTube playlist.
- Search for songs on Spotify.
- Create a new Spotify playlist or use an existing one.
- Add songs to the Spotify playlist.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have a Spotify account.
- You have a YouTube account.
- You have installed Python 3.x.
- You have obtained API keys for the YouTube Data API and Spotify Web API.

## Installation

1. Clone this repository:

    ```sh
    git clone https://github.com/yourusername/youtube-to-spotify.git
    cd youtube-to-spotify
    ```

2. Install the required Python libraries:

    ```sh
    pip install -r requirements.txt
    ```

3. Set up your YouTube Data API and Spotify Web API credentials. Save them in a file named `config.py`.

## Usage

1. Activate your virtual environment:

    ```sh
    source your_virtualenv/bin/activate  # macOS/Linux
    your_virtualenv\Scripts\activate      # Windows
    ```

2. Run the script:

    ```sh
    python main.py
    ```

3. Follow the prompts to enter your YouTube playlist URL and select or create a Spotify playlist.

4. The script will retrieve the songs from the YouTube playlist, search for them on Spotify, and add them to the Spotify playlist.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

If you want to contact the maintainer, you can reach out at `your_email@example.com`.

## Acknowledgments

- YouTube Data API
- Spotify Web API
