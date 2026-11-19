# User Guide – AgM3U Player

## 1. Overview

AgM3U Player plays audio and video streams from M3U and M3U8 playlists. You can load your own playlist files, search for stations in the built-in radio browser, and reopen playlists in the **Files** tab.

The interface adapts to smaller screens. On touch devices, some actions that are opened with a right-click on a computer are available by pressing and holding.

## 2. Loading a playlist

1. Open the menu using the three-dot icon in the upper-right corner.
2. Under **M3U Playlist(s) laden** (Load M3U playlist(s)), select one or more `.m3u` or `.m3u8` files.
3. After loading, the streams appear in the **Player** tab. Click or tap an entry to play it.

Loaded playlists are also stored in the browser's local storage and listed in the **Files** tab. Select a saved playlist there to load it again. The built-in `_CHRISTIAN.m3u` playlist is also available.

> **Note:** Saved playlists are stored in the browser on the current device. They are not automatically available on other devices. Avoid clearing browser data if you want to keep these playlists.

## 3. Finding and playing streams

- In the **Player** tab, use the search field to filter the loaded playlist.
- Select a stream in the list to start playback.
- Use the audio or video player's controls to pause and resume playback.
- Use the previous/next buttons beside the current stream to move through the list. Video playback also has these controls overlaid on the picture.
- Use the fullscreen button to view a video full-screen.

Right-click a stream (or press and hold it on a touch device) to open its menu. Depending on the stream, the menu may include **Info** and **Homepage**. Choose **löschen** (Delete) to remove a stream from the loaded playlist; the app asks you to confirm first.

## 4. Managing playlists

Open the playlist options by right-clicking **Player** or pressing and holding it on a touch device:

- **speichern als** (Save as): Exports the current playlist as an M3U file.
- **Alphabetisch sortieren** (Sort alphabetically): Sorts the streams by title.
- **Neue Liste** (New list): Creates an empty playlist file.

Changes to a playlist are first stored in the app. To use an edited playlist outside the browser, export it using **speichern als**.

In the **Files** tab, click a saved playlist to load it. Right-click or press and hold a saved entry to open the delete option; deletion also requires confirmation. You can also right-click **Files** to open the file picker and load additional M3U files.

## 5. Searching for and adding radio stations

1. Open the **Browser** tab.
2. Enter a station name in the search field and choose **Suchen** (Search).
3. Select a result to play it. Choose **Weitere laden** (Load more) to display additional results.
4. To add a station to a playlist, first load a playlist, then open the menu for the station and choose **In die Playlist** (Add to playlist).
5. **Alle in Playlist** (Add all to playlist) adds the displayed search results after you confirm.

Stations that are already in the playlist are not added again. Searching requires an internet connection and access to radio-browser.info.

## 6. Timers

Open the menu using the three-dot icon in the upper-right corner:

- **Wiedergabe stoppen in (Minuten)** (Stop playback in minutes): Enter 1 to 90 minutes and choose **Set**. When the timer expires, the current playback is paused.
- **Stream wechseln in (Minuten)** (Change stream in minutes): Enter 1 to 90 minutes and choose **Set**. While playback is active, the player switches to the next stream when the timer expires.
- **0** disables the corresponding timer.

The timer indicators at the top show the remaining time. Click or tap an indicator to pause or resume its timer. The stream-change timer runs only during playback. While it is active, the app attempts to keep the screen awake; support depends on the browser and device.

## 7. Hearing test and sound profile

Choose **Hörtest / Klangprofil** (Hearing test / sound profile) to start the guided hearing test. Follow the prompts and indicate whether you can hear each tone. After completing the test, you can turn the generated profile on or off using **Hörprofil für die Wiedergabe verwenden** (Use hearing profile for playback). An existing profile can also be deleted in the same dialog.

The hearing test is an informal guide and is not a medical examination. Start at a low volume and stop if you feel uncomfortable. Some external streams do not allow audio processing, so the profile will not be applied to them.

## 8. Troubleshooting

- **A stream will not start:** Check your internet connection and try another playlist entry. The stream may be offline or unsupported by your browser.
- **The video is blank or will not load:** HLS/M3U8 support depends on the browser and the individual stream.
- **The radio browser returns no results:** Check the spelling and your internet connection. The external search service must be reachable.
- **A saved playlist is missing:** Make sure you are using the same browser and device, and that browser data has not been cleared.
- **The screen turns off while the stream-change timer is active:** Not all browsers and devices support the screen wake-lock feature.
