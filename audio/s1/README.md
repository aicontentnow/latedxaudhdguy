# Season 1 Soundtrack

Drop MP3 files into this folder, then update tracks.json.

## tracks.json format

```json
[
  { "title": "Song Title Here", "file": "filename.mp3" },
  { "title": "Another Song",    "file": "another-song.mp3" }
]
```

The player fetches this file on page load and builds the playlist automatically.
Tracks play in random order. Add as many as you want.

## Workflow

1. Drop MP3 into this folder
2. Add an entry to tracks.json
3. Git push (or ask me to do it)
4. Track appears in the player immediately
