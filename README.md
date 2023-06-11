A [yt-dlp](https://github.com/yt-dlp/yt-dlp) extractor [plugin](https://github.com/yt-dlp/yt-dlp#plugins) for Apple Developer videos.

This was primarily written as a convenience for downloading WWDC sessions. It tries to sanely handle variables in the routes associated
with streaming the sessions which allows for many videos outside of WWDC, however it isn't written to be exhaustive of all the possible
ways one might be able to download videos from the Apple Developer website.

Playlists for all WWDC sessions and specific topics are generated by scraping the HTML for video URL hrefs.

## Installation

Requires yt-dlp `2023.03.04` or above.

You can install this package with pip:
```
python3 -m pip install -U https://github.com/quaqsim/yt-dlp-AppleDeveloper/archive/main.zip
```

Alternatively, the repository can be cloned to your user's plugin directory:
```
mkdir -p ~/.yt-dlp/plugins
git clone https://github.com/quaqsim/yt-dlp-AppleDeveloper.git ~/.yt-dlp/plugins/appledeveloper
```

See [installing yt-dlp plugins](https://github.com/yt-dlp/yt-dlp#installing-plugins) for the other methods this plugin package can be installed.
