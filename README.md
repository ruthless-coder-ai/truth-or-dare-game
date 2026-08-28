# 真心话大冒险 游戏助手 🎲

Truth or Dare game helper — a single-page web app in Chinese. Self-contained
HTML with no build step or dependencies.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The game — current version |
| `index_full_function.html` | Earlier full-feature variant, kept for reference |
| `truth.mp3` | Sound cue for 真心话 (truth) |
| `dare.mp3` | Sound cue for 大冒险 (dare) |

## Running it

Open `index.html` in a browser. The audio cues need the `.mp3` files alongside
it, so keep the folder together — or serve the directory over HTTP if your
browser blocks local audio playback:

```bash
python3 -m http.server 8000
```
