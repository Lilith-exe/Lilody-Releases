# Lilody 💜

Let your viewers pick the next song. Lilody brings requests from Twitch, Kick and YouTube into one Spotify queue and shows what’s playing on your stream.

**[Download Lilody for Windows](https://github.com/Lilith-exe/Lilody-Releases/releases/latest)**

## Get started

1. Download the **Windows x64 ZIP** from the latest release and extract the whole folder.
2. Open **Lilody.exe**. Keep the `app` and `runtime` folders beside it.
3. Follow **Setup Guide** to connect your Spotify Premium account and Streamer.bot. Choose the chats where you want to accept requests.
4. Play something in Spotify and type `!sr` followed by a song name in chat.

Already using a desktop build? Exit it from the tray before opening the new copy. Lilody picks up your saved queue and settings.

## Run your stream

| When you want to… | Here’s how |
|---|---|
| Request a song | Type `!sr artist and song` or paste a Spotify track link after `!sr`. |
| See what's playing or coming up | Type `!np` or `!sq`. The **Commands** page lists the rest. |
| Change the order | Open **Queue**. Drag a song by its handle and drop it on the top or bottom half of another row. Click the bin beside a request to remove it. Songs already sent to Spotify stay in place. |
| Close submissions | Click the padlock on **Queue**. **Pause Queue** separately pauses sending requests to Spotify. |
| Add a player to OBS | In **Player Studio**, choose a layout and click **Copy Overlay Link**. Paste it into an OBS **Browser Source**. Keep Lilody running and capture Spotify audio separately. |
| Make the overlay easier to read | Adjust **Scale** for the whole player and **Text Size** for the lettering. Each layout remembers its settings. |
| Get a newer version | Open **Settings → Check for Updates**. If an update is available, Lilody asks before downloading and restarting. |

### If something looks disconnected

Open **Connections** to check Spotify and Streamer.bot. Keep Streamer.bot running with its WebSocket server started. Twitch, Kick and YouTube use the accounts you connected there. For YouTube, select a broadcast with an active live chat.
