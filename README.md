# YouTube Playlist Downloader

This Python script allows you to download videos from a YouTube playlist and convert them to MP3 format. It utilizes the Pytube library for downloading YouTube videos and MoviePy for converting MP4 to MP3.

## Prerequisites

1. Python: Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

2. Required Python Libraries: Install the necessary libraries by running the following command in your terminal or command prompt:

```bash
pip install pytube 
```

## Usage

1. Clone the repository to your local machine:

```bash
git clone https://github.com/solankikeval166/Youtube-Playlist-downloader-MP3-.git
```

2. Navigate to the project directory:

```bash
cd Youtube-Playlist-downloader-MP3
```
3. Open the script file (download_playlist.py) in a text editor and set the SAVE_PATH variable:

```python
SAVE_PATH = "/path/to/your/directory"  # Change this to your desired download directory
```

4. Run the script:

```bash
python Youtube_Playlist_Downloader.py
```

The script will prompt you for the YouTube playlist URL. Enter the URL, and the script will download the videos from the playlist in MP3 format.

Notes:
1. The downloaded MP3 files will be saved in the directory specified by the SAVE_PATH variable.
2. Make sure the pytube library is installed before running the script.
3. If you encounter any issues, check the error messages and make sure you have a stable internet connection.
4. Feel free to customize the script according to your needs. Happy downloading!
