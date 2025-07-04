# txtpod

**txtpod** is a personal audio feed that turns text into voice and publishes it as a podcast.

this repo contains:

- mp3 audio files generated from articles
- a self-updating `feed.xml` podcast file

## how it works

1. i share an article url to the txtpod ios app
2. the app fetches and cleans the text
3. it uses google gemini, siri or azure speech to generate tts audio
4. the audio and rss feed get committed to this repo
5. podcast players subscribed to the feed auto-pick up new episodes

just having some fun
