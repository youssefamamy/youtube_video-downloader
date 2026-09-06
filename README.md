YouTube Downloader

A simple Python command-line tool that downloads YouTube videos at up to 720p using "yt-dlp".

🚀 Features

- Accepts a YouTube URL from the user
- Validates the entered URL
- Downloads video at up to 720p
- Downloads audio alongside the video when available
- Merges the video and audio into an MP4 file
- Saves downloaded videos to the Android Downloads folder
- Includes retry and timeout settings

🛠️ Technologies

- Python
- yt-dlp

⚙️ How It Works

1. The program asks the user to enter a YouTube URL.
2. It checks whether the URL starts with a supported YouTube URL format.
3. The download configuration is created.
4. "yt-dlp" handles the video and audio download.
5. The video and audio are merged into an MP4 file.
6. The finished file is saved to the Downloads folder.

▶️ How to Run

Install "yt-dlp":

pip install yt-dlp

Then run:

python main.py

Enter the YouTube URL when prompted.

📚 What I Learned

This was my first Python project, and I used it to practice:

- User input
- Variables
- Conditions
- Loops
- String methods
- Tuples
- Dictionaries
- External Python libraries
- File paths
- Basic URL validation
- Retry and timeout configuration
- Working with network-based tools

🔮 Future Improvements

Possible improvements for future versions:

- Better URL validation
- More robust error handling
- User-selectable video quality
- Download progress information
- Better project structure
- Logging
- Automated tests

⚠️ Disclaimer

This project is intended for downloading content that you have permission to download. Users are responsible for following applicable laws and the terms of the services they use.

👨‍💻 Author

Youssef