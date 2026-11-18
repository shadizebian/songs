GUESS THE SONG - SETUP

1. Open songs.js in Notepad or another text editor.
2. Replace the three example entries with your words and filenames:
   { word: "HEART", audio: "heart.mp3" },
   { word: "NIGHT", audio: "night.mp3" }
3. Place the actual audio files in the audio folder.
4. Double-click index.html to open the game in your browser.

Folder layout:
  song_word_game/
    index.html
    songs.js
    audio/
      heart.mp3
      night.mp3

The sample entries are placeholders. Add matching audio files or replace them.
Audio playback begins only when Play Song is clicked.
Next stops the previous audio and shows the next word.
Shuffle randomizes the order and restarts the game.
