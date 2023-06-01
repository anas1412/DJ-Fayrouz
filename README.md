# DJ Fayrouz Discord Bot

DJ Fayrouz is a Discord bot written in Python that allows you to play music in your Discord server. With DJ Fayrouz, you can play music from YouTube and other popular music platforms, control the playback, and manage your music queue.

## Features

- Play music from YouTube: DJ Fayrouz can search and play music from YouTube by providing the song title or URL.
- Music control: You can control the playback of the music by using commands such as play, pause, resume, skip, and stop.
- Music queue: DJ Fayrouz supports a queue system, allowing users to add songs to a queue and listen to them in order.
- Shuffle and repeat: DJ Fayrouz provides commands to shuffle the music queue and repeat the current song.
- User-friendly commands: The bot offers simple and intuitive commands to interact with the music playback.

## Setup

To set up DJ Fayrouz Discord Bot, follow these steps:

1. Clone the repository or download the source code.
2. Install the required dependencies by running `pip install -r requirements.txt` in your terminal or command prompt.
3. Create a new Discord bot and get the bot token. You can do this by following the Discord Developer Portal documentation.
4. Create a `config.json` file in the root directory of the project and add your bot token in the following format:

```json
{
  "token": "YOUR_BOT_TOKEN"
}
```

5. Invite the bot to your Discord server using the OAuth2 URL generated in the Discord Developer Portal.
6. Run the bot by executing python bot.py in your terminal or command prompt.

## Usage
Once the bot is running and connected to your Discord server, you can use the following commands to control the music playback:

!play <song>: Searches for the provided song on YouTube and plays it.
!pause: Pauses the currently playing song.
!resume: Resumes the paused song.
!skip: Skips the current song and plays the next song in the queue.
!stop: Stops the music playback and clears the queue.
!queue: Displays the current music queue.
!volume <value>: Sets the volume of the bot. Value should be between 0 and 100.
!lyrics: Displays the lyrics of the currently playing song.
!shuffle: Shuffles the music queue.
!repeat: Repeats the currently playing song.
Feel free to modify and enhance the bot according to your specific requirements.
  
## Todo

- Play music from Spotify: DJ Fayrouz can search and play music from Spotify by providing the song title or URL.
- Play a whole playlist: DJ Fayrouz can search and play playlists by providing the URL.

##Contributions
Contributions to DJ Fayrouz Discord Bot are welcome! If you find any issues or have ideas for new features, please open an issue on the GitHub repository. You can also fork the repository, make your changes, and submit a pull request.
