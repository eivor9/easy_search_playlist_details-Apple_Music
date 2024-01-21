Apple Music makes some good playlists. This program will convert any Apple Music
playlist into a list making it easy to search for individual songs.

Steps:
1. Navigate to a playlist on apple music via your web browser
2. Now you want to scroll down to the bottom of the page to make sure all songs are loaded onto screen.
3. Right click a blank space between last song of playlist and the side menu bar (near the bottom of the page) and click "Inspect element"
    (if you're using safari on mac this option becomes available after enabling "Show features for web developers" from  the Advanced tab of Safari Settings/Preferences (CMD + ,)
4. Right click the highlighted tab and press Copy > HTML.
7. From here you can enter you playlist's name in between the quotes of PLAYLIST_NAME on line 1 and finally paste the HTML of your playlist in between the backticks (slanted single quotes) of const SONGS on line 2.
8. Run and enjoy the info!

Happy Searching!
